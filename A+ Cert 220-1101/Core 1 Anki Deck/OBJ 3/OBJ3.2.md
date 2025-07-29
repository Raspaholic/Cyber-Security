TARGET DECK: A+ Core 1::3.2 Install Appropriate RAM

START
Basic
Random Access Memory (RAM)
Back:
- used to load applications/files into non-persistent and fast storage area
Tags: OBJ3.2, Random_Access_Memory_RAM, RAM, RAM_Types
<!--ID: 1731604206385-->
END

START
Basic
Single Bank
Back:
- can put any size of module in any slot 
	- Dual inline Memory Module (DIMM)
		- with 240 or 184-pin connector
Tags: OBJ3.2, Single_Bank, Dual_Inline_Memory_Module_DIMM, DIMM, RAM_Types
<!--ID: 1731604206391-->
END

START
Basic
Throughput
Back:
- Calculated based on the bus speed and width of the data bus
Tags: OBJ3.2, RAM_Types, Throughput
<!--ID: 1731604206399-->
END

START
Basic
Virtual Memory / Page File
Back:
- Space on a hard drive that is allocated by the OS and pretends to be memory
	- Check available memory and free memory 
Tags: OBJ3.2, Virtual_Memory, Virtual_RAM, VRAM, RAM_Types
<!--ID: 1731607895836-->
END

START
Basic
Page File / Swap Space
Back:
- file that's hidden on a storage device and pretends as system memory
Tags: OBJ3.2, Virtual_RAM, VRAM, RAM_Types, Page_File, Swap_Space
<!--ID: 1731607895840-->
END

START
Basic
Small Outline Dual In-Line Memory Module (SODIMM)
Back:
- Classified as DDR3, DDR4, or DDR5
- compact vers of standard DIMM RAM, designed primarily for laptops and compact systems 
- usually comes in sizes of 204 pins (DDR3) or 260 pins (DDR4 and DDR5)
- commonly used in laptops, small-form-factor PCs, some high-performance devices w/ limited space 
Tags: OBJ3.2, Small_Outline_Dual_In-Line_Memory_Module_SODIMM, SODIMM, DDR3, DDR4, DDR5, RAM_Types
<!--ID: 1731607895842-->
END

START
Basic
Dynamic Ram (DRAM)
Back:
- oldest type of memory that requires frequent refreshing
	- DRAM storage cell is dynamic 
Tags: OBJ3.2, Dynamic_RAM, DRAM, RAM_Types
<!--ID: 1731607895850-->
END

START
Basic
Synchronous DRAM (SDRAM)
Back:
- First memory module that operates at same speed as motherboard bus (168-pin connector)
	- PC66 (66 MHz bus)
	- PC133 (133 MHz bus)
	- PC266 (266 MHz bus)
Tags: OBJ3.2, Synchronous_DRAM, SDRAM, PC66, PC133, PC266, RAM_Types
<!--ID: 1731607895852-->
END

START
Basic
Dual / Double Data Rate (DDR)
Back:
- Most common type of memory 
	- PC133
		- 133 MHz
- transfers data on both rising/falling edges of the clock signal
Tags: OBJ3.2, Double_Data_Rate_DDR, DDR, PC133, RAM_Types
<!--ID: 1731607895854-->
END

START
Basic
Double Data Rate Synchronous (DDRS)
Back:
- has an internal error checking for its modules
	- DDRS modules can still be sold as ECC or non-ECC modules 
Tags: OBJ3.2, DDR_Synchronous, DDRS, RAM_Type
<!--ID: 1731607895856-->
END

START
Basic
Double Data Rate Synchronous Dynamic RAM (DDR SDRAM)
Back:
- Doubles the transfer speed of an SRAM module (184-pin connector)
- improves performance by processing data on both edges of each clock cycle 
Tags: OBJ3.2, DDRS_Dynamic_RAM, DDR_SDRAM, RAM_Types 
<!--ID: 1731607895858-->
END

START
Basic
DDR 2 Synchronous Dynamic RAM (DDR2 SDRAM)
Back:
- Higher latency and has faster access to the external bust (240-pin connector)
	- PC2-4200
		- 4200 MB/s or 4.2 GB/s
Tags: OBJ3.2, DDR2_SDRAM, PC2-4200, RAM_Types
<!--ID: 1731607895861-->
END

START
Basic
DDR 3 Synchronous Dynamic RAM (DDR3 SDRAM)
Back:
- Runs at lower voltage and higher speed than DDR2 (240 keyed pin connector)
	- PC3-10600
		- 10600 MB/s or 10.6 GB/s
- DDR3 throughput is 6.4 to 17 GB/s with maximum module size of 8GB per memory module 
Tags: OBJ3.2, DDR3_SDRAM, PC3-10600, RAM_Types 
<!--ID: 1731607895863-->
END

