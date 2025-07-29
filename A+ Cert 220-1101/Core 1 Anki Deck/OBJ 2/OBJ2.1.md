TARGET DECK: A+ Core 1::2.1 TCP UDP Ports Protocols Purposes

START
Basic
File Transfer Protocol (FTP)
Back:
	 ports 20, 21
	 provides insecure file transfers
Tags: OBJ2.1, File_Transfer_Protocol_FTP, Port_20_21
<!--ID: 1730932030675-->
END

START
Basic
Secure Shell (SSH)
Back:
	 Port 22
	 Provides secure file transfers 
Tags: OBJ2.1, Secure_Shell_SSH, Port_22
<!--ID: 1730932076779-->
END

START
Basic
	port 23
	provides insecure remote control of another machine using a text-based environment
Back:
Telnet
Tags: OBJ2.1, Telnet, Port_23
<!--ID: 1730932153243-->
END

START
Basic
Simple Mail Transfer Protocol (SMTP)
Back:
	 port 25
	 provides the ability to send emails over the network
Tags: OBJ2.1, Simple_Mail_TX_Protocol_SMTP, Port_25
<!--ID: 1730932153260-->
END

START
Basic
Domain Name Service (DNS)
Back:
	 port 53
	 converts domain names to IP addresses, and vice versa
Tags: OBJ2.1, Domain_Name_Service_DNS, Port_53
<!--ID: 1730932462207-->
END

START
Basic
Dynamic Host Control Protocol (DHCP)
Back:
	 ports 67, 68
	 automatically provides network parameters such as assigned IP address, subnet mask, default gateway, and the DNS server
Tags: OBJ2.1, Dynamic_Host_Control_Protocol_DHCP, Port_67_68
<!--ID: 1730932462218-->
END

START
Basic
Hypertext Transfer Protocol (HTTP)
Back:
	 port 80
	 used for insecure web browsing
Tags: OBJ2.1, Hyper_TX_Protocol_HTTP
<!--ID: 1730932462224-->
END

START
Basic
Post Office Protocol 3 (POP3)
Back:
	port 110
	 used for receiving incoming emails 
Tags: OBJ2.1, Post_Office_Protocol_POP3, Port_110
<!--ID: 1730932462228-->
END

START
Basic
Network Basic Input/Output System (NetBIOS)
Back:
	 ports 137, 139
	 used for file or printer sharing in a Windows network 
Tags: OBJ2.1, NetBIOS, Port_137_139
<!--ID: 1730932462232-->
END

START
Basic
Internet Mail Application Protocol (IMAP)
Back:
	port 143
	 newer method of retrieving incoming emails which improves upon the older POP3
Tags: OBJ2.1, Internet_Map_App_Protocol_IMAP, Port_143
<!--ID: 1730932462237-->
END

START
Basic
Simple Network Management Protocol (SNMP)
Back:
	ports 161, 162 
	 used to collect data about network devices and monitor their status
Tags: OBJ2.1, Simple_Network_Mgmt_Protocol_SNMP, Port_161_162
<!--ID: 1730932462242-->
END

START
Basic
Lightweight Directory Access Protocol (LDAP)
Back:
	port 389
	 used to provide directory services to your network 
Tags: OBJ2.1, Light_Directory_Access_Protocol_LDAP, Port_389
<!--ID: 1730932685272-->
END

START
Basic
Hypertext Transfer Protocol - Secure (HTTPS)
Back:
	port 443
	 used as secure and encrypted version of web browsing
		- SSL (Secure Socket Layer)
		- TLS (Transport Layer Security)
Tags: OBJ2.1, HTTPS, Secure_Socket_Layer, Transport_Layer_Sec, Port_443
<!--ID: 1730932743712-->
END

START
Basic
Server Message Block (SMB)
Back:
	- port 445
	- used for windows file and printer sharing services 
Tags: OBJ2.1, Server_Message_Block_SMB, Port_445
<!--ID: 1730933063019-->
END

START
Basic
Remote Desktop Protocol (RDP)
Back:
	- port 3389 
	- provides graphical remote control of another client or server 
	- RDP provides a full graphical user interface
Tags: OBJ2.1, Remote_Desktop_Protocol_RDP, Port_3389
<!--ID: 1730933063035-->
END

START
Basic
Trivial File Transfer Protocol (TFTP)
Back:
	- ports 69
	- connectionless protocol that uses UDP as its transport
Tags: OBJ2.1, Trivial_File_TX_Protocol_TFTP, Port_69
<!--ID: 1730933199461-->
END

START
Basic
TCP Transmission Control Protocol (Connection-Oriented)
Back: 
	- SSH, HTTP, or HTTPS 
	- reliable (3-way handshake), reliable way to transport segments across the network 
	- connection-oriented 
	- segment retransmission & flow control (windowing)
	- with segmentation of sequencing 
	- with acknowledgement
Tags: OBJ2.1, TX_Control_Protocol_CX_Oriented_TCP, SSH, HTTP, HTTPS
<!--ID: 1730933319492-->
END

START
Basic
UDP User Datagram Protocol (Connectionless)
Back:
- Audio, video streaming, DHCP, and TFTP
	- not reliable 
	- connectionless 
	- no retransmission & no windowing 
	- w/o sequencing 
	- w/o acknowledgement
	- transmits in segments called data grams 
Tags: OBJ2.1, User_Datagram_Protocol_UDP_Connectionless, DHCP, TFTP
<!--ID: 1730933480187-->
END

