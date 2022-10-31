# 2022 OpenSSL vulnerability
This repo contains operational information regarding the recently announced vulnerability in OpenSSL 3. For more information see:

- [OpenSSL pre-notification](https://mta.openssl.org/pipermail/openssl-announce/2022-October/000238.html)

## What is OpenSSL and what is it used for?
OpenSSL is a library used for cryptographic purposes, especially in the field of network connections. For example, web servers often use OpenSSL to establish encrypted HTTPS connections. Mail servers and VPN protocols such as OpenVPN also use OpenSSL to establish encrypted communication channels. The library can be found in a broad array of products, including network devices, embedded systems and container images.

## What products are vulnerable?
The vulnerability is present in products using OpenSSL 3.0.0-3.0.6. Products that use OpenSSL 1.0.2 or 1.1.1 are not affected.

Currently no complete overview of vulnerable products is available. Please see [software/README.md](software/README.md) for a list of products that are known to be vulnerable. The list is a work in progress. For more information about specific products, please refer to your supplier.

## The product I use is vulnerable to this issue. What should I do?
For up-to-date information about patches and mitigations, please refer to your product vendor.

## Are there IoCs?
There are currently no known IoCs that indicate exploitation of this vulnerability. IoCs will be shared - when possible - through this repository. Please see [iocs/README.md](iocs/README.md) for more information.
