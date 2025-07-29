TARGET DECK: A+ Core 1::2.2 Common Networking Hardware

START
Basic
Routers
Back:
- used to connect different networks together
Tags: OBJ2.2, Routers
<!--ID: 1730933667860-->
END

START
Basic
Switches
Back:
- smart hubs that remember the ports that are connected to them
	- switches can have multiple people talking at one time
Managed Switch: 
- performs its functions with configuration 
- features monitoring, control over power distribution, QoS Quality of Service settings, network traffic management 
- ideal for larger networks where admins need control/visibility over network performance 
Unmanaged Switch:
- performs its functions w/o requiring a configuration
Tags: OBJ2.2, Switches, Managed_Switch, Unmanaged_Switch
<!--ID: 1730933667866-->
END

START
Basic
Wireless Access Point (WAP)
Back:
- Device that allows wireless devices to connect to a wired network
Tags: OBJ2.2, Wireless_Access_Point_WAP
<!--ID: 1730933721850-->
END

START
Basic
Patch Panel
Back:
- device that allows cable networks jacks from a wall into a central area 
Tags: OBJ2.2, Patch_Panel
<!--ID: 1730933752577-->
END

START
Basic
Firewall
Back:
- Scans and blocks traffic that enters or leaves a network
	- unified threat management (UTM) contains firewall features 
Tags: OBJ2.2, Firewall, Unified_Threat_Mgmt_UTM
<!--ID: 1730933895695-->
END

START
Basic
Power Over Ethernet (PoE)
Back:
- supplies electrical power from a switch port over an ordinary data cable to a power device 
- allows power/data transmitted over single Ethernet cable 
Power Injector:
- plugs into a wall outlet to get power 
- adds power to a single ethernet connection 
- used when only few PoE-enabled connections are needed 
- used when main switch doesn't support PoE 
PoE Standards: defines amount of power can be delivered over Ethernet cables 
PoE Switch: can send both power/data over ethernet cable
- used for IP phones, WAPs, IP Cameras 
- can deliver power Powered Devices through ethernet cable 
- acts as the Power Sourcing Equipment 
- typically ranging 4-48 ports 
- each port can detect if the device is PoE-compatible, providing power only when necessary 
- integrates PoE on all or selected ports 
Tags: OBJ2.2, PoE, Power_Injector, PoE_Standards, PoE_Switch, Port_4-48
<!--ID: 1730933895714-->
END

START
Basic
PoE Power Budget 
Back:
- total amount of power it can supply across all its ports 
- higher power budgets needed to support more/more power-intensive devices 
Power Classes: PoE devices categorized into pwr classes, helps PoE switch determine amount of power to allocate to each device
Tags: OBJ2.2, PoE_Power_Budget, Power_Classes
<!--ID: 1730933983610-->
END

START
Basic
Class 0
Back:
- 0.44 - 12.95 W (watts)
- default class
Tags: OBJ2.2, Class_0, 0.44-12.95W, default_class
<!--ID: 1730934051406-->
END

START
Basic
Class 1
Back:
- 0.44 - 3.84 W (watts)
- low-power devices 
Tags: OBJ2.2, Class_1, 0.44-3.84W, low_power_devices
<!--ID: 1730934168444-->
END

START
Basic
Class 2
Back:
- 3.84 - 6.49 W (watts)
- slightly higher-powered devices 
Tags: OBJ2.2, Class_2, 3.84-6.49W, slightly_higher_pwr_devices
<!--ID: 1730934269543-->
END

START
Basic
Class 3
Back:
- 6.49 - 12.95 W (watts)
- PoE devices: like basic access points or phones 
Tags: OBJ2.2, Class_3, 6.49-12.95W
<!--ID: 1730934347895-->
END

START
Basic
Class 4
Back:
- 12.95 - 25.5 W 
- PoE+ devices 
Tags: OBJ2.2, Class_4. 12.95-25.5W, PoE+devices
<!--ID: 1730934405745-->
END

START
Basic
Class 5-8
Back:
- higher power ranges for 802.3bt 
- PoE++ / 4-pair 
- up to 60W for Class 5
- up to 100W for Class 8
Tags: OBJ2.2, Class_5-8, Higher_pwr_for_802.3bt, PoE++-4pair, to_60W_Class_5, to_100W_Class_8
<!--ID: 1730934586545-->
END

START
Basic
IEEE 802.3af  (PoE)
Back:
   - released 2003 
   - max power to device: 15.4 watts 
   - voltage at device (PD-powered device): 44-57V DC
   - max current: 350mA
   - power over: 2 pairs of wires (pins 1, 2, 3, and 6) in standard Ethernet cable 
   - common use cases: low-power devices like VoIP phones, basic WAPs, security cameras
   - actual pwr delivered to device slightly lower (~12.95 watts) accounting for power loss over cable
   - Category 5e (Cat5e) recommended
