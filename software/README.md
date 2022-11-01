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
| AlmaLinux OS Foundation | AlmaLinux | 9 | 3.0.1 | Vulnerable | https://repo.almalinux.org/almalinux/9/BaseOS/x86_64/os/Packages/openssl-3.0.1-41.el9_0.x86_64.rpm| |
| AlmaLinux OS Foundation | AlmaLinux | 8 | 1.1.1k | Not vuln | https://repo.almalinux.org/almalinux/8/BaseOS/x86_64/os/Packages/openssl-1.1.1k-7.el8_6.x86_64.rpm| |
| Alpine | Alpine Linux | Edge | 3.0.5 | Vulnerable | https://pkgs.alpinelinux.org/packages?name=openssl&branch=edge&repo=&arch=&maintainer= | |
| Alpine | Alpine Linux | 3.15, 3.16 | 3.0.5 | Vulnerable | https://pkgs.alpinelinux.org/packages?name=openssl3&branch=v3.16&repo=&arch=&maintainer= | optional, non-default package |
| Alpine | Alpine Linux | <= 3.14 | 1.1.1 | Not vuln | https://pkgs.alpinelinux.org/packages?name=openssl&branch=v3.16&repo=&arch=&maintainer= | |
| ALT Linux Ltd | ALT Linux | p10 | 1.1.1q | Not vuln | https://distrib-coffee.ipsl.jussieu.fr/pub/linux/altlinux/p10/branch/x86_64/RPMS.classic/openssl-1.1.1q-alt1.x86_64.rpm| |
| ALT Linux Ltd | ALT Linux | p9 | 1.1.1n | Not vuln | https://distrib-coffee.ipsl.jussieu.fr/pub/linux/altlinux/p9/branch/x86_64/RPMS.classic/openssl-1.1.1n-alt2.x86_64.rpm| |
| Arch | Arch Linux | Core | 1.1.1 | Not vuln | https://archlinux.org/packages/?name=openssl | |
| Amazon | Amazon Linux | 2 | 1.0.2k | Not vuln | https://docs.aws.amazon.com/linux/al2022/ug/compare-al2-to-AL2022.html#openssl3 | |
| Amazon | Amazon Linux | 2022 | 3.0.5-1 | Vulnerable | https://docs.aws.amazon.com/linux/al2022/ug/compare-al2-to-AL2022.html#openssl3 | |
| ASUSWRT-MERLIN | ASUSWRT-MERLIN | 386/NG | 1.1.1q | Not vuln | https://www.asuswrt-merlin.net/changelog | |
| Buildroot | Buildroot | 2022.08.1 | 1.1.1q | Not vuln | https://github.com/buildroot/buildroot/blob/master/package/libopenssl/libopenssl.mk#L7 | OpenSSL 1.1.1q is the default version. |
| Bitdefender | Bitdefender Endpoint Security | All | Unknown | Investigation | https://www.bitdefender.com/business/support/en/77209-80152-open-source-software-used-by-bitdefender-enterprise-products.html | |
| Bitdefender | Bitdefender Security for Mobile | All | Unknown | Investigation | https://www.bitdefender.com/business/support/en/77209-80152-open-source-software-used-by-bitdefender-enterprise-products.html | |
| Bitdefender | Bitdefender GravityZone Management Appliance | All | Unknown | Investigation | https://www.bitdefender.com/business/support/en/77209-80152-open-source-software-used-by-bitdefender-enterprise-products.html | |
| Broadcom | Symantec Endpoint Protection Manager | 14.3 RU5 | 3.0.2 | Vulnerable | https://community.broadcom.com/symantecenterprise/discussion/which-is-the-openssl-version-in-sepm-143-ru5 | |
| Broadcom | Symantec Endpoint Protection Manager | 14.3 RU6 | 3.0.7 | Not Vulnerable | https://community.broadcom.com/symantecenterprise/discussion/which-is-the-openssl-version-in-sepm-143-ru5 | Fixed version not released yet. |
| Canonical | Ubuntu | bionic (18.04 LTS) | 1.1.1 | Not vuln | https://packages.ubuntu.com/search?suite=bionic&keywords=openssl | |
| Canonical | Ubuntu | impish (21.10) | 1.1.1 | Not vuln | https://packages.ubuntu.com/search?suite=impish&keywords=openssl | |
| Canonical | Ubuntu | focal (20.04 LTS) | 1.1.1 | Not vuln | https://packages.ubuntu.com/search?suite=focal&keywords=openssl | |
| Canonical | Ubuntu | jammy (22.04 LTS) | 3.0.2 | Vulnerable | https://packages.ubuntu.com/search?suite=jammy&keywords=openssl | |
| Canonical | Ubuntu | kinetic (22.10) | 3.0.5 | Vulnerable | https://packages.ubuntu.com/search?suite=kinetic&keywords=openssl | |
| Canonical | Ubuntu | Squid | 3.0.5 5 | Vulnerable | https://hub.docker.com/r/ubuntu/squid/tags | |
| CentOS | CentOS | 7.9 | 1.0.2 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| CentOS | CentOS | 8 | 1.1.1 | Not vuln| https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| CentOS | CentOS | >= 9 | 3.x | Vulnerable | https://www.redhat.com/en/blog/experience-bringing-openssl-30-rhel-and-fedora | |
| Cisco | All | Unknown | Unknown | Investigation | https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-openssl-W9sdCc2a | |
| Code42 | Incydr | ALL | 1.x | Not vuln | [Code42 Response to Industry Security Incidents](https://support.code42.com/Terms_and_conditions/Code42_customer_support_resources/Code42_response_to_industry_security_incidents) | |
| Debian | Debian | 9 "Stretch"	| 1.1.0 | Not vuln | https://packages.debian.org/stretch/openssl	| |
| Debian | Debian | 10 "Buster"	| 1.1.1	| Not vuln | https://packages.debian.org/buster/openssl | |
| Debian | Debian | 11 "Bullseye"	| 1.1.1	| Not vuln | https://packages.debian.org/bullseye/openssl | |
| Debian | Debian | 12 "Bookworm" | 3.x | Vulnerable | https://packages.debian.org/bookworm/openssl | _testing_ (not yet released) |
| Deciso B.V. | OPNsense | 22 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ |
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
| Esri | ArcGIS | All | Unknown | Investigation | https://www.esri.com/arcgis-blog/products/trust-arcgis/administration/openssl-v3-vulnerability/ | |
| F5 Networks | BIG-IP | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | BIG-IP SPK | 1.x | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | BIG-IQ Centralized Management | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | F5OS-A | 1.x | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | F5OS-C | 1.x | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX API Connectivity Manager | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX App Protect DoS | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX App Protect WAF | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Controller Application Delivery | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Controller API Management | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Ingress Controller | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Instance Manager | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Plus | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Service Mesh | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | NGINX Unit | All | Unknown | Investigation | https://support.f5.com/csp/article/K44030142 | |
| F5 Networks | Traffix SDC | All | Unknown | Not vuln | https://support.f5.com/csp/article/K44030142 | |
| Fedora | Linux | 35 | 1.1.1 | Not vuln | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | | 
| Fedora | Linux | 36 | 3.0.2 | Vulnerable | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| Fedora | Linux | 37 | 3.0.5 | Vulnerable | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| Fedora | Linux | Rawhide | 3.0.5 | Vulnerable | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| FileCap | FileCap Server | All | < 3.x | Not vuln | https://github.com/NCSC-NL/OpenSSL-2022/blob/main/software/vendor-statements/FileCap.png | | 
| Fortinet | FortiADC | All | n.a. | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiADCManager | All | n.a. | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAIOps | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAnalyzer | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAnalyzer-BigData | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAnalyzer Cloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAP | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAP-C | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiAPCloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
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
| Fortinet | FortiCloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiConnect | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiConverter | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiDDoS | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiDDoS-F | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiDeceptor | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
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
| Fortinet | FortiSASE | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiSIEM | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiSOAR | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiSwitch | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiSwitchManager | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiSwitch Cloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiTester | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiTokenAndroid | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiToken Cloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiTokenIOS | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiVoiceEnterprise | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiVoiceUC | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiVoiceUCDesktop | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWAN | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWeb | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWebCloud | Unknown | Unknown | Investigation | https://www.fortiguard.com/psirt/FG-IR-22-419 | | 
| Fortinet | FortiWebManager | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWLC | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| Fortinet | FortiWLM | All | Unknown | Not vuln | https://www.fortiguard.com/psirt/FG-IR-22-419 | |
| HashiCorp| Unknown | Unknown| Unknown | Investigation | https://discuss.hashicorp.com/t/hcsec-2022-27-hashicorp-response-to-openssl-security-announcement-regarding-november-1-release/46192 | |
| IBM | All | Unknown | Unknown | Investigation | https://www.ibm.com/support/pages/node/6833428 | |
| Intel | System Usage Report (Codename: Queencreek) | 2.4.0.8919 | 3.0.2 | Vulnerable | [Local Proof](vendor-statements/openssl_queencreek.png) | |
| Linux Mint | Linux Mint | 21 Vanessa | 3.0.2 | Vulnerable | http://packages.linuxmint.com/search.php?release=vanessa&section=any&keyword=openssl | 
| FreeBSD | FreeBSD | 13 | 1.1.1q | Not vuln | https://pkg.freebsd.org/FreeBSD:13:amd64/latest/All/openssl-1.1.1q,1.pkg| |
| FreeBSD | FreeBSD | 12 | 1.1.1q | Not vuln | https://pkg.freebsd.org/FreeBSD:12:amd64/quarterly/All/openssl-1.1.1q,1.pkg| |
| KaOS | KaOS | rolling | 1.1.1.18 | Not vuln | http://mirror6.layerjet.com/kaos/core/openssl-1.1.1.18-1-x86_64.pkg.tar.zst| |
| Kemp | LoadMaster | 7.2.58 | 1.1.1n | Not vuln | https://support.kemptechnologies.com/hc/en-us/articles/10228770842637-Current-OpenSSL-Version-for-LoadMaster | |
| Mageia | Mageia | 8 | 1.1.1q | Not vuln | https://distrib-coffee.ipsl.jussieu.fr/pub/linux/Mageia/distrib/8/x86_64/media/core/updates/openssl-1.1.1q-1.mga8.x86_64.rpm| |
| Mageia | Mageia | cauldron | 3.0.5 | Vulnerable | https://distrib-coffee.ipsl.jussieu.fr/pub/linux/Mageia/distrib/cauldron/x86_64/media/core/release/openssl-3.0.5-1.mga9.x86_64.rpm| |
| Nasuni | Edge Appliance | All | Unknown | Not vuln | https://trustcenter.nasuni.com/?tcuUid=495df3df-eb99-44cf-9d8b-6ac7a3944cd7 | |
| Nasuni | Management Console | All | Unknown | Not vuln | https://trustcenter.nasuni.com/?tcuUid=495df3df-eb99-44cf-9d8b-6ac7a3944cd7 | |
| NixOS | NixOS | 22.05 | 1.1.1q | Not vuln | https://search.nixos.org/packages?channel=22.05&query=openssl&show=openssl | There are exceptions, e.g., nginx is built against OpenSSL 3! |
| NixOS | NixOS | unstable | 3.0.5 | Vulnerable | https://search.nixos.org/packages?channel=unstable&query=openssl&show=openssl | |
| NetBSD | NetBSD | 9 | 1.1.1k | Not vuln | https://cdn.netbsd.org/pub/NetBSD/NetBSD-9.3/CHANGES-9.2 |
| NetBSD | NetBSD | 8 | 1.0.2k | Not vuln | https://netbsd.org/releases/formal-8/NetBSD-8.0.html |
| NetBSD | pkgsrc | - | 1.1.1q | Not vuln | https://cdn.netbsd.org/pub/pkgsrc/current/pkgsrc/security/openssl/index.html|
| Node.js | JavaScript Runtime Environment | 17 | 3.x | Investigation | https://github.com/nodejs/node/blob/main/doc/changelogs/CHANGELOG_V17.md#17.0.0 | Missing from Node.js security update blog post because v17 is EOL |
| Node.js | JavaScript Runtime Environment | 18 | 3.x | Investigation | https://nodejs.org/zh-cn/blog/vulnerability/openssl-november-2022/ ||
| Node.js | JavaScript Runtime Environment | 19 | 3.x | Investigation | https://nodejs.org/zh-cn/blog/vulnerability/openssl-november-2022/ ||
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
| Palo Alto Networks | Prisma Cloud | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Prisma Cloud Compute | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Prisma SD-WAN ION | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | Prisma SDWAN (Cloudgenix) | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | SaaS Security | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | User-ID Agent | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | WildFire Appliance (WF-500) | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| Palo Alto Networks | WildFire Cloud | * | < 3.X | Not vuln | https://security.paloaltonetworks.com/PAN-SA-2022-0006 | |
| PCLinuxOS | PCLinuxOS | rolling | 1.1.1q | Not vuln | https://ftp.nluug.nl/pub/os/Linux/distr/pclinuxos/pclinuxos/apt/pclinuxos/64bit/RPMS.x86_64/openssl-1.1.1q-1pclos2022.x86_64.rpm| |
| Proxmox Server Solutions GmbH| Proxmox | 6 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| Proxmox Server Solutions GmbH| Proxmox | 7 | 1.1.1 | Not vuln | https://www.proxmox.com/en/news/press-releases/proxmox-virtual-environment-7-0 (EN) |Based on Debian 11, no custom OpenSSL version used. |
| PHP | PHP | < 8.1 | < 3.0 | Not vuln | https://www.php.net/manual/en/openssl.requirements.php | | 
| PHP	| PHP	| >= 8.1 | Unknown | Investigation | https://www.php.net/manual/en/openssl.requirements.php | |
| Red Hat | Enterprise Linux | <= 8 | 1.x	| Not vuln | https://access.redhat.com/security/vulnerabilities/RHSB-2022-004	| | 
| Red Hat | Enterprise Linux | >= 9.0 | 3.x	| Vulnerable | https://access.redhat.com/security/vulnerabilities/RHSB-2022-004	| | 
| Red Hat | OpenShift Container Platform | => 4.0 | 1.1.1 | Not vuln | https://access.redhat.com/security/vulnerabilities/RHSB-2022-004 | |
| Red Hat | Universal Base Images | <= 8 | 1.x | Not vuln | https://access.redhat.com/security/vulnerabilities/RHSB-2022-004 | |
| Red Hat | Universal Base Images | >= 9.0 | 3.x | Vulnerable | https://access.redhat.com/security/vulnerabilities/RHSB-2022-004 | |
| Rocky Enterprise Software Foundation | Rocky Linux | 8.0 | 1.1.1k | Not vuln | https://dl.rockylinux.org/pub/rocky/8/BaseOS/x86_64/os/Packages/o/openssl-1.1.1k-7.el8_6.x86_64.rpm| |
| Rocky Enterprise Software Foundation | Rocky Linux | 9.0 (Blue Onyx) | 3.0.1 | Vulnerable | https://dl.rockylinux.org/pub/rocky/9/BaseOS/x86_64/os/Packages/o/openssl-3.0.1-41.el9_0.x86_64.rpm| |
| PulseSecure (Ivanti) | All | Unknown | Unknown | Not vuln | https://kb.pulsesecure.net/articles/Pulse_Secure_Article/OpenSSL-3-0-x-Vulnerability-Ivanti-Product-Impact1/?kA13Z000000FseL | |
| Slackware | Slackware Linux | 14.1 | 1.0.1e | Not vuln | https://slackware.uk/slackware/slackware64-14.1/slackware64/n/openssl-1.0.1e-x86_64-1.txz| |
| Slackware | Slackware Linux | 14.2 | 1.0.2h | Not vuln | https://slackware.uk/slackware/slackware64-14.2/slackware64/n/openssl-1.0.2h-x86_64-1.txz| |
| Slackware | Slackware Linux | 15.0 | 1.1.1q | Not vuln | https://slackware.uk/slackware/slackware64-15.0/patches/packages/openssl-1.1.1q-x86_64-1_slack15.0.txz| |
| Slackware | Slackware Linux | current | 1.1.1q | Not vuln | https://slackware.uk/slackware/slackware64-current/slackware64/n/openssl-1.1.1q-x86_64-1.txz| |
| Softether | Softether VPN | 4.39 Build 9772 Beta | 3.0.2 | Vulnerable | https://www.softether.org/5-download/history | |
| SpamTitan | SpamTitan | All |  1.1.1n | Not vuln | https://helpdesk.spamtitan.com/support/solutions/articles/4000188396-spamtitan-not-susceptible-to-openssl-3-0-7| |
| SPI | adelie | 1.0 | 1.1.1g | Not vuln | https://distfiles.adelielinux.org/adelie/1.0/system/x86_64/openssl-1.1.1g-r0.apk| |
| Splunk | Splunk Enterprise | <= 9.0.1 | <= 1.0.2zd | Not vuln | https://docs.splunk.com/images/9/91/Splunk_Enterprise_3rd_Party_Software_900.pdf | |
| Splunk | Universal Forwarder | <= 9.0.x | <= 1.0.2zd | Not vuln | https://docs.splunk.com/images/9/91/Splunk_Enterprise_3rd_Party_Software_900.pdf | |
| Solus | Solus | rolling | 1.1.1q | Not vuln | https://mirrors.rit.edu/solus/packages/shannon/o/openssl-11/openssl-11-32bit-devel-1.1.1q-15-1-x86_64.eopkg| |
| Tenable | Nessus | 10.3.0 | 3.0.5 | Vulnerable | https://docs.tenable.com/releasenotes/Content/nessus/nessus1030.htm| |
| Tenable | Nessus Agent | 10.2 | 3.0.5 | Vulnerable | https://docs.tenable.com/releasenotes/Content/nessusagent/agent1020.htm | |
| Tenable | Nessus Network Monitor | 6.1.0 | 3.0.5 | Vulnerable | https://docs.tenable.com/releasenotes/Content/nnm/nnm610.htm?Highlight=openssl| |
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
| VMware| All | All | Unknown | Not vuln | https://blogs.vmware.com/security/2022/11/vmware-response-to-cve-2022-3602-and-cve-2022-3786-vulnerabilities-in-openssl-3-0-x.html | |
| VMware| VMware Tools | 12.0.0<br/>  12.1.0 | 3.0.0<br/>  3.0.3 | Vulnerable | https://docs.vmware.com/en/VMware-Tools/12.0/rn/VMware-Tools-1200-Release-Notes.html| |
| VMware| Harbor | <=2.6.1 | 3.0.0 | Vulnerable | https://github.com/goharbor/harbor/issues/17724 | Only the official docker images are vulnerable |
| Void Linux| Void Linux | current | 1.1.1q | Not vuln | https://alpha.de.repo.voidlinux.org/current/openssl-1.1.1q_1.x86_64.xbps| |
