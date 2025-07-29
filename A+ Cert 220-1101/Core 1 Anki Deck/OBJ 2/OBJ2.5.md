TARGET DECK: A+ Core 1::2.5 Install Config Wired Wireless SOHO Networks

START
Basic
Private (Non-Routable)
Back:
- can be used by anyone anytime, but only within their own local area network 
- Private IP ranges include those that start with either 10, 172, or 192
Tags: OBJ2.5, Private_IP, Local_Area_Network_LAN
<!--ID: 1730945782368-->
END

START
Basic
Public (Routable)
Back:
- can be accessed over the internet and is assigned to the network by an internet service provider
Tags: OBJ2.5, Public_IP
<!--ID: 1730945782370-->
END

START
Basic
Multicast Address
Back:
- a logical identifier for a group of hosts in a computer network 
Tags: OBJ2.5, Multicast_Address
<!--ID: 1730945782372-->
END

START
Basic
Classful Mask
Back:
- default subnet mask for a given class of IP addresses 
Tags: OBJ2.5, Classful_Mask
<!--ID: 1730945782374-->
END

START
Basic
Classless inter-Domain Routing (CIDR)
Back:
- allows for borrowing some of the host bits and reassigning them to the network portion
Tags: OBJ2.5, Classless_Inter-Domain_Routing_(CIDR)
<!--ID: 1730945782377-->
END

START
Basic
Network Address Translation (NAT)
Back:
- allows for routing of private IPs through a public IP Loopback Address (127.0.0.1)
- creates a loopback to the host and is often used in troubleshooting and testing network protocols on a system
Tags: OBJ2.5, Network_Address_Translation_NAT, Public_IP_Loopback_Address
<!--ID: 1730945782380-->
END

START
Basic
IPv6
Back:
An IPv6 address uses hexadecimal digits and allows the use of shorthand notation
IPv4 = 2^32:
- 4.2 billion addresses 
Tags: OBJ2.5, IPv6
<!--ID: 1730997700009-->
END

START
Basic
Address Exhaustion
Back:
- running out of network addresses in IPv4 
	- IPv4 = 2^32 
		- 4.2 billion addresses 
	- IPv6 = 2^128 
		- 340 undecillion addresses 
Tags: OBJ2.5, IPv4, IPv6, Address_Exhaustion
<!--ID: 1730997700019-->
END

START
Basic
IPv5
Back:
IPv5 was an experimental protocol but some of its concepts have been incorporated into IPv6:
- larger address space 
- no broadcasts 
- no fragmentation 
- can coexist with IPv4 
- simplified header 
Tags: OBJ2.5, IPv5
<!--ID: 1730997805298-->
END

START
Basic
Dual Stack
Back:
- simultaneously runs both the IPv4 and IPv6 protocols on the same network devices 
Tags: OBJ2.5, Dual_Stack, IPv4, IPv6
<!--ID: 1730997805315-->
END

START
Basic
Tunneling
Back:
- allows an existing IPv4 router to carry IPv6 traffic 
Tags: OBJ2.5, Tunneling, IPv4, IPv6
<!--ID: 1730997805320-->
END

START
Basic
Extended Unique Identifier (EUI)
Back:
- allows a host to assign itself a unique 64-bit IPv6 interface identifier called EUI-64
Tags: OBJ2.5, Extended_Unique_Identifier_EUI, IPv6, EUI-64
<!--ID: 1730998449817-->
END

START
Basic
DHCPv6 Protocol
Back:
- allows DHCP to automatically assign addresses from a DHCPv6 server 
Tags: OBJ2.5, DHCPv6_Protocol, DHCPv6, DHCP
<!--ID: 1730998449823-->
END

START
Basic
IP Address Management
Back:
- manages IPs being assigned and returned over time
Tags: OBJ2.5, IP_Address_Management
<!--ID: 1730998449828-->
END

START
Basic
Automatic Private IP Addressing (APIPA)
Back:
- used when a device does not have a static IP address or cannot reach a DHCP server 
	- 169.254.0.0 to 169.254.255.255
		- Discover
		- Offer
		- Request
		- Acknowledge
Tags: OBJ2.5, Automatic_Priv_IP_Addressing_APIPA, APIPA, 169.254.0.0-169.254.255.255
<!--ID: 1730998449833-->
END

START
Basic
Zero Configuration (ZeroConf)
Back:
- new technology that provides the same features as APIPA 
- assign an IPv4 link-local address to a client 
- Resolve computer names to IP addresses w/o the need for DNS by using mDNS (multicast domain name service)
- perform service discovery on a network 
	- Windows 
		- Link-Local Multicast Name Resolution (LLMNR)
	- Linux
		- SystemD
Tags: OBJ2.5, Zero_Config_ZeroConf, ZeroConf, IPv4_Link-local, Multicast_Domain_Name_Service_mDNS, mDNS, Link-Local_Multicast_Name_Resolution_LLMNR, LLMNR, SystemD
<!--ID: 1730998449839-->
END

START
Basic
Static Assignment
Back:
- manually type the IP address for the host, its subnet mask, default gateway, and DNS server 
- Static assignment of IP addresses is impractical on large enterprise networks 
Tags: OBJ2.5, Static_Assignment, 
<!--ID: 1730998449844-->
END

START
Basic
Dynamic Assingment
Back:
- Dynamic allocation of IP addresses 
Tags: OBJ2.5, Dynamic_Assignment
<!--ID: 1730998449848-->
END

START
Basic
Gateway
Back:
- what serves as entry/exit point for a network 
- connects local network devices to external networks and the internet 
  
In typical SOHO network, gateway is often the **router** 
- routes traffic between local devices and external networks 
	- forwards requests from devices within the network to the correct external destination 

default gateway is IP address of the router within a network: 
- often assigned as first IP in a range, the default path that devices follow when sending data outside of the local network 

How it works?
- sends request to the gateway, gateway forwards this to appropriate destination, response returns and gateway directs back to original device 

Gateway IP usually configured automatically through DHCP on most SOHO routers setup
- users can manually configure the gateway address within the network settings if DHCP isn't used 
Tags: OBJ2.5, Gateway, Router, DHCP
<!--ID: 1730998449853-->
END
