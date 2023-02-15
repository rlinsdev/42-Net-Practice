# 42 - Net Practice

## Definitions:
Using IPv4, not IPv6.
IPv4-address is a 32-bit number divided into 4 "blocks", each 8 bits.
11111111 = 255
* The first address is reserved as the network-address
* The last address is reserved as a broadcast-address

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
* [GitHub - Explanation](https://github.com/Laubester/NetPractice) - Todo: Deixar ou add todos?
* [IP Subnet Calc.](https://www.calculator.net/ip-subnet-calculator.html)

