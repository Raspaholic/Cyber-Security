TARGET DECK: A+ Core 1::2.4 Services By Networked Hosts

START
Basic
Domain Name System (DNS) Server
Back:
- translates human-readable domain names into IP addresses computers use to identify each other on the network 
1. user types domain name into their browser, request is sent to server
2. DNS server resolves the domain to the correct IP address, enables browser to locate requested site/resource 
- simplifies navigation
- enables large networks to have centralized management of address translation 
- DNS can be configured to direct traffic to different IP addresses for the same domain, aids load balancing and provides redundancy 
Tags: OBJ2.4, DNS_Server
<!--ID: 1730940861699-->
END

START
Basic
Dynamic Host Configuration Protocol (DHCP) Server
Back:
- dynamically assigns IP addresses and other network configuration details (like gateway/DNS addresses) to devices on network 
1. when device connects to a network, sends broadcast request for an IP address 
2. DHCP server responds with IP address from its pool: along with configuration info, allows device to communicate on the network 
- automated IP address assignments: eliminates need for manual IP configuration 
- Prevents IP Conflicts: ensures each device gets unique IP address preventing conflicts 
- frees up addresses when devices disconnect, making available for other devices 
Tags: OBJ2.4, DHCP_Server, dynamic-IP, automated_IP
<!--ID: 1730940861701-->
END

START
Basic
Server
Back:
Server:
- can be configured to allow the clients on the network to access the network and be able to read and write to its disk (file share)
Tags: OBJ2.4, Fileshare, Server
<!--ID: 1730940861704-->
END

START
Basic
Print Server
Back:
- another server that could be a physical workstation or network infrastructure that provides printing functionality
Tags: OBJ2.4, Print_Server
<!--ID: 1730940861705-->
END

START
Basic
Windows-based File / Print server
Back:
- relies on the NetBIOS protocol or SMB
	- Network Basic Input/Output System (NetBIOS):
		- ports 137, 139
		- used for file or printer sharing  in a windows network 
	- Server Message Block (SMB):
		- port 445 
		- used for Windows file and printer sharing services 
Tags: OBJ2.4, Windows_File_Print_Server, NetBIOS, Port_137_139, Server_Message_Block_SMB, Port_445
<!--ID: 1730940861707-->
END

START
Basic
Samba
Back:
- provides the ability for a Linux or Unix server to be able to host files or printers that can then be used by Windows clients running the SMB protocol 
Tags: OBJ2.4, Samba, Linux, Unix, Server_Message_Block_SMB
<!--ID: 1730940861709-->
END

START
Basic
Linux / Unix-based File / Print Server
Back:
- supports windows machines known as Samba 
	- File Transfer Protocol (FTP):
		- ports 20, 21 
			- provides insecure file transfers
Tags: OBJ2.4, Linux, Unix, File_Print_Server, Samba, File_TX_Protocol_FTP, Port_20_21, Insecure-File-Transfers
<!--ID: 1730940861711-->
END

START
Basic
IP-based File / Print Server / Cloud Printing
Back:
- allows for printing anywhere in the world
Tags: OBJ2.4, IP_File_Print_Server, Cloud_Printing
<!--ID: 1730940861714-->
END

START
Basic
Email Server
Back:
- Servers that are set up to compose a message and send it to another user 
Tags: OBJ2.4, Email_Server
<!--ID: 1730940861716-->
END

START
Basic
Simple Mail Transfer Protocol (SMTP)
Back:
- Specifies how emails should be delivered from one mail domain to another 
- Send mail transfer protocol 
- SMTP operates over port 25
Tags: OBJ2.4, Simple_Mail_TX_Protocol_SMTP, Port_25
<!--ID: 1730940861718-->
END

START
Basic
Post Office Protocol 3 (POP3)
Back:
- older email protocol which operates over port 110
Tags: OBJ2.4, Post_Office_Protocol_3_POP3, Port_110
<!--ID: 1730940861720-->
END

START
Basic
Internet Message Access Protocol (IMAP)
Back:
- Mail retrieval protocol 
	- IMAP operates over port 143 and can connect to a server and receive and read messages 
