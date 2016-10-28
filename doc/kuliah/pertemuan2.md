Background
==========
There is also the Address Resolution Protocol (ARP) spoofing, also known as ARP Poison Routing (APR), is a technique used to attack an Ethernet wired or wireless network. ARP Spoofing can allow an attacker to sniff data frames on a local area network (LAN), modify the traffic,

or stop the traffic altogether (known as a denial of service attack). Attacks can only be used on networks that actually make use of ARP and not another method of address resolution.

The principle of ARP spoofing is by sending a fake, or "spoofed", ARP messages to an Ethernet LAN. In general, the aim is to associate the attacker's MAC address with the IP address of another node (such as the default gateway). Any traffic that is intended for IP addresses will be mistakenly sent to the attacker alone. The attacker can then choose to forward the traffic to the actual default gateway (passive sniffing) or modify the data before forwarding it (man-in-the-middle attack). Attackers can also launch a denial-of-service attack against a victim by associating the MAC address that does not exist to the default gateway IP address of the victim. ARP spoofing attacks can be launched from compromised host, or from the attacker's machine that is connected directly to the target Ethernet segment.

Solutions to prevent IP spoofing is a way to secure packet-packet transmitted and installing screening policies. Encryption Point-to-point also can prevent users who do not have the right to read the data / packet. Authentication can also be used to screen the legal source and not a source that is already in a spoof by the attacker. In other precautions, Admininistrator can use signatures to packages that communicate in their network, so as to ensure that the package is not modified in transit.

Anti-Spoofing rules (anti-spoof rules) which basically tells the server to reject the packet that comes from outside is seen coming from the inside, generally it will break any spoofing attacks.

**Conclusions and recommendations**
Network security may not be able to secure a network that can not be hacked but there he tested an IT Support, then it can only prevent it.