Tags: OBJ2.2, IEEE_802.3af_PoE, max_15.4W, 44-57V_DC_Pwr_Device, max_Current_350mA, Pwr_Ovr_2pairs_Pins1_2_3_6_standardEthernet_Cable
<!--ID: 1730934814185-->
END

START
Basic
IEE 802.3at (PoE+)
Back:
   - released 2009
   - max pwr to device: 25.5 watts 
   - voltage at device: 50-57V DC
   - max current: 600mA
   - power over: 2 pairs of wires, similar to 802.3af, allows for higher current 
   - common use cases: devices requiring more power, pan-tilt-zoom (PTZ) IP cameras, advanced wireless access points, video conference systems
   - backward-compatible with PoE (802.3af), devices designed for this can fall back to reg PoE if connected to a PoE switch 
   - Category 5e (Cat5e) recommended
Tags: OBJ2.2, IEEE_802.3at_PoE+, max_25.5W, 50-57V_DC_Pwr_Device, max_Current_600mA, Pwr_Ovr_2pairs, backward_compatible_802.3af_PoE, Cat5e_Recommended
<!--ID: 1730934987673-->
END

START
Basic
IEEE 802.3bt (PoE++ or 4-Pair PoE)
Back:
   - released 2018
   - max power to device:
	   - Type 3 (PoE++): Up to 60 watts 
	   - Type 4 (PoE++): Up to 100 watts
- voltage at device: 50-57V DC
- max current: 
	- Type 3: 600mA  
	- Type 4: 960mA
- power over: 4 pairs of wires (all 8 conductors in ethernet cable used for pwr delivery) 
- common use cases: 
	- Type 3: high-end WAPs, more complex IP cameras, advanced network equipment
	- Type 4: devices w/ significant pwr needs, building automation systems, digital signage, laptops (through USB-C/PoE combinations)
- Category 6/6a (Cat6/6a) recommended to ensure proper pwr delivery & reduce heat generation over longer cable runs 
Tags: OBJ2.2, IEEE_802.3bt_PoE++, 4pair_PoE, max_60W_PoE++Type3, max_100W_PoE++Type4, 50-57V_DC_Pwr_Device, max_Curr_Type3_600mA, max_Curr_Type4_960mA, Cat6_6a_recomm
<!--ID: 1730935242094-->
END

START
Basic
Types of PoE Devices
Back:
- PSE (Power Sourcing Equipment): device like switch/injector provides power to other devices over ethernet cable 
- PD (Powered Device): device like camera/access point receives power from the PSE
Tags: OBJ2.2, Pwr_Src_Equipment, Powered_Device
<!--ID: 1730935313375-->
END

START
Basic
Hub
Back:
- has several different ports between 4 - 48 ports 
Tags: OBJ2.2, Hub, Port_4-48
<!--ID: 1730935419647-->
END

START
Basic
Cable Modem
Back:
- device that translates coaxial cable signals into radio frequency waves 
Tags: OBJ2.2, Cable_Modem
<!--ID: 1730935419664-->
END

START
Basic
Digital Subscriber Lines (DSL)
Back:
- device that translates coaxial cable signals into phone lines 
Tags: OBJ2.2, Digital_Subscriber_Lines_DSL
<!--ID: 1730935509492-->
END

START
Basic
Optical Network Terminal (ONT)
Back:
- terminates fiber connection
Tags: OBJ2.2, Optical_Network_Terminal_ONT
<!--ID: 1730935509507-->
END

START
Basic
Network Interface Card (NIC)
Back:
- provides ethernet connection to the network 
Tags: OBJ2.2, Network_Interface_Card_NIC
<!--ID: 1730935664421-->
END

START
Basic
Software-defined Network (SDN)
Back:
- way of virtualizing the network hardware 
- enables the network to be intelligently and centrally controlled, or programmed, using software applications
	- can be changed automatically by the network itself using automation and orchestration 
Application Layer:
- focuses on the communication resource requests or information about the network as a whole 
Control Layer:
- uses the information from the applications and decides how to route a data packet on the network 
Infrastructure Layer:
- contains the network devices that recieve information about where to move the data
Management Plane:
- used to monitor traffic conditions and the status of the network 
	- provides a layer of abstraction between the devices and the control and data flow that happens on the network 
Tags: OBJ2.2, Software-defined_Network_SDN, Application_Layer, Control_Layer, Infrastructure_Layer, Mgmt_Plane
<!--ID: 1730935664427-->
END