Tags: OBJ2.4, Internet_Message_Access_Protocol_IMAP, Port_143
<!--ID: 1730940861722-->
END

START
Basic
Microsoft Exchange
Back:
- mailbox server environment designed for Windows-based domain environments
- Microsoft Exchange Server is widely used in many corporate environments 
Tags: OBJ2.4, Microsoft_Exchange, Windows, Microsoft_Exchange_Server
<!--ID: 1730940861724-->
END

START
Basic
Syslog
Back:
- enables different appliances and software applications to transmit logs to a centralized server 
- Syslog is the de facto standard for logging events 
	- PRI code (Priority code)
	- Header
	- Message 
Tags: OBJ2.4, Syslog, Priority_code, Header, Message
<!--ID: 1730942188626-->
END

START
Basic
Web Servers
Back:
- Any server that provides access to a website 
	- HTTP:
		- port 80
	- HTTPS:
		- port 443
- When a web browser connects to a server, it will be able to see a digital certificate to create a random code
Tags: OBJ2.4, Web_Servers, HTTP, Port_80, HTTPS, Port_443
<!--ID: 1730942188643-->
END

START
Basic
Internet Information Services (IIS)
Back:
- extensible web server software, created by Microsoft (HTTP, HTTP/2, and HTTPS)
Tags: OBJ2.4, Web_Servers, Internet_Information_Services_IIS, HTTP, HTTP-2, HTTPS
<!--ID: 1730942188647-->
END

START
Basic
Apache
Back:
- Most popular way to run a web server these days 
Tags: OBJ2.4, Web_Servers, Apache
<!--ID: 1730942188652-->
END

START
Basic
NGINX
Back:
- reverse proxy, load balancer, mail proxy, and HTTP cache
Tags: OBJ2.4, Web_Servers, NGINX, Reverse_Proxy, Load_Balancer, Mail_Proxy, HTTP_Cache
<!--ID: 1730942188656-->
END

START
Basic
Uniform Resource Locator (URL)
Back:
- combines the fully qualified domain name with a protocol at the beginning
Tags: OBJ2.4, Uniform_Resource_Locator_URL
<!--ID: 1730942188661-->
END

START
Basic
802.1x
Back:
- standardized framework used for port-based authentication on weird and wireless networks 
Tags: OBJ2.4, 802.1x, AAA, Port-based_Authentication
<!--ID: 1730942188665-->
END

START
Basic
Authentication
Back:
- occurs when a person's identity is established with proof and is confirmed by the system
	- smth yk
	- smth you are 
	- smth you have 
	- smth you do 
	- somewhere you are 
Tags: OBJ2.4, AAA, Authentication 
<!--ID: 1730942188670-->
END

START
Basic
Authorization
Back:
- occurs when a user is given access to a certain piece of data or certain areas of a building
Tags: OBJ2.4, AAA, Authorization
<!--ID: 1730942188675-->
END

START
Basic
Accounting
Back:
- ensures the tracking of data, computer usage, and network resources is maintained
Tags: OBJ2.4, AAA, Accounting
<!--ID: 1730942188680-->
END

START
Basic
Lightweight Directory Access Protocol (LDAP)
Back:
- a database used to centralize information about clients and objects on the network 
Tags: OBJ2.4, AAA, Lightweight_Directory_Access_Protocol_LDAP
<!--ID: 1730942188684-->
END

START
Basic
Active Directory (AD)
Back:
- used to organize and manage the network, including clients, servers, devices, users, and groups
Tags: OBJ2.4, AAA, Active_Directory_AD
<!--ID: 1730942188689-->
END

START
Basic
Remote Authentication Dial-In User Service (RADIUS)
Back:
- provides centralized administration of dial-up, VPN, and wireless authentication services for 802.1x and the EAP
	- RADIUS operates at the application layer
	- RADIUS utilizes UDP for making connections
Tags: OBJ2.4, AAA, Remote_Auth_Dial-In_User_Service_RADIUS, VPN, 802.1x, EAP
<!--ID: 1730942188695-->
END

