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
| Alpine | Alpine Linux | <= 3.16 | 1.1.1 | Not vuln | https://pkgs.alpinelinux.org/packages?name=openssl&branch=v3.16&repo=&arch=&maintainer= | |
| Alpine | Alpine Linux | Edge | 3.0.5 | Vulnerable | https://pkgs.alpinelinux.org/packages?name=openssl&branch=edge&repo=&arch=&maintainer= | |
| Arch | Arch Linux | Core | 1.1.1 | Not vuln | https://archlinux.org/packages/?name=openssl | |
| Canonical | Ubuntu | bionic (18.04 LTS) | 1.1.1 | Not vuln | https://packages.ubuntu.com/search?keywords=openssl | |
| Canonical | Ubuntu | impish (21.10) | 1.1.1 | Not vuln | https://packages.ubuntu.com/search?keywords=openssl | |
| Canonical | Ubuntu | focal (20.04 LTS) | 1.1.1 | Not vuln | https://packages.ubuntu.com/search?keywords=openssl | |
| Canonical | Ubuntu | jammy (22.04 LTS) | 3.0.2 | Vulnerable | https://packages.ubuntu.com/search?keywords=openssl | |
| CentOS | CentOS | 7.9 | 1.0.2 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| CentOS | CentOS | 8 | 1.1.1 | Not vuln| https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| CentOS | CentOS | >= 9 | 3.x | Vulnerable | https://www.redhat.com/en/blog/experience-bringing-openssl-30-rhel-and-fedora | |
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
| Fedora | Linux | 35 | 1.1.1 | Not vuln | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | | 
| Fedora | Linux | 36 | 3.0.2 | Vulnerable | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| Fedora | Linux | 37 | 3.0.5 | Vulnerable | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
| Fedora | Linux | Rawhide | 3.0.5 | Vulnerable | https://packages.fedoraproject.org/pkgs/openssl/openssl/ | |
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
| Linux Mint | Linux Mint | 21 Vanessa | 3.0.2 | Vulnerable | http://packages.linuxmint.com/search.php?release=vanessa&section=any&keyword=openssl | 
| FreeBSD | FreeBSD | <=13 | <3 | Not vuln | https://pkg.opnsense.org/FreeBSD:12:amd64/21.7/latest/All/ | Base for OPNSense and pfSense CE |
| Node.js | JavaScript Runtime Environment | 18 | 3.x | Investigation | Node.js 18 updates OpenSSL support, enables fetch API | InfoWorld	|
| Offensive Security | Kali | 2022.3 | 3.0.5 | Vulnerable | https://pkg.kali.org/pkg/openssl | 
| OpenMandriva | OpenMandriva | 4.3 | 3.0.3 | Vulnerable | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenMandriva | OpenMandriva | Cooker | 3.0.6 | Vulnerable | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenMandriva | OpenMandriva | Cooker | 3.0.6 | Vulnerable | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.3 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.4 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.2 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.3 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenSUSE | Leap | 15.4 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| OpenVPN | OpenVPN | <= 2.5.7 | < 3.0 | Investigation | https://en.wikipedia.org/wiki/OpenVPN | https://openvpn.net/community-downloads/ Support for OpenSSL 3 in later version: OpenVPN 2.6. | |
| Proxmox Server Solutions GmbH| Proxmox | 6 | 1.1.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| PHP | PHP | < 8.1 | < 3.0 | Not vuln | https://www.php.net/manual/en/openssl.requirements.php | | 
| PHP	| PHP	| >= 8.1 | Unknown | Investigation | https://www.php.net/manual/en/openssl.requirements.php | |
| Red Hat | Enterprise Linux | >= 9.0 | 3.x	| Vulnerable | https://www.redhat.com/en/blog/experience-bringing-openssl-30-rhel-and-fedora	| | 
| Rocky Enterprise Software Foundation | Rock Linux | 9.0 (Blue Onyx) | 3.0.1 | Vulnerable | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
| Slackware | Slackware Linux | 14 | 1.0.1 | Not vuln | https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/ | |
