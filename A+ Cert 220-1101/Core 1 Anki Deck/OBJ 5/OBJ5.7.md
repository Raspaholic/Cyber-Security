TARGET DECK: A+ Core 1::5.7 Troubleshoot Problems with Wired & Wireless Networks

START
Basic
Wired Connectivity Issues
Back:
- Physical connection
- Cable length
- Interference 
- Port flapping 
- link light shows valid link 
Activity light blinks when sending or receiving data:
- 10 Mbps (off)
- 100 Mbps (Orange)
- 1000 Mbps (Green)

repeater is used to increase the connectivity signal 
Tags: OBJ5.7, Wired_Connectivity_Issues
<!--ID: 1732126635738-->
END

START
Basic
Standards Mismatch
Back:
- intermittent wireless connectivity: connected or disconnected network 
- Intermittent wired connectivity: upstate to downstate of switch port 

- Signal interference is causing signal issues
- Channels 1, 6, and 11 spread out the network and avoid interference 
- Wireless a, n, ac, and ax are less prone to signal interference 
Tags: OBJ5.7, Wired_Connectivity_Issues, Standards_Mismatch, Intermittent_Wireless_Connectivity, Intermittent_Wired_Connectivity
<!--ID: 1732126635743-->
END

START
Basic
Received Signal Strength Indicator (RSSI)
Back:
- used to measure the signal strength based on an index level and gives a value in decibels (dB)
Tags: OBJ5.7, Wired_Connectivity_Issues, Received_Signal_Strength_Indicator_RSSI, RSSI
<!--ID: 1732126635745-->
END

START
Basic
RSSI Displayed in Negative dB's
Back:
- increase the power of transmission
- increase the antenna size 
- move closer to the source 
- wireless a, n, ac, and ax 5 GHz
- wireless b, g, or n 2.4 GHz

		What frequency is being used?
		what is the maximum speed of that frequency?
		which versions of wireless networking are being used?

configure the wireless access points to support the modern versions of the protocols 
Tags: OBJ5.7, Wired_Connectivity_Issues, RSSI_Displayed_Negative_dB's
<!--ID: 1732126635747-->
END

START
Basic
Network Performance Issues
Back:
- manifesting the slowdown of network 
Tags: OBJ5.7, Network_Performance_Issues
<!--ID: 1732126635749-->
END

START
Basic
Half Duplex
Back:
- Network that sends or receives information 
- the standard in hubs and networks
Tags: OBJ5.7, Network_Performance_Issues, Half_Duplex
<!--ID: 1732126635752-->
END

START
Basic
Full Duplex
Back:
- network that sends/receives information 
- Network Interface Cards are set to auto negotiation
Tags: OBJ5.7, Network_Performance_Issues, Full_Duplex
<!--ID: 1732126635754-->
END

START
Basic
Data Exfiltration
Back:
sending data in the background w/o the user seeing it
1. mismatch in the duplex setting 
2. mismatch in the speed setting 
3. network adapter drivers are out of date 
4. malware infection 
Tags: OBJ5.7, Network_Performance_Issues, Data_Exfiltration
<!--ID: 1732126635757-->
END

START
Basic
Intermittent Wireless Connectivity
Back:
**intermittent wireless connectivity**: connected or disconnected network 
	**Intermittent wired connectivity**: upstate to downstate of switch port 
- connection drops sporadically or disconnects from network 
- causes: distance from access point, physical obstructions, device interference 
- move closer to AP
- remove/rearrange obstacles if possible
- change the AP's frequency channel to reduce interference 
Tags: OBJ5.7, Common_Symptoms, Intermittent_Wireless_Connectivity, Intermittent_Wired_Connectivity
<!--ID: 1732126635759-->
END

START
Basic
Slow Network Speeds
Back:
- limit bandwidth-intensive activities or move devices off of the network 
- test network speed to identify if the issue is with the ISP
- wired networks: check cables for any physical damage 
Tags: OBJ5.7, Common_Symptoms, Slow_Network_Speeds
<!--ID: 1732126635761-->
END

START
Basic
Limited Connectivity
Back:
- specialized message to receive within the operating system 
1. affects one network client 
2. VLAN is properly configured 
- device shows limited/no internet access message 
- DHCP server issues or improper IP configuration 
- Router or modem malfunction 
- renew the IP address (ipconfig /renew in command prompt)
- restart the router / configure IP settings manually if DHCP fails
Tags: OBJ5.7, Common_Symptoms, Limited_Connectivity
<!--ID: 1732126635763-->
END

START
Basic
Limited Connectivity Issues is Having a DHCP Issue
Back: 
- IP address
- Subnet
- Default gateway
- DNS server IPs
Tags: OBJ5.7, Common_Symptoms, Limited_Connectivity_Issues_Having_DHCP_Issue
<!--ID: 1732126635765-->
END

START
Basic
Jitter
Back:
- measurement of the variation in delay over time 
- when latency increases by up to 30-50 milliseconds, starts to have jitter 
- increase network performance 
- implement quality of service 
- use Quality of Service QoS settings on the router to prioritize traffic 
- reduce bandwidth-hogging activities or upgrade to higher bandwidth if needed 
Tags: OBJ5.7, Common_Symptoms, Jitter, QoS
<!--ID: 1732126635771-->
END

START
Basic
Poor Voice Over Internet Protocol (VoIP) Quality
Back:
Voice Over Internet Protocol (VoIP):
	- set of protocols used to send streaming voice and video in real time 
	  - enable QoS to prioritize VoIP traffic 
- check for network congestion and resolve by minimizing other network use during calls 
Tags: OBJ5.7, Poor_VoIP_Quality, Voice_Over_Internet_Protocol_VoIP, VoIP, Common_Symptoms
<!--ID: 1732126635773-->
END

START
Basic
Port Flapping
Back:
- caused by an intermittent connectivity issue between the client and the network switch
- port flapping status is from upstate to downstate 
- causes: faulty ethernet cables, loose connections, network loop caused by improper switch setup 
- replace or resecure cables 
- inspect switch settings to ensure proper loop prevention settings (like Spanning Tree Protocol)
Tags: OBJ5.7, Common_Symptoms, Port_Flapping
<!--ID: 1732126635775-->
END

START
Basic
Latency
Back:
Latency:
	- time for signal to reach intended client 
	- keep latency under 50-100 milliseconds 

- causes: long physical distance to the destination server, network congestion, overloaded routers 
- use wired connection for reduced latency 
- contact ISP if latency persists, issue might require network adjustments
Tags: OBJ5.7, Common_Symptoms, High_Latency, Latency
<!--ID: 1732126635777-->
END

START
Basic
External Interference
Back:
interference with wired connections is coming from an external interference source:
		- power lines
		- fluorescent lighting 
		- motors
		- generators 
the network cables near power lines use fiber optic connections 
- change WiFi channel on AP to reduce interference 
- move the router to a central location away from potential interference sources 
Tags: OBJ5.7, Common_Symptoms, External_Interference
<!--ID: 1732126635779-->
END

