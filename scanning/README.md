# OpenSSL overview Scanning software

This page contains an overview of any scanning software or tools for getting insight in used OpenSSL version. 

**NCSC-NL has not verified the scanning software listed below and therefore cannot guarantee the validity of said rules.
However NCSC-NL strives to provide scanning software from reliable sources.**

## Identifying

### Windows

#### Powershell

```powershell
Get-ChildItem -Recurse -File -ErrorAction SilentlyContinue -Path "C:\" -Filter "libssl*"
```