START
Basic
DDR 4 Synchronous Dynamic RAM (DDR4 SDRAM)
Back:
- widely used in desktops, laptops, and servers 
- operates at 2133-3200 MHz, 
- low voltage (1.2V) 
- standard DIMM has 288 pins, SODIMM has 260 pins 
- suited for multitasking and high-performance applications 
Tags: OBJ3.2, DDR4_SDRAM, DIMM, SODIMM
<!--ID: 1731607895865-->
END

START
Basic
DDR 5 Synchronous Dynamic RAM (DDR5 SDRAM)
Back:
- operates at speeds of 3200-6400 MHz with lower power consumption than DDR4
- lower voltage (1.1V)
- standard DIMM has 288 pins (configured diff from DDR4) SODIMM has 262 pins 
- ideal for data-intensive tasks, gaming, future-proofing against demanding applications 
Tags: OBJ3.2, DDR5_SDRAM, DIMM, SODIMM
<!--ID: 1731607895867-->
END

START
Basic
Error Correcting Code (ECC)
Back:
- Detects and corrects an error
Tags: OBJ3.2, Error_Correcting_Code_ECC, ECC, RAM_Types
<!--ID: 1731607895869-->
END

START
Basic
Buffered / Registered Memory
Back:
- Additional hardware (register) between memory and CPU
	- the system requires buffering or registering the data to reduce the electrical load
Tags: OBJ3.2, RAM_Types, Registered_Memory
<!--ID: 1731607895871-->
END

START
Basic
Motherboard
Back:
supports ECC modules
Tags: OBJ3.2, Motherboard, ECC, RAM_Types
<!--ID: 1731607895873-->
END

START
Basic
Parity Memory
Back:
- Performs basic error checking and ensures the memory contents are reliable
	- parity check does basic calculation
		- every bit has an associated parity bit 
			- Bits can only be a zero or one 
Tags: OBJ3.2, RAM_Types, Parity_Memory
<!--ID: 1731607895875-->
END

START
Basic
Non-Parity Memory
Back:
- Standard memory that doesn't check for errors and allows data to be put in or taken out 
Tags: OBJ3.2, Non-Parity_Memory, RAM_Types
<!--ID: 1731607895877-->
END

START
Basic
Single Channel
Back:
- 64-bit data bus
- Uses one memory module on one bus (64-bit data bus)
- 64-bit channel for data transfer between CPU and RAM 
- lower bandwidth and speed, used in basic systems w/ only 1 RAM stick 
Tags: OBJ3.2, Single_Channel, 64-bit
<!--ID: 1731607895880-->
END

START
Basic
Dual Channel 
Back:
- 128-bit data bus
	- Interleaving
		- Provides increase performance
- Requires 2 memory modules and 2 memory slots on the motherboard (128-bit data bus)
- 2 64-bit channels, doubling data throughput 
- better performance than single-channel
- requires 2 matching RAM sticks, ideally installed in paired slots specified by motherboard 
Tags: OBJ3.2, Dual_Channel, 128-bit
<!--ID: 1731607895882-->
END

START
Basic
Triple Channel
Back:
- Uses 3 memory modules and 3 memory slots (192-bit data bus)
- increases data transfer rate 
- less common than dual or quad-channel configurations 
- primarily supported by specific intel platforms 
Tags: OBJ3.2, Triple_Channel, 192-bit
<!--ID: 1731607895884-->
END

START
Basic
Quad Channel
Back:
- Uses 4 memory modules and 4 memory slots (256-bit data bus)
- optimal for high-end computing like workstations and gaming rigs that require substantial memory bandwidth 
- generally seen in high-performance motherboards and servers 
Tags: OBJ3.2, Quad_Channel, 256-bit
<!--ID: 1731607895886-->
END

START
Basic
Addressing Memory
Back:
- Processor reaching the files inside RAM 
	- single channel memory controller
		- 32 or 64 bits
	- x86
		- 32-bit
	- x64
		- 64-bit
			- x86 or 32-bit processor can address a maximum of 4 GB of RAM 
			- x64 or 64-bit processor can access more than 4 GB of RAM (8, 16, 32, or 64 GB)
Tags: OBJ3.2, Addressing_Memory, x86, x64
<!--ID: 1731607895889-->
END

START
Basic
Multi-Channel Memory
Back:
Uses 2 different memory modules to increase performance and throughput
- In multi-channel configurations, use same model, speed, and throughput of memory
Tags: OBJ3.2, Multi-Channel_Memory
<!--ID: 1731607895891-->
END

START
Basic
Installing Memory
Back:
	easier to install first with processor
	USE ESD MAT AND STRAP
	check motherboard manual if it supports single, dual, triple, or quad channel
	1. get the memory stick
	2. open memory socket
	3. align notch with motherboard 
	4. seat the memory stick and close memory socket 
Tags: OBJ3.2, Installing_Memory
<!--ID: 1731607895894-->
END