START
Basic
Terminal Access Controller Access-Control System Plus (TACACS+)
Back:
- proprietary version of RADIUS that can perform the role of an authenticator in 802.1x networks 
Tags: OBJ2.4, AAA, Terminal_Access_Controller_Access-Control_System_Plus_TACACS+, RADIUS, 802.1x 
<!--ID: 1730942188700-->
END

START
Basic
Kerberos
Back:
- Authentication protocol used by Windows to provide for two-way (mutual) authentication using a system of tickets 
- domain controller can be a single point of failure for Kerberos
Non-repudiation:
- occurs when you have proof that someone has taken action 
![[Kerberos.png]]
Tags: OBJ2.4, AAA, Kerberos, Windows, Non-repudiation
<!--ID: 1730942188705-->
END

START
Basic
Spam Gateways
Back:
- filters/blocks unwanted spam before it reaches the end user's inbox
1. positioned at networks entry point: spam gateway inspects incoming emails for spam characteristics 
	- known spam keywords, suspicious links, patterns commonly used in spam emails to adapt to new spam methods 
2. many spam gateways use machine learning and heuristic analysis to identify spam patterns, enabling them to adapt to new spam methods 
- reduces inbox clutter 
- enhances security: prevents phishing, malware, other threats 
- saves bandwidth: blocks spam at gateway level: reducing volume of emails to be delivered
Tags: OBJ2.4, Internet_Appliances, Spam_Gateways, Spam, Heuristic_Analysis, Phishing, Malware
<!--ID: 1730942553790-->
END

START
Basic
Unified Threat Management (UTM)
Back:
- Provides the ability to conduct security functions within a single device or network appliance 
![[UTM Adv Dis.png]]
Tags: OBJ2.4, Unified_Threat_Management_UTM
<!--ID: 1730942553798-->
END

START
Basic
Access Control List (ACL)
Back:
- rule sets placed on the firewalls, routers, and other network devices that permit or allow traffic through a particular interface 
- The actions are performed top-down inside of an ACL
	- Top 
		- specific rules
	- Bottom
		- generic rules 
Tags: OBJ2.4, Internet_Appliances, Access_Control_List_ACL
<!--ID: 1730942553802-->
END

START
Basic
Firewall
Back:
- inspects and controls the traffic that's trying to enter or leave a network's boundary
	- packet-filtering
	- stateful
	- proxy
	- dynamic packet-filtering 
	- kernel proxy 
Tags: OBJ2.4, Internet_Appliances, Firewall, Packet-filtering, Stateful, Proxy, Dynamic_Packet-filtering, Kernel_Proxy
<!--ID: 1730942553807-->
END

START
Basic
Load Balancer/Content Switch
Back:
- distributes incoming requests across several servers inside a server farm or a cloud infrastructure
- A load balancer is one of the key things to help defend against a DoS attack or a DDoS attack
Tags: OBJ2.4, Load_Balancer, Content_Switch, DDoS_Attack
<!--ID: 1730944606302-->
END

START
Basic
Denial of Service (DoS)
Back:
- Involves a continual flooding of victim systems with requests for services causing the system to crash (single attacker)
Tags: OBJ2.4, Load_Balancer, Denial_of_Service_DoS, single-attacker, Load_Balancer, Content_Switch
<!--ID: 1730944606319-->
END

START
Basic
Distributed Denial of Service (DDoS)
Back:
- multiple machines simultaneously launch attacks on the server to force it offline (multiple attackers)
Tags: OBJ2.4, Load_Balancer, Content_Switch, Distributed_Denial_of_Service_DDoS, multiple-attackers
<!--ID: 1730944606324-->
END

START
Basic
Blackholing / Sinkholing
Back:
- identifies any attacking IP addresses and routes their traffic through a null interface 
Tags: OBJ2.4, Load_Balancer, Content_Switch, Blackholing_Sinkholing, null-interface
<!--ID: 1730944606329-->
END

START
Basic
Intrusion Prevention System (IPS)
Back:
- works for small-scale attacks against DoS 
Tags: OBJ2.4, Load_Balancer, Content_Switch, Intrusion_Prevention_System_IPS, Denial_of_Service_DoS
<!--ID: 1730944606333-->
END

