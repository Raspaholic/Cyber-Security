TARGET DECK: A+ Core 1::3.5 Install Replace Appropriate Power Supply

START
Basic
Alternating Current (AC) PSU
Back:
- Cycled between positives and negatives repeatedly
Tags: OBJ3.5, Power_Supply_Unit_PSU, PSU, Alternating_Current_AC, AC
<!--ID: 1731877000675-->
END

START
Basic
Main Purpose of PSU
Back:
- to deliver DC to all components when receiving AC power supply 
Tags: OBJ3.5, PSU_Purpose, PSU
<!--ID: 1731877000678-->
END

START
Basic
Modular PSU
Back:
- allows to unhook connectors and detach from the unit
- frees up space inside of computer 
Tags: OBJ3.5, Modular_PSU, PSU
<!--ID: 1731877000680-->
END

START
Basic
120V AC (Low Line Power)
Back:
- US-based power supply
- Common in North America and parts of Asia.
- Lower voltage that some power supplies can be set to use by a physical switch
Tags: OBJ3.5, 120V_AC, Low_Line_Power, 
<!--ID: 1731877000683-->
END

START
Basic
230V AC (High Line Power)
Back:
- Europe and Asia power supply
- Standard in Europe and other regions. 
- Higher voltage; more efficient in delivering power over long distances
Most power supplies support multi-voltage outputs
Tags: OBJ3.5, 230V_AC, High_Line_Power
<!--ID: 1731877000685-->
END

START
Basic
Voltage Sensing / Dual Voltage Power Supplies
Back:
- Detects the outlet and converts into DC voltage 
- Many power supplies support both 110-120V and 220-240V and have an auto-switching feature, or a manual switch, to adapt to different regional voltages
Tags: OBJ3.5, Voltage_Sensing, Dual_Voltage_Power_Supplies
<!--ID: 1731877000687-->
END

START
Basic
Rail
Back:
- wire that provides current at specific voltage 
	- 12 VDC Rail
		- wire that provides 12 DVC 
		- 12 DVC rail most used voltage in the PC
Tags: OBJ3.5, Rail, 12V_DC_Rail
<!--ID: 1731877000690-->
END

START
Basic
Wattage Rating
Back:
- PSU output capacity or capability
- the devices inside the PC require power from PSU
Tags: OBJ3.5, Wattage_Rating, PSU
<!--ID: 1731877000692-->
END

START
Basic
Amperage to Wattage
Back:
- A x V
- I x V
![[Component Power Usage.png]]
**PSU has increments of 50 or 100 Watts**:
- buy a PSU that's bigger than calculated
**How much power is being drawn out of a wall outlet?**
- 500-watt PSU that's 70% efficient will draw 714 watts 
- 500-watt PSU that's 80% efficient will draw 625 watts 
PSU aren't 100% efficient 
Tags: OBJ3.5, Amperage_to_Wattage, AxV, LxV
<!--ID: 1731877000695-->
END

START
Basic
24-pin Connector
Back:
power from main motherboard 
	20-pin, 20+4 pin, or 24-pin
Tags: OBJ3.5, 24-pin, 20-pin, 20+4-pin
<!--ID: 1731877000698-->
END

START
Basic
Main Board / Motherboard Adapter
Back:
- provides power to the motherboard 
Tags: OBJ3.5, Main_Board_Adapter, Motherboard_Adapter
<!--ID: 1731877000700-->
END

START
Basic
ATX Standard
Back:
- 20-pin connector
- Older ATX standard, with fewer connections for power
Tags: OBJ3.5, 20-pin, Old_ATX_Standard
<!--ID: 1731877000702-->
END

START
Basic
ATX 12V
Back:
24-pin connector 
- Updated ATX standard 
- adds 4 additional pins to support more powerful motherboards
Tags: OBJ3.5, ATX_12V, 24-pin, Updated_ATX_Standard
<!--ID: 1731877000704-->
END

START
Basic
20+4 Pin Connector
Back:
- 2 connectors coupled together before installing into 24-pin connector 
	- flexible motherboard power connector 
	- combines 20-pin connector w/ opt 4-pin attachment
		- allows it to support both 20-pin and 24-pin motherboards 
	- designed for backward compatibility 
	- can be used with older motherboards req 20-pin or newer motherboards req 20+4-pin connector 
	- used in power supplies 
Tags: OBJ3.5, 20+4-pin, 20-pin, 4-pin
<!--ID: 1731877000706-->
END

START
Basic
Redundant Power Supply
Back:
- provides backup power source in case one unit fails 
- common in servers & critical systems to ensure continuous operation, especially in data servers 
- redundant PSUs often configured in pairs, allowing one to take over immediately if the other fails 
Tags: OBJ3.5, Redundant_Power_Supply, PSU
<!--ID: 1731877000709-->
END

START
Basic
Modular Power Supply
Back:
- type of PSU with removable cables 
- reduces clutter in the case by only using necessary cables 
	- improves airflow and simplifies cable management 
- types: full modular (all cables are detachable) semi-modular (some essential cables are fixed, like motherboard and CPU connectors)
Tags: OBJ3.5, Modular_Power_Supply, PSU
<!--ID: 1731877000711-->
END

START
Basic
Wattage Rating
Back:
- maximum power the PSU can deliver, measured in watts (W)
- determines total power available for all components
	- higher wattage is needed for high-performance systems with powerful GPUs and CPUs 
- always select a PSU with a wattage rating slightly above your system's requirements for better efficiency and future upgrades
Tags: OBJ3.5, Wattage_Rating
END

START
Basic
Installing a PSU
Back:
ESD Safe practices
	1. take out PSU
	2. orientate PSU with fan for case 
	3. line up holes, screw in
	4. 24-pin cord plug into motherboard power on back of PSU
	5. 6+2 connector for PCIe x16 graphics card, plug into PSU
	6. plug in CPU power with cord next to PCIe plug
	7. plug in SATA cable into SATA PATA port on PSU 
	8. plug in PCI x16 cable for graphics card into PSU
	9. connect main board power cord 24-pin to motherboard 
	10. connect power to CPU with 8-pin plug
	11. check setting on PSU for 120V
Tags: OBJ3.5, Install_PSU
<!--ID: 1731877000714-->
END

START
Basic
Processor Power / CPU Power
Back:
- has 4, 6, or 8 pin connector 
- 8-pin plug/connector where CPU is
PCIe connectors 
	6+2
Tags: OBJ3.5, Processor_Power, CPU_Power, 4-pin, 6-pin, 8-pin, 6+2pin, PSU_Connectors
<!--ID: 1731877000716-->
END

START
Basic
SATA Power Connectors
Back:
15-pin connector 
	connects to different drives to give power 
Tags: OBJ3.5, SATA_Power_Connectors, SATA, 15-pin, PSU_Connector
<!--ID: 1731877000719-->
END

START
Basic
Molex Connector
Back:
- used for IDE and PATA hard disks, CDs, and DVD drives
- 4-pin round pin connector 
- old devices like tape backup drive or really old hard drive, CD, DVD player
Tags: OBJ3.5, Molex_Connector, 4-pin, PSU_Connector
<!--ID: 1731877000721-->
END

START
Basic
Y Connector
Back:
- 1 connector that can support multiple devices
Tags: OBJ3.5, Y_Connector, PSU_Connector
<!--ID: 1731877000723-->
END