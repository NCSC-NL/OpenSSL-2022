# OpenSSL overview Scanning software

This page contains an overview of any scanning software or tools for getting insight in used OpenSSL version. 

**NCSC-NL has not verified the scanning software listed below and therefore cannot guarantee the validity of said rules.
However NCSC-NL strives to provide scanning software from reliable sources.**

## Identifying

runZero recently added support for [discovering-and-surfacing any endpoints which are running OpenSSL 3.0.x](https://www.runzero.com/blog/what-you-need-to-know-about-openssl/). (versions v2.3.6+ of their [Explorer and Scanner](https://www.runzero.com/docs/installing-an-explorer/) tools)

## Docker

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

### Microsoft Azure

#### Microsoft Defender for Cloud
Microsoft has published a blogpost with instructions for identifying Azure resources with OpenSSL installed using Microsoft Defender for Cloud.
Blogpost Microsoft: https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/new-openssl-v3-vulnerability-prepare-with-microsoft-defender-for/ba-p/3666487
