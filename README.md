# 42 - Net Practice


<div align="center">

<p align="center">

<img src="https://game.42sp.org.br/static/assets/achievements/netpracticen.png" alt="NetPractice" />
<!-- <img src="https://i2.wp.com/www.aponia-dental-center.com/fachzahnarztliche-praxis/wp-content/uploads/2014/01/work-in-progress.png?fit=286%2C253" alt="Working Progress" /> -->
</p>

</div>

## Definitions:
* TCP: **T**ransmission **C**ontrol **P**rotocol / Transport layer
* IPV4: - 32bit number protocol.
* CIDR Notation (`/24`): [**C**lassless **I**nter-**D**omain **R**outing (**CIDR**)]
	* This form represents the mask as a slash "/", followed by the number of bits that serve as the network address.
	* `255.255.255.128` is equivalent to a mask of `/25` using the CIDR notation
* Switch: Connects multiple devices together in a single network.
	* Cannot talk directly to a network outside
	* It only distributes packets to its local network
* Router: Router connects multiple networks together.
	* In Netpractice this is visualized by the so called **Interface**.

"Typically, a switch operates inside a network whereas a router works as an interface between two different networks or sub-networks."

* In this project: Using IPv4, not IPv6.
* IPv4-address is a 32-bit number divided into 4 "blocks", each 8 bits.
* The first address is reserved as the network-address
* The last address is reserved as a broadcast-address
* octet = 8bits
* 1111 1111 = 255

## Mask
Decide which range of ip-addresses are part of the same subnet.
Two notation to mask:
* Decimal notation. Ex: `255.255.255.0`
* CIDR - Class Inter Domain Routing. Ex: `/24`

| CIDR | Dot-decimal | Number of IP-addresses<br /> per subnet | Usable IP-addresses <br /> per subnet | Number of subnets |
| :---: | :-----------: | :---: | :---: | :---: |
| /32 | 255.255.255.255 | 1 | 0 | 256 |
| /31 | 255.255.255.254 | 2 | 0 | 128 |
| /30 | 255.255.255.252 | 4 | 2 | 64 |
| /29 | 255.255.255.248 | 8 | 6 | 32 |
| /28 | 255.255.255.240 | 16 | 14 | 16 |
| /27 | 255.255.255.224 | 32 | 30 | 8 |
| /26 | 255.255.255.192 | 64 | 62 | 4 |
| /25 | 255.255.255.128 | 128 | 126 | 2 |
| /24 | 255.255.255.0 | 256 | 254 | 1 |



## Links:
* [GitHub - Laubester](https://github.com/Laubester/NetPractice)
* [GitHub - tblaase](https://github.com/tblaase/Net_Practice)
* [GitHub - viruskizz](https://github.com/viruskizz/42bangkok-netpractice)
* [IP Subnet Calc.](https://www.calculator.net/ip-subnet-calculator.html)
* [Routers vs. Switches vs. Access Points](https://www.youtube.com/watch?v=Vc16CCAAz7Q)
* [Subnet Mask](https://www.youtube.com/watch?v=s_Ntt6eTn94)