START
Basic
Elastic Cloud
Back:
- allows to scale up demand as needed 
Tags: OBJ2.4, Load_Balancer, Content_Switch, Elastic_Cloud
<!--ID: 1730944606338-->
END

START
Basic
Proxy Server
Back:
- devices that create a network connection between an end user's client machine and a remote resource (web server)
	- increased network speed and efficiency
	- increased security 
	- additional auditing capabilities
Tags: OBJ2.4, Proxy_Servers
<!--ID: 1730944606342-->
END

START
Basic
Information Technology (IT)
Back:
- includes computers, servers, networks, and cloud platforms
Tags: OBJ2.4, Legacy_Embedded_Systems, Supervisory_Control_Data_Aquisition_SCADA, Information_Technology_IT
<!--ID: 1730944606348-->
END

START
Basic
Operational Technology (OT)
Back:
- communications network designed to implement an ICS 
- Technology that interacts with the real world 
Tags: OBJ2.4, Legacy_Embedded_Systems, Supervisory_Control_Data_Aquisition_SCADA, Operational_Technology_OT
<!--ID: 1730944606352-->
END

START
Basic
Industrial Control Systems (ICS)
Back:
- provides the mechanisms for workflow and process automation by controlling machinery using embedded devices 
- multiple ICSs can create a distributed control system (DCS)
Tags: OBJ2.4, Legacy_Embedded_Systems, Supervisory_Control_Data_Aquisition_SCADA, Industrial_Control_Systems_ICS, Distributed_Control_System_DCS
<!--ID: 1730944606357-->
END

START
Basic
Supervisory Control and Data Acquisition (SCADA)
Back:
- type of ICS used to manage large scale multi-site devices and equipment in a geographic region from a host computer 
Tags: OBJ2.4, Legacy_Embedded_Systems, Supervisory_Control_Data_Aquisition_SCADA
<!--ID: 1730944606361-->
END

START
Basic
Fieldbus
Back:
- digital serial data communication protocol used in Operational Technology networks to link different PLCs
Tags: OBJ2.4, Fieldbus, Operational_Technology, Programmable_Logic_Controller_PLC
<!--ID: 1730944606366-->
END

START
Basic
Programmable Logic Controller (PLC)
Back:
- Type of digital computer used in industrial settings that enables automation and assembly lines, autonomous field operations, robotics, and other applications 
Tags: OBJ2.4, Programmable_Logic_Controller_PLC
<!--ID: 1730944606370-->
END

START
Basic
Human-machine Interface (HMI)
Back:
- can be a local control panel or software that runs on a computer 
Tags: OBJ2.4, Human_Machine_Interface_HMI
<!--ID: 1730944606376-->
END

START
Basic
Embedded Systems
Back:
- computer system that's designed to perform specific and dedicated functions 
- are considered static environments, where frequent changes aren't allowed
Tags: OBJ2.4, Embedded_Systems, static-environment
<!--ID: 1730944606380-->
END

START
Basic
Real-time Operating System (RTOS)
Back:
- OS that prioritizes deterministic execution of operations that ensures consistent response for time-critical tasks
- embedded systems in critical applications 
Tags: OBJ2.4, Real-time_Operating_System_RTOS, Embedded_Systems
<!--ID: 1730944606385-->
END

START
Basic
Legacy System
Back:
- computer system that's no longer supported by its vendor and no longer provided with security updates and patches
- identify legacy systems and put mitigations in place to keep operating as such systems 
Tags: OBJ2.4, Legacy_System
<!--ID: 1730944606390-->
END

START
Basic
Proprietary System
Back:
- system that's owned by its developer or vendor 
Tags: OBJ2.4, Proprietary_System
<!--ID: 1730944606394-->
END

START
Basic
Internet of Things (IoT) Devices
Back:
- global network of appliances and personal devices that's equipped with sensors, software, and network connectivity to report state and configuration 
	- segregation of IoT devices is critically important for the business network's security
Tags: OBJ2.4, Internet_of_Things_IoT, IoT_Devices
<!--ID: 1730944606399-->
END