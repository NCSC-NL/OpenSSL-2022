# 2022 OpenSSL vulnerability - CVE-2022-3602/CVE-2022-3786

<img src="spooky.png" alt="Spooky SSL" width="300">

This repo contains operational information regarding CVE-2022-3602 and CVE-2022-3786, two vulnerabilities in OpenSSL 3.0.0-3.0.6. For more information see:

- [OpenSSL Security Advisory](https://www.openssl.org/news/secadv/20221101.txt)
- [OpenSSL Blogpost FAQ](https://www.openssl.org/blog/blog/2022/11/01/email-address-overflows/)
- [CERT-Bund advisory (DE)](https://www.bsi.bund.de/SharedDocs/Cybersicherheitswarnungen/DE/2022/2022-267005-1032.html)
- [CISA advisory](https://www.cisa.gov/uscert/ncas/current-activity/2022/11/01/openssl-releases-security-update)
- [NCSC-NL advisory (NL)](https://www.ncsc.nl/actueel/advisory?id=NCSC-2022-0685)
- [OpenSSL pre-notification](https://mta.openssl.org/pipermail/openssl-announce/2022-October/000238.html)
- [OpenSSL release notification](https://mta.openssl.org/pipermail/openssl-announce/2022-November/000241.html)
- [SANS Internet Storm Center Blogpost](https://isc.sans.edu/forums/diary/Critical+OpenSSL+30+Update+Released+Patches+CVE20223786+CVE20223602/29208)


## What is OpenSSL and what is it used for?
OpenSSL is a library used for cryptographic purposes, especially in the field of network connections. For example, web servers often use OpenSSL to establish encrypted HTTPS connections. Mail servers and VPN protocols such as OpenVPN also use OpenSSL to establish encrypted communication channels. The library can be found in a broad array of products, including network devices, embedded systems and container images.

## What products are vulnerable?
The vulnerability is present in products using OpenSSL 3.0.0-3.0.6. Products that use OpenSSL 1.0.2 or 1.1.1 are not affected.

Currently no complete overview of vulnerable products is available. Please see [software/README.md](software/README.md) for a list of products that are known to be vulnerable. The list is a work in progress. For more information about specific products, please refer to your supplier.

## The product I use is vulnerable to this issue. What should I do?
For up-to-date information about patches and mitigations, please refer to your product vendor.

## IoCs and Detection
There are currently no known IoCs that indicate exploitation of this vulnerability. IoCs will be shared - when possible - through this repository.
For network detection rules please see [iocs_detection/README.md](iocs_detection/README.md).

## Hall of fame

We would like to thank every single one that provided source information or whom contributed to our GitHub page.

Below we present a very incomplete list of contributants or sources we consider the repository's hall of fame:

* [SANS](https://isc.sans.edu/diary/Upcoming+Critical+OpenSSL+Vulnerability+What+will+be+Affected/29192/)
* [SURFcert](https://wiki.surfnet.nl/pages/viewpage.action?pageId=11063492)
* [@jspaans](https://github.com/jspaans91)
* [@robert-scheck](https://github.com/robert-scheck)
* [@RobinFlikkema](https://github.com/RobinFlikkema)
* [@MaxGroot](https://github.com/maxgroot)
