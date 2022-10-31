# OpenSSL overview Scanning software

This page contains an overview of any scanning software or tools for getting insight in used OpenSSL version. 

**NCSC-NL has not verified the scanning software listed below and therefore cannot guarantee the validity of said rules.
However NCSC-NL strives to provide scanning software from reliable sources.**

## Identifying


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
