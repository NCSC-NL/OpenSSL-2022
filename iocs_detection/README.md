# IoCs & Detection
This page contains an overview of any detection and mitigation software regarding the SpookySSL vulnerability. On this page NCSC-NL will maintain a list of all known rules to detect SpookySSL presence or (suspected) exploitation. Furthermore, any references will contain specific information regarding detection and mitigation.

**NCSC-NL has not verified the rules and software listed below and therefore cannot guarantee the validity of said rules. However, NCSC-NL strives to provide rules and detection and mitigation software from reliable sources.**


## Suricata Rules

Rule from [Fox-IT Security Research Team](https://github.com/fox-it/spookyssl-pcaps):

```suricata
alert tls any any -> any any (msg:"FOX-SRT - Exploit - Possible SpookySSL Certificate Observed (CVE-2022-3602)"; \
    flow: established; \
    content:"|2b 06 01 05 05 07 08 09|"; fast_pattern; \
    content:"|06 03 55 1d 1e|"; content:"xn--"; \
    content:!"|81|"; distance:-6; within:1; byte_test:2,>=,500,-6,relative; \
    classtype:attempted-user; threshold:type limit, track by_src, count 1, seconds 3600; \
    reference:url, www.openssl.org/news/secadv/20221101.txt; \
    reference:url, https://github.com/fox-it/spookyssl-pcaps; \
    metadata:ids suricata; \
    metadata:created_at 2022-11-02; sid:21004268; rev:3;)
```


## Example PCAPs

<table>
  <thead>
    <th>PCAP</th>
    <th>Description</th>
  </thead>
  <tbody>
    <tr>
        <td><a href=https://github.com/fox-it/spookyssl-pcaps/raw/main/pcaps/spookyssl-windowscrash.pcap>spookyssl-windowscrash.pcap</a></td>
        <td>Created using the Windows Crash PoC from DataDog</td>
    </tr>
    <tr>
        <td><a href=https://github.com/fox-it/spookyssl-pcaps/raw/main/pcaps/spookyssl-malicious_client.pcap>spookyssl-malicious_client.pcap</a></td>
        <td>Created using the malicious_client PoC from DataDog</td>
    </tr>
    <tr>
        <td><a href=https://github.com/fox-it/spookyssl-pcaps/raw/main/pcaps/spookyssl-malicious_server.pcap>spookyssl-malicious_server.pcap</a></td>
        <td>Created using the malicious_server PoC from DataDog</td>
    </tr>
    <tr>
        <td><a href=https://github.com/fox-it/spookyssl-pcaps/raw/main/pcaps/not-spookyssl-certificate.pcap>not-spookyssl-certificate.pcap</a></td>
        <td>Legitimate punycode certificate (not malicous)</td>
    </tr>
  </tbody>
</table>

For further context, see https://github.com/fox-it/spookyssl-pcaps
