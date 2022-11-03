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
| 3CX | All | Unknown | Unknown | Not vuln | https://www.3cx.com/community/threads/openssl-warns-of-critical-security-vulnerability.117443/#post-544312 | |
| Acronis | Cyber Protect Cloud | C22.10 | < 3.x | Not vuln | https://security-advisory.acronis.com/advisories/SEC-5299 | |
| Acronis | Cyber Protect Home Office | 2022 | < 3.x | Not vuln | https://security-advisory.acronis.com/advisories/SEC-5299 | |
| Acronis | Cyber Protect | 15 | < 3.x | Not vuln | https://security-advisory.acronis.com/advisories/SEC-5299 | |
| AlmaLinux OS Foundation | AlmaLinux | 9 | 3.0.1-43 | Fix | https://repo.almalinux.org/almalinux/9/BaseOS/x86_64/os/Packages/openssl-3.0.1-43.el9_0.x86_64.rpm | |
| AlmaLinux OS Foundation | AlmaLinux | 8 | 1.1.1k | Not vuln | https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/openssl-1.1.1k-7.el8_6.x86_64.rpm| |
| Alpine | Alpine Linux | Edge | 3.0.7-r0 | Fix | https://pkgs.alpinelinux.org/packages?name=openssl&branch=edge&repo=&arch=&maintainer= | |
| Alpine | Alpine Linux | 3.15, 3.16 | 3.0.7-r0 | Fix | https://pkgs.alpinelinux.org/packages?name=openssl3&branch=v3.16&repo=&arch=&maintainer= | optional, non-default package |
| Alpine | Alpine Linux | <= 3.14 | 1.1.1 | Not vuln | https://pkgs.alpinelinux.org/packages?name=openssl&branch=v3.16&repo=&arch=&maintainer= | |
| ALT Linux Ltd | ALT Linux | p10 | 1.1.1q | Not vuln | https://distrib-coffee.ipsl.jussieu.fr/pub/linux/altlinux/p10/branch/x86_64/RPMS.classic/openssl-1.1.1q-alt1.x86_64.rpm| |
| ALT Linux Ltd | ALT Linux | p9 | 1.1.1n | Not vuln | https://distrib-coffee.ipsl.jussieu.fr/pub/linux/altlinux/p9/branch/x86_64/RPMS.classic/openssl-1.1.1n-alt2.x86_64.rpm| |
| Amazon | Amazon Linux | 2 | 1.0.2k | Not vuln | https://docs.aws.amazon.com/linux/al2022/ug/compare-al2-to-AL2022.html#openssl3 | |
| Amazon | Amazon Linux | 2022 | 3.0.5-1 | Vulnerable | https://docs.aws.amazon.com/linux/al2022/ug/compare-al2-to-AL2022.html#openssl3 | |
| Arch | Arch Linux | Core | 1.1.1 | Not vuln | https://archlinux.org/packages/?name=openssl | |
| Argo Project | Argo CD | 2.5.1 | 3.0.2-0ubuntu1.7 | Fix | https://github.com/argoproj/argo-cd/releases/tag/v2.5.1 | fixes for older versions are in 2.3.11, 2.2.16, 2.4.16 |
| Arista | All | All | Unknown | Not vuln | https://www.arista.com/en/support/advisories-notices/security-advisory/16339-security-advisory-0081 | |
| Aruba | All | All | Unknown | Not vuln | https://asp.arubanetworks.com/notifications/Tm90aWZpY2F0aW9uOjEzMjAw;notificationCategory=Security | |
| ASUSWRT-MERLIN | ASUSWRT-MERLIN | 386/NG | 1.1.1q | Not vuln | https://www.asuswrt-merlin.net/changelog | |
| Atlassian | Bitbucket Cloud | All | Unknown | Investigation | https://community.atlassian.com/t5/Trust-Security-articles/Atlassian-s-Response-to-the-OpenSSLv3-Vulnerability/ba-p/2179584 | |
| Atlassian | Bitbucket Server | All | Unknown | Investigation | https://community.atlassian.com/t5/Trust-Security-articles/Atlassian-s-Response-to-the-OpenSSLv3-Vulnerability/ba-p/2179584 | |
| Atlassian | Bitbucket Datacenter | All | Unknown | Investigation | https://community.atlassian.com/t5/Trust-Security-articles/Atlassian-s-Response-to-the-OpenSSLv3-Vulnerability/ba-p/2179584 | |
| Atlassian | Confluence Cloud | All | Unknown | Investigation | https://community.atlassian.com/t5/Trust-Security-articles/Atlassian-s-Response-to-the-OpenSSLv3-Vulnerability/ba-p/2179584 | |
| Atlassian | Confluence Server | All | Unknown | Investigation | https://community.atlassian.com/t5/Trust-Security-articles/Atlassian-s-Response-to-the-OpenSSLv3-Vulnerability/ba-p/2179584 | |
| Atlassian | Confluence Datacenter | All | Unknown | Investigation | https://community.atlassian.com/t5/Trust-Security-articles/Atlassian-s-Response-to-the-OpenSSLv3-Vulnerability/ba-p/2179584 | |
| Atlassian | Jira Cloud | All | Unknown | Investigation | https://community.atlassian.com/t5/Trust-Security-articles/Atlassian-s-Response-to-the-OpenSSLv3-Vulnerability/ba-p/2179584 | |
| Atlassian | Jira Server | All | Unknown | Investigation | https://community.atlassian.com/t5/Trust-Security-articles/Atlassian-s-Response-to-the-OpenSSLv3-Vulnerability/ba-p/2179584 | |
| Atlassian | Jira Datacenter | All | Unknown | Investigation | https://community.atlassian.com/t5/Trust-Security-articles/Atlassian-s-Response-to-the-OpenSSLv3-Vulnerability/ba-p/2179584 | |
| Barracuda | Web Application Firewall Vx | All | 1.1.1 | Not vuln | [Ticket Answer](vendor-statements/openssl_Barracuda-Web-Application-Firewall.png) | |
| Barracuda | Email Security Gateway Vx  | All | Unknown | Not vuln | [Ticket Answer](vendor-statements/openssl_Barracuda-Email-Secure-Gateway.png) | |
| Barracuda | Web Security Gateway  | All | Unknown | Not vuln | [Ticket Answer](vendor-statements/openssl_Barracuda-Web-Secure-Gateway.png) | |
| Bitdefender | Bitdefender Endpoint Security | All | Unknown | Investigation | https://www.bitdefender.com/business/support/en/77209-80152-open-source-software-used-by-bitdefender-enterprise-products.html | |
| Bitdefender | Bitdefender Security for Mobile | All | Unknown | Investigation | https://www.bitdefender.com/business/support/en/77209-80152-open-source-software-used-by-bitdefender-enterprise-products.html | |
| Bitdefender | Bitdefender GravityZone Management Appliance | All | Unknown | Investigation | https://www.bitdefender.com/business/support/en/77209-80152-open-source-software-used-by-bitdefender-enterprise-products.html | |
| Broadcom | Symantec Endpoint Protection Manager | 14.3 RU5 | 3.0.2 | Vulnerable | https://community.broadcom.com/symantecenterprise/discussion/which-is-the-openssl-version-in-sepm-143-ru5 | |
| Broadcom | Symantec Endpoint Protection Manager | 14.3 RU6 | 3.0.7 | Not Vulnerable | https://community.broadcom.com/symantecenterprise/discussion/which-is-the-openssl-version-in-sepm-143-ru5 | Fixed version not released yet. |
| Broadcom | Symantec SiteMinder | All | 1.0.2 | Not vuln | https://knowledge.broadcom.com/external/article/245955/openssl-vulnerability-in-symantec-sitemi.html | |
| Buildroot | Buildroot | 2022.08.1 | 1.1.1q | Not vuln | https://github.com/buildroot/buildroot/blob/master/package/libopenssl/libopenssl.mk#L7 | OpenSSL 1.1.1q is the default version. |
| Canonical | Ubuntu | bionic (18.04 LTS) | 1.1.1 | Not vuln | https://packages.ubuntu.com/search?suite=bionic&keywords=openssl | |
| Canonical | Ubuntu | impish (21.10) | 1.1.1 | Not vuln | https://packages.ubuntu.com/search?suite=impish&keywords=openssl | |
| Canonical | Ubuntu | focal (20.04 LTS) | 1.1.1 | Not vuln | https://packages.ubuntu.com/search?suite=focal&keywords=openssl | |
| Canonical | Ubuntu | jammy (22.04 LTS) | 3.0.2-0ubuntu1.7 | Fix | https://packages.ubuntu.com/search?suite=jammy&keywords=openssl | |
| Canonical | Ubuntu | kinetic (22.10) | 3.0.5-2ubuntu2 | Fix | https://packages.ubuntu.com/search?suite=kinetic&keywords=openssl | |
| Canonical | Ubuntu | Squid | 3.0.5 5 | Vulnerable | https://hub.docker.com/r/ubuntu/squid/tags | |
| CentOS | CentOS | 7.9 | 1.0.2 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| CentOS | CentOS | 8 | 1.1.1 | Not vuln| https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| CentOS | CentOS | 9 | 3.0.1-43 | Fix | https://gitlab.com/redhat/centos-stream/rpms/openssl/-/commit/39f800af50db23de7aa01ebd56c8132589ad36a8 | |
| Check Point | All | All | 1.1.1 | Not vuln | https://supportcenter.checkpoint.com/supportcenter/portal?eventSubmit_doGoviewsolutiondetails=&solutionid=sk92447&partition=Basic&product=All | |
| Cisco | Application Policy Infrastructure Controller (APIC) | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Container Platform | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Data Center Network Manager (DCNM) | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Elastic Services Controller (ESC) | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Evolved Programmable Network Manager | Unknown | Unknown | Investigation | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | HyperFlex System | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | IoT Field Network Director | Unknown | Unknown | Investigation | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | Formerly known as Connected Grid Network Management System |
| Cisco | Nexus Dashboard, formerly known as Application Services Engine | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Prime Infrastructure | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | SD-WAN vAnalytics Software | Unknown | Unknown | Investigation | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | SD-WAN vManage Software | Unknown | Unknown | Investigation | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Ultra Cloud Core - Network Repository Function | Unknown | Unknown | Investigation | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Ultra Cloud Core - Policy Control Function | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Ultra Cloud Core - Redundancy Configuration Manager | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Ultra Cloud Core - Serving Gateway Function | Unknown | Unknown | Investigation | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Ultra Cloud Core - Subscriber Microservices Infrastructure | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Cisco | Ultra Cloud Core - User Plane Function | Unknown | Unknown | Not vuln | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Citrix | Citrix ADC (NetScaler ADC) and Citrix Gateway (NetScaler Gateway)   | Unknown | Unknown | Not vuln | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Application Delivery Management (NetScaler MAS)   | Unknown | Unknown | Investigation | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Cloud Connector   | Unknown | Unknown | Not vuln | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Connector Appliance for Cloud Services   | Unknown | Unknown | Not vuln | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Connector Appliance for Cloud Services   | Unknown | Unknown | Investigation | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Endpoint Management (Citrix XenMobile Server)   | Unknown | Unknown | Not vuln | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Hypervisor (XenServer)   | Unknown | Unknown | Not vuln | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix License Server   | Unknown | Unknown | Not vuln | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix SD-WAN   | Unknown | Unknown | Investigation | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix ShareFile StorageZones Controller   | Unknown | Unknown | Investigation | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Virtual Apps and Desktops (XenApp & XenDesktop)   | Unknown | Unknown | Investigation | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Workspace App for Linux   | Unknown | Unknown | Not vuln | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Workspace App for Mac   | Unknown | Unknown | Not vuln | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Citrix | Citrix Workspace App for Windows   | Unknown | Unknown | Investigation | https://support.citrix.com/article/CTX473026/impact-of-open-ssl-30-vulnerabilities-cve20223602-cve20223786-on-citrix-products | |
| Cloudflare | all | all | Unknown | Not vuln | https://blog.cloudflare.com/cloudflare-is-not-affected-by-the-openssl-vulnerabilities-cve-2022-3602-and-cve-2022-37/ | |
| Code42 | Incydr | ALL | 1.x | Not vuln | [Code42 Response to Industry Security Incidents](https://support.code42.com/Terms_and_conditions/Code42_customer_support_resources/Code42_response_to_industry_security_incidents) | |
| cPanel | All | All | Unknown | Not vuln | https://support.cpanel.net/hc/en-us/articles/4416312844055-Is-cPanel-affected-by-OpenSSL-Security-Advisory-CVE-2021-4044- | |
| Debian | Debian | 9 "Stretch"	| 1.1.0 | Not vuln | https://packages.debian.org/stretch/openssl	| |
| Debian | Debian | 10 "Buster"	| 1.1.1	| Not vuln | https://packages.debian.org/buster/openssl | |
| Debian | Debian | 11 "Bullseye"	| 1.1.1	| Not vuln | https://packages.debian.org/bullseye/openssl | |
| Debian | Debian | 12 "Bookworm" | 3.x | Vulnerable | https://packages.debian.org/bookworm/openssl | _testing_ (not yet released) |
| Deciso B.V. | OPNsense | 22 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ |
| DigiCert | all | all | Unknown | Not vuln | https://www.digicert.com/blog/openssl-releases-patch-for-high-level-vulnerability-in-3-0-and-above | |
| Dockerhub | aerospike | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | alpine | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | arangodb | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | backdrop | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | bonita | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | buildpack-deps | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | busybox | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | cassandra | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | celery | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | centos | latest | 3.x | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | chronograf | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | cirros | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | clojure | latest | 3.0.2 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:deb/ubuntu/openssl@3.0.2-0ubuntu1.6?os_distro=jammy&os_name=ubuntu&os_version=22.04; ; Instruction: /bin/sh -c #(nop) ADD file:ba96f963bbfd429a0839c40603fdd7829eaca58f20adfa0d15e6beae8244bc08 in /; Layer 0: sha256:301a8b74f71f85f3a31e9c7e7fedd5b001ead5bcf895bc2911c1d260e06bd987 |
| Dockerhub | consul | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | couchbase | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | couchdb | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | crate | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | crux | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | debian | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | django | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | docker | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | drupal | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | elixir | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | erlang | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | fedora | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | gazebo | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | gcc | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | ghost | latest | 3.x | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | glassfish | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | golang | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | haproxy | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | haskell | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | hello-world | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | hipache | latest | 3.x | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | httpd | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | hylang | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | iojs | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | irssi | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | jetty | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | joomla | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | jruby | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | julia | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | kaazing-gateway | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | lightstreamer | latest | 3.0.2 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:deb/ubuntu/openssl@3.0.2-0ubuntu1.6?os_distro=jammy&os_name=ubuntu&os_version=22.04; ; Instruction: /bin/sh -c #(nop) ADD file:ba96f963bbfd429a0839c40603fdd7829eaca58f20adfa0d15e6beae8244bc08 in /; Layer 0: sha256:301a8b74f71f85f3a31e9c7e7fedd5b001ead5bcf895bc2911c1d260e06bd987 |
| Dockerhub | mageia | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | mariadb | latest | 3.0.2 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:deb/ubuntu/openssl@3.0.2-0ubuntu1.6?os_distro=jammy&os_name=ubuntu&os_version=22.04; ; Instruction: /bin/sh -c #(nop) ADD file:ba96f963bbfd429a0839c40603fdd7829eaca58f20adfa0d15e6beae8244bc08 in /; Layer 0: sha256:301a8b74f71f85f3a31e9c7e7fedd5b001ead5bcf895bc2911c1d260e06bd987 |
| Dockerhub | maven | latest | 3.0.2 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:deb/ubuntu/openssl@3.0.2-0ubuntu1.6?os_distro=jammy&os_name=ubuntu&os_version=22.04; ; Instruction: /bin/sh -c #(nop) ADD file:ba96f963bbfd429a0839c40603fdd7829eaca58f20adfa0d15e6beae8244bc08 in /; Layer 0: sha256:301a8b74f71f85f3a31e9c7e7fedd5b001ead5bcf895bc2911c1d260e06bd987 |
| Dockerhub | memcached | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | mongo-express | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | mongo | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | mono | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | mysql | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | nats | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | neo4j | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | neurodebian | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | nginx | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | node | latest | 3.x | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:github/nodejs/node@19.0.0; ; Instruction: /bin/sh -c groupadd --gid 1000 node   && useradd --uid 1000 --gid node --shell /bin/bash --create-home node; Layer 6: sha256:f699dd37397dc8c9014384aff075343f3ef47f8a955bab08f62cb459df8929f0 |
| Dockerhub | nuxeo | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | odoo | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | orientdb | latest | 3.0.2 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:deb/ubuntu/openssl@3.0.2-0ubuntu1.6?os_distro=jammy&os_name=ubuntu&os_version=22.04; ; Instruction: /bin/sh -c #(nop) ADD file:ba96f963bbfd429a0839c40603fdd7829eaca58f20adfa0d15e6beae8244bc08 in /; Layer 0: sha256:301a8b74f71f85f3a31e9c7e7fedd5b001ead5bcf895bc2911c1d260e06bd987 |
| Dockerhub | owncloud | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | percona | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | perl | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | photon | latest | 3.0.6 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:rpm/photon/openssl@3.0.6-1.ph4?os_name=photon&os_version=4; ; Instruction: /bin/sh -c #(nop) ADD file:7b9533117763ef391712376da8c6c2bea7675c2a8d3d088b9c76c61885906404 in /; Layer 0: sha256:4a67cc17bbc78d5a23e5c97998754f5fe74254a76a5363e58222100caaa6517a |
| Dockerhub | php-zendserver | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | php | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | piwik | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | postgres | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | pypy | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | python | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | r-base | latest | 3.0.4 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:deb/debian/openssl@3.0.4-2?os_name=debian&os_version=unstable; ; Instruction: /bin/sh -c #(nop)  LABEL org.opencontainers.image.licenses=GPL-2.0-or-later org.opencontainers.image.source=https://github.com/rocker-org/rocker org.opencontainers.image.vendor=Rocker Project org.opencontainers.image.authors=Dirk Eddelbuettel <edd@debian.org>; Layer 2: sha256:d06267fca963eae8a21b9c01db4027c0fce62c50c1b2af7e1b64ee3831395be9 |
| Dockerhub | rabbitmq | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | rails | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | rakudo-star | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | redis | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | redmine | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | registry | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | rethinkdb | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | rocket.chat | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | ros | latest | 3.0.2 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:deb/ubuntu/openssl@3.0.2-0ubuntu1.6?os_distro=jammy&os_name=ubuntu&os_version=22.04; ; Instruction: /bin/sh -c #(nop) ADD file:ba96f963bbfd429a0839c40603fdd7829eaca58f20adfa0d15e6beae8244bc08 in /; Layer 0: sha256:301a8b74f71f85f3a31e9c7e7fedd5b001ead5bcf895bc2911c1d260e06bd987 |
| Dockerhub | ruby | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | sentry | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | solr | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | sonarqube | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | sourcemage | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | swarm | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | thrift | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | tomcat | latest | 3.0.2 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:deb/ubuntu/openssl@3.0.2-0ubuntu1.6?os_distro=jammy&os_name=ubuntu&os_version=22.04; ; Instruction: /bin/sh -c #(nop) ADD file:ba96f963bbfd429a0839c40603fdd7829eaca58f20adfa0d15e6beae8244bc08 in /; Layer 0: sha256:301a8b74f71f85f3a31e9c7e7fedd5b001ead5bcf895bc2911c1d260e06bd987 |
| Dockerhub | tomee | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | traefik | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | ubuntu-debootstrap | latest | 3.x | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | ubuntu-upstart | latest | 3.x | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | ubuntu | latest | 3.0.2 | Vulnerable | https://dso.docker.com/cve/DSA-2022-0001 | pkg:deb/ubuntu/openssl@3.0.2-0ubuntu1.6?os_distro=jammy&os_name=ubuntu&os_version=22.04; ; Instruction: /bin/sh -c #(nop) ADD file:ba96f963bbfd429a0839c40603fdd7829eaca58f20adfa0d15e6beae8244bc08 in /; Layer 0: sha256:301a8b74f71f85f3a31e9c7e7fedd5b001ead5bcf895bc2911c1d260e06bd987 |
| Dockerhub | websphere-liberty | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dockerhub | wordpress | latest | < 3.x | Not vuln | https://dso.docker.com/cve/DSA-2022-0001 |  |
| Dynatrace | All | All | Unknown | Not vuln | https://www.dynatrace.com/news/security-alert/openssl-3-x-vulnerability/ | |
| Elastic | All | All | OpenSSL Unknown | Not vuln | https://discuss.elastic.co/t/elastic-security-statement-for-openssl-cve-2022-3786-and-cve-2022-3602-openssl-version-3-0-7/318039 | |
| EuroLinux | EuroLinux | 8 | 1.1.1k | Not vuln | https://vault.cdn.euro-linux.com/sources/eurolinux/8/baseos/x86_64/Packages/o/openssl-1.1.1k-7.el8_6.src.rpm | |
| EuroLinux | EuroLinux | 9 | 3.0.1 | Vulnerable | https://fbi.cdn.euro-linux.com/dist/eurolinux/server/9/x86_64/BaseOS/all/Packages/o/openssl-3.0.1-41.el9_0.x86_64.rpm | |
| Esri | ArcGIS | All | Unknown | Investigation | https://www.esri.com/arcgis-blog/products/trust-arcgis/administration/openssl-v3-vulnerability/ | |
| F5 Networks | BIG-IP | All | < 3.x | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | BIG-IP SPK | 1.x | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | BIG-IQ Centralized Management | All | < 3.x | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | F5OS-A | 1.x | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | F5OS-C | 1.x | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX API Connectivity Manager | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX App Protect DoS | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX App Protect WAF | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Controller Application Delivery | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Controller API Management | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Ingress Controller | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Instance Manager | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Plus | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Service Mesh | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Unit | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | Traffix SDC | All | < 3.x | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| Fedora | Linux | 35 | 1.1.1 | Not vuln | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | | 
| Fedora | Linux | 36 | 3.0.2-4.fc36 | Fix | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| Fedora | Linux | 37 | 3.0.5-2.fc37 | Fix | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| Fedora | Linux | Rawhide | 3.0.5-6.fc38 | Fix | https://packages.fedoraproject.org/pkgs/openssl/openssl/fedora-rawhide.html | |
| Fedora | EPEL | 7 | 1.1.1k | Not vuln | https://packages.fedoraproject.org/pkgs/openssl11/openssl11/ | |
| Fedora | EPEL | 8 | 3.0.1-43 | Fix | https://bodhi.fedoraproject.org/updates/FEDORA-EPEL-2022-e228f64914 | |
| FileCap | FileCap Server | All | < 3.x | Not vuln | https://github.com/NCSC-NL/OpenSSL-2022/blob/main/software/vendor-statements/FileCap.png | | 
| Fortinet | FortiADC | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiADCManager | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAIOps | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAnalyzer | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAnalyzer-BigData | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAnalyzer Cloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAP | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAP-C | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAPCloud | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAP-S | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAP-U | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAuthenticator | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiCASB | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiCentral | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiClient Cloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiClientEMS | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiClientLinux | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiClientMac | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiClientWindows | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiCloud | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiConnect | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiConverter | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiDDoS | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiDDoS-F | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiDeceptor | All | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiDevSec | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiEdge | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiEDR | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiExtender Cloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiFone | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiGuest | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiInsight | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiIsolator | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiLANCloud | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiMail | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiManager | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiManager Cloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiMoM | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiNAC | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiNDR | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiOS | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiPAM | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiPentest | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiPhish | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiPolicy | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiPortal | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiPresence | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiProxy | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiRecorder | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiSandbox | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiSandbox Cloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiSASE | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiSIEM | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiSOAR | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiSwitch | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiSwitchManager | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiSwitch Cloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiTester | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiTokenAndroid | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiToken Cloud | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiTokenIOS | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiVoiceEnterprise | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiVoiceUC | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiVoiceUCDesktop | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWAN | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWeb | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWebCloud | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiWebManager | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWLC | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWLM | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| FreeBSD | FreeBSD | 13 | 1.1.1q | Not vuln | https://pkg.freebsd.org/FreeBSD:13:amd64/latest/All/openssl-1.1.1q,1.pkg| |
| FreeBSD | FreeBSD | 12 | 1.1.1q | Not vuln | https://pkg.freebsd.org/FreeBSD:12:amd64/quarterly/All/openssl-1.1.1q,1.pkg| |
| Gentoo Foundation | Gentoo Linux | Rolling | 1.1.1s | Not vuln | https://packages.gentoo.org/packages/dev-libs/openssl | |
| Gentoo Foundation | Gentoo Linux | Rolling | 3.0.7 | Fix | https://packages.gentoo.org/packages/dev-libs/openssl | |
| GitLab B.V. | Gitlab | 15.5.2, 15.4.4, and 15.3.5 | 3.0.2-0ubuntu1.7 | Fix | https://about.gitlab.com/releases/2022/11/02/security-release-gitlab-15-5-2-released/ | "The version of openssl has been updated to 3.0.2-0ubuntu1.7 in order to mitigate security concerns." |
| Governikus | Ausweis 2 | 1.24.4 | 3.0.7 | Fix | https://github.com/Governikus/AusweisApp2/releases/tag/1.24.4 | OpenSSL 3.0.5 was intruduced with Version 1.24 |
| HashiCorp| All | Unknown | Unknown | Not vuln | https://discuss.hashicorp.com/t/hcsec-2022-27-hashicorp-response-to-openssl-security-announcement-regarding-november-1-release/46192/3 | |
| Homebrew | Brew | openssl@3 | 3.0.7 | Fix | https://formulae.brew.sh/formula/openssl@3 | |
| Huawei | openEuler | 20.03 LTS | 1.1.1d | Not vuln | https://www.openeuler.org/en/security/safety-bulletin/detail/?id=openEuler-SA-2022-1833 | |
| Huawei | openEuler | 22.03 LTS | 1.1.1m | Not vuln | https://www.openeuler.org/en/security/safety-bulletin/detail/?id=openEuler-SA-2022-1833 | |
| Huawei | openEuler | 22.09 | 1.1.1m | Not vuln | https://gitee.com/src-openeuler/openssl/tree/openEuler-22.09/ | |
| IBM | All | Unknown | Unknown | Investigation | https://www.ibm.com/support/pages/node/6833428 | |
| IBM | Websphere Application Server | All | Unknown | Not vuln | https://www.ibm.com/support/pages/node/6832478 | |
| IBM | Liberty | All | Unknown | Not vuln | https://www.ibm.com/support/pages/node/6832478 | |
| IBM | HTTP Server | All | Unknown | Not vuln | https://www.ibm.com/support/pages/node/6832478 | |
| Infoblox | BloxOne | All | Unknown | Not vuln | https://support.infoblox.com/s/article/000008377 | |
| Infoblox | NetMRI | All | Unknown | Not vuln | https://support.infoblox.com/s/article/000008377 | |
| Infoblox | NIOS | All | Unknown | Not vuln | https://support.infoblox.com/s/article/000008377 | |
| Intel | System Usage Report (Codename: Queencreek) | 2.4.0.8919 | 3.0.2 | Vulnerable | [Local Proof](vendor-statements/openssl_queencreek.png) | |
| Ivanti | All | Unknown | Unknown | Not vuln | https://www.ivanti.com/blog/openssl-3-0-x-security-vulnerability-impact-on-ivanti-solutions | |
| JFrog | All | All | Unknown | Not vuln | https://jfrog.com/knowledge-base/upcoming-openssl-3-x-critical-vulnerability/ |  |
| Juniper | JunOS| All | Unknown | Not vuln | https://supportportal.juniper.net/s/article/2022-11-Out-of-Cycle-Security-Bulletin-High-severity-security-issues-resolved-in-OpenSSL-3-0-7-CVE-2022-3602-CVE-2022-3786?language=en_US | |
| Juniper | JunOS Evolved | >22.1R1-EVO | Unknown | Workaround | https://supportportal.juniper.net/s/article/2022-11-Out-of-Cycle-Security-Bulletin-High-severity-security-issues-resolved-in-OpenSSL-3-0-7-CVE-2022-3602-CVE-2022-3786?language=en_US | |
| KaOS | KaOS | rolling | 1.1.1.18 | Not vuln | http://mirror6.layerjet.com/kaos/core/openssl-1.1.1.18-1-x86_64.pkg.tar.zst| |
| Kemp | LoadMaster | 7.2.58 | 1.1.1n | Not vuln | https://support.kemptechnologies.com/hc/en-us/articles/10228770842637-Current-OpenSSL-Version-for-LoadMaster | |
| Linux Mint | Linux Mint | 21 Vanessa | 3.0.2 | Vulnerable | http://packages.linuxmint.com/search.php?release=vanessa&section=any&keyword=openssl | |
| Mageia | Mageia | 8 | 1.1.1q | Not vuln | https://distrib-coffee.ipsl.jussieu.fr/pub/linux/Mageia/distrib/8/x86_64/media/core/updates/openssl-1.1.1q-1.mga8.x86_64.rpm | |
| Mageia | Mageia | cauldron | 3.0.5-2 | Fix | https://mageia.pkgs.org/cauldron/mageia-core-release-x86_64/openssl-3.0.5-2.mga9.x86_64.rpm.html | |
| Mend | All | All | Unknown | Not vuln | https://www.mend.io/resources/blog/advisory-new-openssl-critical-security-vulnerability/ | |
| Nasuni | Edge Appliance | All | Unknown | Not vuln | https://trustcenter.nasuni.com/?tcuUid=495df3df-eb99-44cf-9d8b-6ac7a3944cd7 | |
| Nasuni | Management Console | All | Unknown | Not vuln | https://trustcenter.nasuni.com/?tcuUid=495df3df-eb99-44cf-9d8b-6ac7a3944cd7 | |
| NetApp | 7-Mode Transition Tool | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | AFF Baseboard Management Controller (BMC) - A700s | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | ATTO FibreBridge | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Active IQ Unified Manager for Linux | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Active IQ Unified Manager for Microsoft Windows | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Active IQ Unified Manager for VMware vSphere | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Active IQ mobile app | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Astra Control Center - NetApp Kubernetes Monitoring Operator | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Astra Trident | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Astra Trident Autosupport | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | BeeGFS CSI Driver | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Brocade Fabric Operating System Firmware | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Brocade SAN Navigator (SANnav) | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Cloud Backup OST Plug-in (formerly AltaVault OST Plug-in) | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Cloud Data Sense | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Cloud Insights Acquisition Unit | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Cloud Insights Telegraf Agent | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Cloud Manager | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Cloud Secure Agent | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Cloud Volumes ONTAP Mediator | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Clustered Data ONTAP | All | Unknown | Vulnerable | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Clustered Data ONTAP Antivirus Connector | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Converged Systems Advisor Agent | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | E-Series BeeGFS Collection | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | E-Series BIOS | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | E-Series Host Collection | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | E-Series Performance Analyzer | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | E-Series SANtricity Collection | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | E-Series SANtricity OS Controller Software 11.x | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | E-Series SANtricity Storage Manager | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | E-Series SANtricity Unified Manager and Web Services Proxy | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Element .NET SDK | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Element HealthTools | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Element JAVA SDK | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Element Plug-in for vCenter Server | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Element Powershell Tools | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Element Python SDK | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | FAS/AFF Baseboard Management Controller (BMC) | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | FAS/AFF BIOS | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | FAS/AFF Service Processor | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Global File Cache | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | HCI Baseboard Management Controller (BMC) | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | HCI Compute Node (Bootstrap OS) | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | HCI Compute Node BIOS | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | HCI Storage Node BIOS | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Host Utilities - SAN for Linux | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Host Utilities - SAN for Windows | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Interoperability Matrix Tool | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Inventory Collect Tool | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Kubernetes Monitoring Operator | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Manageability SDK | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Management Services for Element Software and NetApp HCI | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | MetroCluster Tiebreaker for clustered Data ONTAP | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Multipath I/O (SANtricity DSM for Windows MPIO) | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | NFS Plug-in for VMware VAAI | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | ONTAP Mediator | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | ONTAP Select Deploy administration utility | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | ONTAP tools for VMware vSphere | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | OnCommand Insight | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | OnCommand Workflow Automation | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Open Systems SnapVault Agent | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SANtricity SMI-S Provider | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SANtricity Storage Plugin for vCenter | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SAS Firmware | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SRA Plugin for Linux | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SRA Plugin for Windows | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Single Mailbox Recovery | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SMI-S Provider | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Snap Creator Framework | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SnapCenter | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SnapCenter Plug-in for VMware vSphere | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SnapManager for Hyper-V | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SolidFire & HCI Management Node | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SolidFire & HCI Storage Node (Element Software) | All | Unknown | Investigation | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SolidFire Plug-in for vRealize Orchestrator (SolidFire vRO) | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | SolidFire Storage Replication Adapter | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Spot PC | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Storage Services Connector | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | StorageGRID (formerly StorageGRID Webscale) | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | StorageGRID BIOS | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | StorageGRID Baseboard Management Controller (BMC) | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | System Manager 9.x | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | Virtual Desktop Service (VDS) | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | XCP NFS | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetApp | XCP SMB | All | Unknown | Not vuln | https://security.netapp.com/advisory/ntap-20221102-0001/ | |
| NetBSD | NetBSD | 9 | 1.1.1k | Not vuln | https://cdn.netbsd.org/pub/NetBSD/NetBSD-9.3/CHANGES-9.2 |
| NetBSD | NetBSD | 8 | 1.0.2k | Not vuln | https://netbsd.org/releases/formal-8/NetBSD-8.0.html |
| NetBSD | pkgsrc | - | 1.1.1q | Not vuln | https://cdn.netbsd.org/pub/pkgsrc/current/pkgsrc/security/openssl/index.html|
| Netgate | pfSense | All | 1.1.1l | Not vuln | https://forum.netgate.com/topic/175585/does-pfsense-use-openssl-3-x-at-all/4 | |
| NixOS | NixOS | 22.05 | 1.1.1q | Not vuln | https://search.nixos.org/packages?channel=22.05&query=openssl&show=openssl | There are exceptions, e.g., nginx is built against OpenSSL 3! |
| NixOS | NixOS | unstable | 3.0.5 | Vulnerable | https://search.nixos.org/packages?channel=unstable&query=openssl&show=openssl | |
| NLnet Labs | Krill | All | 1.1.1q | Not vuln | https://twitter.com/routinator3000/status/1587517298893520903 | |
| Node.js | JavaScript Runtime Environment | 17 | 3.x | Investigation | https://github.com/nodejs/node/blob/main/doc/changelogs/CHANGELOG_V17.md#17.0.0 | Missing from Node.js security update blog post because v17 is EOL |
| Node.js | JavaScript Runtime Environment | 18 | 3.x | Vulnerable | https://nodejs.org/en/blog/vulnerability/november-2022-security-releases/ | |
| Node.js | JavaScript Runtime Environment | 19 | 3.x | Vulnerable | https://nodejs.org/en/blog/vulnerability/november-2022-security-releases/ | |
| Offensive Security | Kali | 2022.3 | 3.0.5 | Vulnerable | https://pkg.kali.org/pkg/openssl | 
| OpenMandriva | OpenMandriva | 4.3 | 3.0.3 | Vulnerable | http://abf-downloads.openmandriva.org/4.3/repository/x86_64/main/updates/openssl-3.0.3-1-omv4003.x86_64.rpm| |
| OpenMandriva | OpenMandriva | 4.2 | 3.0.0 | Vulnerable | http://abf-downloads.openmandriva.org/4.2/repository/x86_64/main/updates/openssl-3.0.0-0.alpha17.1-omv4002.x86_64.rpm| |
| OpenMandriva | OpenMandriva | rolling | 3.0.6 | Vulnerable | http://abf-downloads.openmandriva.org/rolling/repository/x86_64/main/release/openssl-3.0.6-1-omv4050.x86_64.rpm| |
| OpenMandriva | OpenMandriva | cooker | 3.0.6 | Vulnerable | http://abf-downloads.openmandriva.org/cooker/repository/x86_64/main/release/openssl-3.0.6-3-omv4090.x86_64.rpm| |
| OpenSUSE | Leap | 15.2 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.3 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.4 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | OpenSUSE | tumbleweed | 3.0.5 | Vulnerable | https://software.opensuse.org/package/openssl-3 | |
| OpenVPN | OpenVPN | <= 2.5.7 | < 3.0 | Investigation | https://en.wikipedia.org/wiki/OpenVPN | https://openvpn.net/community-downloads/ Support for OpenSSL 3 in later version: OpenVPN 2.6. | |
| Oracle | Linux | <= 8 | 1.x | Not vuln | https://linux.oracle.com/errata/ELSA-2022-9683.html | |
| Oracle | Linux | 8.x | 3.0.1 | Vulnerable | https://linux.oracle.com/errata/ELBA-2022-22325.html | Optional package |
| Oracle | Linux | >= 9.0 | 3.0.1 | Fix | https://linux.oracle.com/errata/ELSA-2022-9968.html | |
| Palo Alto Networks | AutoFocus | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Bridgecrew | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | | 
| Palo Alto Networks | Cloud NGFW | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | | 
| Palo Alto Networks | Cortex Data Lake	| * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | | 
| Palo Alto Networks | Cortex XDR Agent	| * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | | 
| Palo Alto Networks | Cortex Xpanse | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | | 
| Palo Alto Networks | Cortex XSOAR | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | | 
| Palo Alto Networks | Enterprise Data Loss Prevention | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Exact Data Matching CLI	 | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Expanse | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Expedition Migration Tool | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | GlobalProtect App | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | IoT Security | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Okyo Garde | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Palo Alto Networks App for Splunk | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | PAN-OS | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Prisma Access | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Prisma Cloud | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Prisma Cloud Compute | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Prisma SD-WAN ION | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Prisma SDWAN (Cloudgenix) | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | SaaS Security | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | User-ID Agent | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | WildFire Appliance (WF-500) | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | WildFire Cloud | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Paessler | PRTG Network Monitor | latest | Unknown | Not vuln | [Local Proof](vendor-statements/openssl_paessler_prtg.jpg) | |
| PCLinuxOS | PCLinuxOS | rolling | 1.1.1q | Not vuln | https://ftp.nluug.nl/pub/os/Linux/distr/pclinuxos/pclinuxos/apt/pclinuxos/64bit/RPMS.x86_64/openssl-1.1.1q-1pclos2022.x86_64.rpm| |
| PHP | PHP | < 8.1 | < 3.0 | Not vuln | https://www.php.net/manual/en/openssl.requirements.php | | 
| PHP	| PHP	| >= 8.1 | Unknown | Investigation | https://www.php.net/manual/en/openssl.requirements.php | |
| Progress | Chef | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Corticon | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | DataDirect+(all+components) | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | iMail | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | IMacros | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Fiddler+/+Fiddler+Everywhere | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Flowmon | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Kemp360+(Central,+Vision) | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Kemp+LoadMaster | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Kendo+UI | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Kinvey | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | MessageWay | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | MOVEit/+MOVEit+Cloud | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | NativeChat | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | OpenEdge | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Sitefinity+(all+components) | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Telerik+(Developer+Tools) | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | ThemeBuilder+/+Unite+UX | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | Test+Studio | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | WhatsUp+Gold | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Progress | WS_FTP | All | Unknown | Not vuln | https://www.progress.com/security/openssl-vulnerability-2022-11-01 | |
| Proxmox Server Solutions GmbH| Proxmox | 6 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| Proxmox Server Solutions GmbH| Proxmox | 7 | 1.1.1 | Not vuln | https://www.proxmox.com/en/news/press-releases/proxmox-virtual-environment-7-0 (EN) |Based on Debian 11, no custom OpenSSL version used. |
| PulseSecure (Ivanti) | All | Unknown | Unknown | Not vuln | https://kb.pulsesecure.net/articles/Pulse_Secure_Article/OpenSSL-3-0-x-Vulnerability-Ivanti-Product-Impact1/?kA13Z000000FseL | |
| Red Hat | Enterprise Linux | <= 8 | 1.x	| Not vuln | https://access.redhat.com/security/vulnerabilities/RHSB-2022-004	| | 
| Red Hat | Enterprise Linux | >= 9.0 | 3.0.1-43	| Fix | https://access.redhat.com/errata/RHSA-2022:7288	| | 
| Red Hat | OpenShift Container Platform | => 4.0 | 1.1.1 | Not vuln | https://access.redhat.com/security/vulnerabilities/RHSB-2022-004 | |
| Red Hat | Universal Base Images | <= 8 | 1.x | Not vuln | https://access.redhat.com/security/vulnerabilities/RHSB-2022-004 | |
| Red Hat | Universal Base Images | >= 9.0.0-1690 | 3.0.1-43 | Fix | https://access.redhat.com/security/vulnerabilities/RHSB-2022-004 | Updated container information: https://catalog.redhat.com/software/containers/ubi9/618326f8c0d15aff4912fe0b?container-tabs=packages |
| RedGate | All | * | Unknown | Not vuln | [Local Proof](vendor-statements/openssl_redgate_all.png) | |
| Rocky Enterprise Software Foundation | Rocky Linux | 8.0 | 1.1.1k | Not vuln | https://dl.rockylinux.org/pub/rocky/8/BaseOS/x86_64/os/Packages/o/openssl-1.1.1k-7.el8_6.x86_64.rpm| |
| Rocky Enterprise Software Foundation | Rocky Linux | 9.0 (Blue Onyx) | 3.0.1-43 | Fix | https://dl.rockylinux.org/pub/rocky/9/BaseOS/x86_64/os/Packages/o/openssl-3.0.1-43.el9_0.x86_64.rpm| |
| RSA (SecurID) | Access Manager | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Authentication Manager | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Authentication Agents | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Authentication Manager Prime (Packaged Solution) | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Authentication Manager Web Tier (a component of RSA Authentication Manager) | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Cloud Authentication Service | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Identity Router (a component of Cloud Authentication Service) | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Hardware and Software Authenticators | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Governance and Lifecycle (RSA G&L) | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Governance and Lifecycle Cloud (RSA G&L Cloud) | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| RSA (SecurID) | Governance and Lifecycle Data Reach (Packaged Solution) | All | Unknown | Not vuln | https://community.rsa.com/t5/securid-product-advisories/rsa-customer-advisory-openssl-3-0-7-security-patch-cve-2022-3786/ta-p/689811 | |
| SailPoint | IdentityNow (IDN) | All | 3.x.x | Vulnerable | https://community.sailpoint.com/t5/Community-Announcements/OpenSSL-3-0-x-high-severity-vulnerabilities-CVE-2022-3786-and/ba-p/224261 | |
| SailPoint | IdentityAI (IAI) | All | 3.x.x | Vulnerable | https://community.sailpoint.com/t5/Community-Announcements/OpenSSL-3-0-x-high-severity-vulnerabilities-CVE-2022-3786-and/ba-p/224261 | |
| SailPoint | IDN Virtual Appliance (VA) | All | 3.x.x | Vulnerable | https://community.sailpoint.com/t5/Community-Announcements/OpenSSL-3-0-x-high-severity-vulnerabilities-CVE-2022-3786-and/ba-p/224261 | |
| SailPoint | IdentityIQ | All | Unknown | Not vuln | https://community.sailpoint.com/t5/Community-Announcements/OpenSSL-3-0-x-high-severity-vulnerabilities-CVE-2022-3786-and/ba-p/224261 | |
| SailPoint | Cloud Access Manager | All | Unknown | Not vuln | https://community.sailpoint.com/t5/Community-Announcements/OpenSSL-3-0-x-high-severity-vulnerabilities-CVE-2022-3786-and/ba-p/224261 | |
| SailPoint | File Access Manager | All | Unknown | Not vuln | https://community.sailpoint.com/t5/Community-Announcements/OpenSSL-3-0-x-high-severity-vulnerabilities-CVE-2022-3786-and/ba-p/224261 | |
| SailPoint | Access Risk Management | All | Unknown | Not vuln | https://community.sailpoint.com/t5/Community-Announcements/OpenSSL-3-0-x-high-severity-vulnerabilities-CVE-2022-3786-and/ba-p/224261 | |
| SailPoint | SaaS Management | All | Unknown | Not vuln | https://community.sailpoint.com/t5/Community-Announcements/OpenSSL-3-0-x-high-severity-vulnerabilities-CVE-2022-3786-and/ba-p/224261 | |
| Slackware | Slackware Linux | 14.1 | 1.0.1e | Not vuln | https://slackware.uk/slackware/slackware64-14.1/slackware64/n/openssl-1.0.1e-x86_64-1.txz| |
| Slackware | Slackware Linux | 14.2 | 1.0.2h | Not vuln | https://slackware.uk/slackware/slackware64-14.2/slackware64/n/openssl-1.0.2h-x86_64-1.txz| |
| Slackware | Slackware Linux | 15.0 | 1.1.1q | Not vuln | https://slackware.uk/slackware/slackware64-15.0/patches/packages/openssl-1.1.1q-x86_64-1_slack15.0.txz| |
| Slackware | Slackware Linux | current | 1.1.1q | Not vuln | https://slackware.uk/slackware/slackware64-current/slackware64/n/openssl-1.1.1q-x86_64-1.txz| |
| Softether | Softether VPN | 4.39 Build 9772 Beta | 3.0.2 | Vulnerable | https://www.softether.org/5-download/history | |
| Solus | Solus | rolling | 1.1.1q | Not vuln | https://mirrors.rit.edu/solus/packages/shannon/o/openssl-11/openssl-11-32bit-devel-1.1.1q-15-1-x86_64.eopkg| |
| SonicWall | Analytics | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Capture Security Appliance | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Capture Client | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Connect Tunnel | <= 12.1 | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Connect Tunnel | 12.4 | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Email Security | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Global VPN Client | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | GMS | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Mobile Connect for MacOS | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Mobile Connect for iOS | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Mobile Connect for Android and ChromeOS | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NetExtender Client | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NetExtender for Linux | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NetExtender for Windows | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NSA 2600/2650/3600/3650/4600/4650/5600/5650/6600/6650 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NSA 2700/3700/4700/5700/6700 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NSA 9250/9450/9650 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NSM | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NSSP 10700/11700/13700/15700 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NSSP 12400/12800 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NSV 10/25/50/100/200/400/800/1600 (ESX, KVM, HYPER-V, AWS, Azure) | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | NSV 270/470/870 (ESX, KVM, HYPER-V, AWS, Azure) | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SM 9200/9400/9600/9800 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SMA 210/410 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SMA 500v (ESX, KVM, Hyper-V, AWS, Azure) | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SMA 6200/7200/6210/7210 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SMA 8200v (ESX, KVM, Hyper-V, AWS, Azure) | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SOHO/SOHO-W, SOHO-250 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SonicWave Access Points | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SWS 12-8/12-8POE | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SWS 12-10FPOE | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SWS 14-24/14-24FPOE | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | SWS 14-48/14-48FPOE | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | TZ300/W, TZ350/W | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | TZ400/W | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | TZ500/W | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | TZ600 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | TZ270/W | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | TZ370/W | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | TZ470/W | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | TZ570/W | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | TZ670 | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| SonicWall | Global VPN Client | All | Unknown | Not vuln | https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2022-0023 | |
| Sophos | All | All | Unknown | Not vuln | https://www.sophos.com/en-us/security-advisories/sophos-sa-20221031-openssl-vuln | [Further Information in Community Post](https://community.sophos.com/utm-firewall/f/general-discussion/137121/openssl-security-update-announced/509354) |
| SpamTitan | SpamTitan | All |  1.1.1n | Not vuln | https://helpdesk.spamtitan.com/support/solutions/articles/4000188396-spamtitan-not-susceptible-to-openssl-3-0-7| |
| SPI | adelie | 1.0 | 1.1.1g | Not vuln | https://distfiles.adelielinux.org/adelie/1.0/system/x86_64/openssl-1.1.1g-r0.apk| |
| Splunk | All | All | Unknown | Not vuln | https://www.splunk.com/en_us/product-security/announcements/svd-2022-1114.html | |
| SUSE | Enterprise Linux Server | <= 15 SP4 | <= 1.1.1l | Not vuln | https://www.suse.com/support/kb/doc/?id=000019582 | |
| SUSE | Enterprise Linux Server | 15 SP4 | 3.0.1 | Vulnerable | https://www.suse.com/support/kb/doc/?id=000019582 | Optional package |
| Synacor | Zimbra Email & Collaboration | <= 8.8.15 | 1.1.1q | Not vuln | https://wiki.zimbra.com/wiki/Zimbra_Releases/8.8.15/P34 | |
| Synacor | Zimbra Email & Collaboration | 9.0.0 | 1.1.1q | Not vuln | https://wiki.zimbra.com/wiki/Zimbra_Releases/9.0.0/P27 | |
| Synology | All | Unkown | Unkown | Not vuln | https://www.synology.com/en-global/security/advisory/Synology_SA_22_21 | |
| Tanium | All | All | < 3.x | Not vuln | https://community.tanium.com/s/article/How-Tanium-Can-Help-Identify-OpenSSL-3-0-X#tanium | |
| Tenable | Nessus | < 10.3.2 | Unknown | Fix | https://www.tenable.com/security/tns-2022-23 | |
| Tenable | Nessus | < 10.4.1 | Unknown | Fix | https://www.tenable.com/security/tns-2022-24 | |
| Tenable | Nessus Agent | < 10.2.1 | Unknown | Fix | https://www.tenable.com/security/tns-2022-22 | |
| Tenable | Other | Unknown | Unknown | Investigation | https://www.tenable.com/blog/cve-2022-3786-and-cve-2022-3602-openssl-patches-two-high-severity-vulnerabilities | | 
| Trend Micro | Unknown | Unknown| Unknown | Investigation | https://success.trendmicro.com/dcx/s/solution/000291744?language=en_US | |
| Trellix | Trellix EPO | ? | ? | Investigation | https://kcm.trellix.com/corporate/index?page=content&id=KB96105 | |
| Tunnelblick | Tunnelblick | <= 3.8.2beta07 | 1.1.1m | Not vuln | https://tunnelblick.net/cRlsNotes.html | |
| Ubiquiti | AmpliFi Alien | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | AmpliFi HD | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | AmpliFi Instant | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | Cloud Key | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | Cloud Key Gen2 | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | Cloud Key Gen2 Plus | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | EdgeRouters | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | EdgeSwitches | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UFIBER | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UISP airCube | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UISP airFiber | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UISP airMAX | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UISP LTU | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UISP Router | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UISP Switches | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UISP Wave | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UniFi Access Points | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UniFi Gateways | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UniFi Protect Cameras | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UniFi Switches | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UNVR | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Ubiquiti | UNVR PRO | All | Unknown | Not vuln | https://community.ui.com/releases/Statement-Regarding-OpenSSL-3-x-Vulnerability-001/86d4308a-a65d-4a26-90c8-0ac068dd757e | |
| Univention | Corporate Server | <= 5.0 | 1.1.1n | Not vuln | https://forge.univention.org/bugzilla/show_bug.cgi?id=54901 | Based on Debian 10 |
| Veritas | All | All | Unknown | Investigation | https://www.veritas.com/content/support/en_US/security/VTS22-016 | |
| WithSecure (formerly F-Secure) | Atlant | All | Unknown | Not vuln | https://help.f-secure.com/product.html#business/releasenotes-business/latest/en/fsa-latest-en | Response from WithSecure Customer Care as part of (private) business ticket |
| WithSecure (formerly F-Secure) | Linux Security 64 | All | 1.1.1 | Not vuln | https://help.f-secure.com/product.html?business/releasenotes-business/latest/en/fsls64-latest-en | Response from WithSecure Customer Care as part of (private) business ticket |
| VMware| All | All | Unknown | Not vuln | https://blogs.vmware.com/security/2022/11/vmware-response-to-cve-2022-3602-and-cve-2022-3786-vulnerabilities-in-openssl-3-0-x.html | |
| VMware| Harbor | <=2.6.1 | 3.0.0 | Vulnerable | https://github.com/goharbor/harbor/issues/17724 | Only the official docker images are vulnerable |
| VMware| VMware Tools | 12.0.0<br/>  12.1.0 | 3.0.0<br/>  3.0.3 | Vulnerable | https://docs.vmware.com/en/VMware-Tools/12.0/rn/VMware-Tools-1200-Release-Notes.html| |
| Void Linux| Void Linux | current | 1.1.1q | Not vuln | https://alpha.de.repo.voidlinux.org/current/openssl-1.1.1q_1.x86_64.xbps| |
| WatchGuard | Cloud Wi-Fi APs | Any | Not Stated | Not vuln | https://www.watchguard.com/wgrd-psirt/advisory/wgsa-2022-00021 | |
| WatchGuard | Dimension | Any | Not Stated | Not vuln | https://www.watchguard.com/wgrd-psirt/advisory/wgsa-2022-00021 | |
| WatchGuard | FireBox | Any | Not Stated | Not vuln | https://www.watchguard.com/wgrd-psirt/advisory/wgsa-2022-00021 | |
| WatchGuard | System Manager (WSM) | Any | Not Stated | Not vuln | https://www.watchguard.com/wgrd-psirt/advisory/wgsa-2022-00021 | |
| Wire | Wire Server | All | 1.1.1 | Not vuln | https://github.com/wireapp/wire-server/blob/develop/docs/src/security-responses/2022-11-01_openssl.md | |
| Wire | Wire Webapp | All | 1.1.1 | Not vuln | https://github.com/wireapp/wire-server/blob/develop/docs/src/security-responses/2022-11-01_openssl.md | |
| Wire | Wire Desktop | All | 1.1.1 | Not vuln | https://github.com/wireapp/wire-server/blob/develop/docs/src/security-responses/2022-11-01_openssl.md | |
