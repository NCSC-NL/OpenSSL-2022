# OpenSSL overview Scanning software

This page contains an overview of any scanning software or tools for getting insight in used OpenSSL version. 

**NCSC-NL has not verified the scanning software listed below and therefore cannot guarantee the validity of said rules.
However NCSC-NL strives to provide scanning software from reliable sources.**

## Identifying

### Docker

Docker has provided an experimental tool for verifying docker containers for containing a vulnerable OpenSSLv3 version. 

Required tool: https://github.com/docker/index-cli-plugin

```bash
docker-index cve --image $IMAGE DSA-2022–0001
```

### YARA rules

Akamai has provided a YARA rule for identifying OpenSSLv3 versions. More information: https://www.akamai.com/blog/security-research/openssl-vulnerability-how-to-effectively-prepare

```
rule openssl_version {
	strings:
		$re1 = /OpenSSL\s3\.[0-6]{1}\.[0-9]{1}[a-z]{,1}/
	
	condition:
		$re1
}
```

In case we don’t want to rely on the string, we can also look for the main application that relies on OpenSSL, but parsing the executable’s imports. This is a less foolproof method though, and should be treated as such.

```
rule pe_import_openssl {
    condition:
        pe.is_pe and
        (
            for any i in (0..pe.number_of_imports):
            (
                pe.import_details[i].library_name contains "libcrypto-3" or pe.import_details[i].library_name contains "libssl-3"
            )
        )
}
```

### Windows

#### Powershell

```powershell
Get-ChildItem -Recurse -File -ErrorAction SilentlyContinue -Path "C:\" -Filter "libssl*"
```

### Microsoft Security Solutions

#### Microsoft Defender for Cloud
Microsoft has published a blogpost with instructions for identifying Azure resources with OpenSSL installed using Microsoft Defender for Cloud.
Blogpost Microsoft: https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/new-openssl-v3-vulnerability-prepare-with-microsoft-defender-for/ba-p/3666487

#### M365 Defender / Azure Sentinel
```
DeviceTvmSoftwareInventory
| where SoftwareName contains "openssl"
| where SoftwareName contains "3.0" or SoftwareVersion contains "3.0"
| project DeviceName, SoftwareName, SoftwareVersion
```

### Linux

#### System-wide version
```bash
openssl version
```

#### Running processes running OpenSSL 3.x 
```bash
sudo lsof -n | grep libssl.so.3 
```

#### OSquery OpenSSL version check for Debian based systems
```
select name, version from deb_packages where name like "openssl" and version like "3.0%";
```

#### OSquery OpenSSL version check for Fedora/CentOS based systems
```
select name, version from rpm_packages where name like "openssl" and version like "3.0%";
```

## External scanning tools and scripts

| Source      | Notes        | Links |
|:----------------|:----------------|:---------------:|
| MalwareTech scripts | Bash + PowerShell | https://github.com/MalwareTech/SpookySSLTools |
