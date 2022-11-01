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
