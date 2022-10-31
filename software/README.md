# Overview of software (un)affected by vulnerability
This page contains an overview of software (un)affected by the OpenSSL vulnerability. NCSC-NL and partners are attempting to maintain a list of all known vulnerable and not vulnerable software. Listed software is paired with specific information regarding which version contains the security fixes and which software still requires fixes. Please note that this vulnerability may also occur in custom software developed within your organisation. These occurrences are not registered in this overview.

## Software overview
The following status labels are in use:

| Status vulnerability | Description                                                      |
|:--------------------|:-----------------------------------------------------------------|
| Vulnerable          | Software is vulnerable to vulnerability                          |
| Fix                 | Software contains a fix for vulnerability                        |
| Workaround          | Software is vulnerable but mitigation steps are available.       |
| Not vuln            | Software is **NOT** vulnerable for vulnerability                 |
| Investigation       | Software is under investigation whether it is vulnerable or not. |

The `Version` relates to the `Status` column. If `Status` field is set to 'Vulnerable', the `Version` field indicates vulnerable version(s) if these version numbers are known to us. If `Status` is set to 'Fix', the `Version` field indicates the version(s) in which the fix was introduced. Some products do not have clear version numbers, in which case the `Version` field is empty. We advise readers to follow the provided source links for more detailed information.

## Software

| Vendor | Product | Version | OpenSSL version | Status | Reference | Notes |
|--------|---------|---------|-----------------|--------|-----------|-------|
| Arch | Arch Linux | Core | 1.1.1 | Not vuln | https://archlinux.org/packages/?name=openssl | |
| Canonical | Ubuntu | 20.04 LTS | 1.1.1 | Not vuln | https://packages.ubuntu.com/focal/openssl | |
| Canonical | Ubuntu | 22.04 LTS | 3.0.2 | Vulnerable | https://discourse.ubuntu.com/t/openssl-3-0-transition-plans/24453 | |
| CentOS | CentOS | 7.9 | 1.0.2 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| CentOS | CentOS | 8 | 1.1.1 | Not vuln| https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| CentOS | CentOS | >= 9 | 3.x | Vulnerable | https://www.redhat.com/en/blog/experience-bringing-openssl-30-rhel-and-fedora | |
| Debian | Debian | 9 "Stretch"	| 1.1.0 | Not vuln | https://packages.debian.org/stretch/openssl	| |
| Debian | Debian | 10 "Buster"	| 1.1.1	| Not vuln | https://packages.debian.org/buster/openssl | |
| Debian | Debian | 11 "Bullseye"	| 1.1.1	| Not vuln | https://packages.debian.org/bullseye/openssl | |
| Debian | Debian | 12 "Bookworm" | 3.x | Vulnerable | https://packages.debian.org/bookworm/openssl | |
| Deciso B.V. | OPNsense | 22 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ |
| Fedora | Linux | 35 | 1.1.1 | Not vuln | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | | 
| Fedora | Linux | 36 | 3.0.2 | Vulnerable | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| Fedora | Linux | 37 | 3.0.5 | Vulnerable | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| Fedora | Linux | Rawhide | 3.0.5 | Vulnerable | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| Linux Mint | Linux Mint | 21 Vanessa | 3.0.2 | Vulnerable | http://packages.linuxmint.com/search.php?release=vanessa&section=any&keyword=openssl | 
| Node.js | Javascript Runtime Environment | 18 | 3.x | Investigation | Node.js 18 updates OpenSSL support, enables fetch API | InfoWorld	|
| Offensive Security | Kali | 2022.3 | 3.0.5 | Vulnerable | https://pkg.kali.org/pkg/openssl | 
| OpenMandriva | OpenMandriva | 4.3 | 3.0.3 | Vulnerable | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenMandriva | OpenMandriva | Cooker | 3.0.6 | Vulnerable | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenMandriva | OpenMandriva | Cooker | 3.0.6 | Vulnerable | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| Deciso B.V. | OPNsense | 22 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ |
| OpenSUSE | Leap | 15.3 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.4 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.2 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.3 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.4 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenVPN | OpenVPN | <= 2.5.7 | < 3.0 | Investigation | https://en.wikipedia.org/wiki/OpenVPN | https://openvpn.net/community-downloads/ Support for OpenSSL 3 in later version: OpenVPN 2.6. |
| Proxmox Server Solutions GmbH| Proxmox | 6 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ |
| PHP | PHP | < 8.1 | < 3.0 | Not vuln | https://www.php.net/manual/en/openssl.requirements.php | | 
| PHP	| PHP	| >= 8.1 | Unknown | Investigation | https://www.php.net/manual/en/openssl.requirements.php | |
| Red Hat | Enterprise Linux | >= 9.0 | 3.x	| Vulnerable | https://www.redhat.com/en/blog/experience-bringing-openssl-30-rhel-and-fedora	| | 
| Rocky Enterprise Software Foundation | Rock Linux | 9.0 (Blue Onyx) | 3.0.1 | Vulnerable | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ |
| Slackware | Slackware Linux | 14 | 1.0.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ |
