# OpenSSL-vulnerability-2022
Operational information about the recently announced vulnerability in OpenSSL 3

## What is OpenSSL and what is it used for?
OpenSSL is a library used for cryptographic applications, especially in the field of network connections. For example, web servers often use OpenSSL to establish encrypted HTTPS connections. Mail servers and VPN protocols such as OpenVPN also use OpenSSL to establish encrypted communication.

## Is the vulnerability being exploited?
At this time, there is no indication that the vulnerability is being exploited. The NCSC expects that this vulnerability might be exploited as it's widely used. Therefore, we would like to address that patching the vulnerability is important. Our security advice will be published on this GitHub page.

## What products are vulnerable?
The vulnerability is present in products using OpenSSL 3.0.0-3.0.6. Products that have OpenSSL < 3.0.0 user are not vulnerable. However, using the vulnerable OpenSSL version does not mean that the vulnerability can actually be exploited (remotely). Refer to the security advisory for updates.

There is currently no complete overview of vulnerable products available, please see [software/README.md](software/README.md) for more information. For information about specific products, refer to your supplier. In case of widely used products, we will also contact the supplier.

## Can this vulnerability be scanned?
As far as is known, it is not possible at network level to scan for the presence of a vulnerable OpenSSL version. It may be possible to determine whether a vulnerable version of OpenSSL is installed through software at the end-point level.

## The product I use is vulnerable to this issue. What should I do?
Please find the latest information in the security advisory for up-to-date steps. When the situation changes we will update the advisory. For product-specific advisories, please refer to your supplier.

## Is LibreSSL/BoringSSL/Tink vulnerable?
LibreSSL is based on OpenSSL 1.1.1g and is not vulnerable.
BoringSSL is based on OpenSSL 1.x.y and probably not vulnerable.
Tink is based on BoringSSL and probably not vulnerable.

## Are there IoCs?
There are currently no known IoCs that indicate exploitation of this vulnerability. As far as possible, IoCs will be shared through the usual channels, such as MISP and this repository. Please see [iocs/README.md](iocs/README.md) for more information.
