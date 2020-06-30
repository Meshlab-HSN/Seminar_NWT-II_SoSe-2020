Nickname | FQDN of your OpenWrt VM <br> (your choosen dyndns domain) | Am I behind a CG-NAT ? <br> (check from your OpenWrt terminal <sup id="a1">[1](#f1)</sup>)
------------ | :-------------: | :-------------:
MeshLab Server  | evernet-kihei.dedyn.io  | `no`
Lars Gebken     | kenny0.ddns.de          | `yes/no`
Niklas Mäder    | mniklas19.ddnss.de      | `yes/no`
Niklas Häger    | niklash.ddnss.de        | `yes/no`
Fabian Heydecke | nwtp.spdns.org          | `yes/no`


<br>
<br>

<b id="f1">1</b> To check weather your ISP puts your behind a [CG-NAT](https://en.wikipedia.org/wiki/Carrier-grade_NAT) with changing public IP's, run: <br>`curl ipecho.net/plain -w "\n"; curl ifconfig.me/ip -w "\n"; curl ident.me -w "\n"` <br> from your OpenWrt command line. If your the three IPs differ, you got probably CG-NATed [↩](#a1)

