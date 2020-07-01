Nickname | [FQDN][1] of your OpenWrt VM <br> *(your dyndns domain)* | Am I behind a [CG-NAT][2]? <br> *(Test your IP <sup id="a1">[1](#f1)</sup>)* | Public-Key of your [WireGuard][3] peer <br> *(DO NOT PUT YOUR PRIVATE KEY HERE!)* | Chosen ip address in range 10.10.222.0/24
--------------- | :---------------------: | :-------: | :---------------------------------------------: | :--------------:
MeshLab Server  | evernet-kihei.dedyn.io  | `no`      | `iTa3sr8lIu7UXQIB/l2szLQtC7z0dA8eQUMRPIvtqmw=`  | 10.10.222.1/24
Lars Gebken     | kenny0.ddns.de          | `yes/no`  |                                                 |
Niklas Mäder    | mniklas19.ddnss.de      | `yes/no`  |                                                 |
Niklas Häger    | niklash.ddnss.de        | `yes/no`  |                                                 |
Fabian Heydecke | nwtp.spdns.org          | `yes/no`  |                                                 |
Jonas Jelonek   | meshlab484.spdns.org    | `no`      | `hot7ThrzP1MV8nlfgrTMuep7zMrOOcGaLjTPrsFI5xA=`  | 10.10.222.48/24
Benedikt Streicher | bstreicher.ddnss.eu  | `no`      | `EeEcwSzW5xIlqILEBpgjGffcCcWjn2P+npo7wUjNGjQ=`  | 10.10.222.50/24
Paul Schreiber  | meshlab.schreiber-p.de  | `no`  | `oXc+CvulGlVYVynvIAbipWchnzBJGsJ8f7OgglM5jBs=`  | 10.10.222.55/32
LarryAn         | thatismy.ddnss.de       | 'yes/no'
Vivi Probst     | vprobst.twn.de          | `yes `    |                                                 | 



<br>
<br>

<b id="f1">1</b> To check weather your ISP puts your behind a [CG-NAT](https://en.wikipedia.org/wiki/Carrier-grade_NAT) with changing public IP's, run: <br>`curl ipecho.net/plain -w "\n"; curl ifconfig.me/ip -w "\n"; curl ident.me -w "\n"` <br> from your OpenWrt terminal. If your the three IPs differ, you got probably CG-NATed [↩](#a1)

[1]: https://en.wikipedia.org/wiki/Fully_qualified_domain_name
[2]: https://en.wikipedia.org/wiki/Carrier-grade_NAT
[3]: https://www.wireguard.com/
