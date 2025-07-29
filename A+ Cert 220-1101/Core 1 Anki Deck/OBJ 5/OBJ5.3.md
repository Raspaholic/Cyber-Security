TARGET DECK: A+ Core 1::5.3 Troubleshoot Diagnose Problems with Storage Drives RAID Arrays

START
Basic
Boot Issues 
Back:
SSD/Hard drive 
Removable media 
Network
Tags: OBJ5.3, Boot_Issues, SSD, Hard_Drive, Removable_Media, Network
<!--ID: 1732049305730-->
END

START
Basic
Master Boot Record (MBR)
Back:
- legacy method of providing the boot information
- partition on a storage device is the logical part of an entire drive 
	- Windows: single partition 
	- Linux: multiple partitions 
	- Boot Configuration Data (BCD): Windows 
	- GRUB/LILO: Linux 
Tags: OBJ5.3, Master_Boot_Record_MBR, MBR, Boot_Configuration_Data_BCD, BCD
<!--ID: 1732049305736-->
END

START
Basic
GUID Partition Table (GPT)
Back:
- specialized boot scheme with modern advantages 
- inability to find a bootable device indicates a problem with MBR or GPT
	- bootable device not found 
	- OS not found 
	- Invalid drive specification 
- The UEFI and BIOS set prioritized boot order based on their configurations 
- check if internal storage device is working properly 
Tags: OBJ5.3, GUID_Partition_Table_GPT, GPT, MBR, UEFI, BIOS
<!--ID: 1732049305741-->
END

START
Basic
Hard Disk Drive (HDD)
Back:
- older storage devices that spin and move the read/write head across the platter
- Low-cost, slower speed 
Tags: OBJ5.3, Hard_Disk_Drive_HDD, HDD, Storage_Device_Issues
<!--ID: 1732049305746-->
END

START
Basic
Solid-state Device
Back:
- non-volatile memory that stores data and can access data from the device 
- high cost, less storage, faster speed 
- Solid-state devices have a limit on the amount of time to read and write data 

Clicking sounds or grinding noises are signs of a hard disk drive mechanical problem
Tags: OBJ5.3. Solid-state_Device, Storage_Device_Issues
<!--ID: 1732049305751-->
END

START
Basic
Light not blinking during Read/Write from Device
Back:
- LED activity is constantly blinking 

Adding physical memory will stop the disk from being used as a swap file or page file 
Use disk management tools to see if the device is detected
Tags: OBJ5.3, Light_Read_Write
<!--ID: 1732049305756-->
END

START
Basic
Sector 
Back:
- Allows to read/write on the hard drive by identifying the sector 
- use disk utility to identify which sectors are bad and try to recover them 
	- Sectors: Windows/Linux 
	- Blocks: Solid-state device 

It's always best practice to have a good backup drive 
Tags: OBJ5.3, Sector, Disk_Utility
<!--ID: 1732049305761-->
END

START
Basic
Self-Monitoring Analysis Reporting Technology (SMART)
Back:
- self-diagnostic program that alerts the OS if there's failure 
Tags: OBJ5.3, Self-Monitoring_Analysis_Reporting_Technology_SMART, SMART
<!--ID: 1732049305766-->
END

START
Basic
SMART monitors Hard Drive Health Status
Back:
SMART monitors the hard drive and understands the health status of the drive 
	- Read Error Rate 
	- Spin-Up Time
	- Reallocated Sector Count 
	- Seek Error Rate 
	- Power-On Hours 
	- Temperature
Tags: OBJ5.3, SMART_Hard_Drive_Health_Status, SMART
<!--ID: 1732049305770-->
END

START
Basic
SMART Utility Monitoring Input/Output Operations Per Second (IOPS)
Back:
SMART utility is monitoring input/output operations per second (IOPS)
	- hard disk drive has a lower IOPS than a solid-state device 
	- cloud can measure performance by using IOPS
	- Low IOPS can be an issue with the hardware or the software
Tags: OBJ5.3, SMART_Utility_IOPS, Input_Output_Operations_Per_Second_IOPS, IOPS
<!--ID: 1732049305776-->
END

START
Basic
SMART Defragmentation Tool
Back:
The defragmentation tool can put files back together and reduce read/write times 
	- deleting and rewriting causes fragmentation 
Tags: OBJ5.3, SMART_Defragmentation_Tool, SMART
<!--ID: 1732049305781-->
END

START
Basic
Issues with RAIDs
Back:
RAID protects data against the risk of data loss 
Tags: OBJ5.3, Issues_with_RAIDs
<!--ID: 1732049305786-->
END

START
Basic
Single Disk Failure
Back:
- if a RAID loses a disk, it will continue to operate as normal but at a slower speed 
- RAID rebuild is the utility used to rebuild the RAID
Tags: OBJ5.3, Single_Disk_Failure, RAID
<!--ID: 1732049305792-->
END

START
Basic
Full Raid Failure
Back:
- entire array or volume stops working 
- when the RAID fails, restore from backup, reconfigure, and rebuild using new disks
Tags: OBJ5.3, Full_Raid_Failure, RAID
<!--ID: 1732049305798-->
END

START
Basic
Light-emitting diode (LED) Status Indicators
Back:
- different colors / blink patterns indicate statuses like normal operation, drive failure, rebuild in progress, inactive drive 
- refer to drives documentation for specific LED codes 
Tags: OBJ5.3, Light-emitting_Diode_LED, LED, LED_Status_Indicators, Common_Symptoms
<!--ID: 1732049305803-->
END

START
Basic
Grinding Noises
Back:
- often indicates physical damage in mechanical hard drives, usually worn bearings or failing components 
- backup data immediately
- replace drive if possible
Tags: OBJ5.3, Common_Symptoms, Grinding_Noises
<!--ID: 1732049305810-->
END

START
Basic
Clicking Sounds 
Back:
- HHDs "click of death": indicates head or motor failure in HDDs 
- stop using the drive, attempt data recovery if necessary and replace drive 
- clicking usually indicator of irreparable hardware damage 
Tags: OBJ5.3, Common_Symptoms, Clicking_Sounds
<!--ID: 1732049305816-->
END

START
Basic
Bootable Device Not Found
Back:
- drive not recognized: 
	can occur if the boot drive has failed, isn't properly connected, or misconfigured in the BIOS/UEFI
- corrupted boot partition:
	boot sector or partition may be corrupted 
- check BIOS settings to ensure the correct drive is selected as the boot device 
- reconnect the cables and attempt startup repair to fix boot partition issues
Tags: OBJ5.3, Common_Symptoms, Bootable_Device_Not_Found
<!--ID: 1732049305821-->
END

START
Basic
Data Loss Corruption
Back:
- drive degradation:
	aging/damaged drives often develop bad sectors that corrupt data 
- power issues or improper shutdowns: these can lead to file corruption 
- regularly backup data
- run file system checks 
- replace aging drives as a preventative measure 
- data recovery software may restore lost files 
Tags: OBJ5.3, Common_Symptoms, Data_Loss_Corruption
<!--ID: 1732049305826-->
END

START
Basic
RAID Failure
Back:
- RAID 0 cannot tolerate any drive failure
- RAID 1, 5, 6 can handle one or more drive failures depending on the configuration 
- RAID controller problems can also lead to failures 
- replace failed drives as needed and use the RAID management software to rebuild the array 
- ensure you use compatible drives for replacement to avoid further complications 
Tags: OBJ5.3, Common_Symptoms, RAID_Failure, RAID_Controller, RAID_0, RAID_1_5_6
<!--ID: 1732049305831-->
END

START
Basic
Self-Monitoring Analysis Reporting Technology (SMART) Failure
Back:
- monitors drive health and predicts failures by tracking error rates, reallocated sectors, other factors 
- when it indicates a potential failure, backup data immediately and replace the drive, this is an early warning of hardware issues 
Tags: OBJ5.3, Self-Monitoring_Analysis_Reporting_Technology_SMART, SMART, SMART_Failure, Common_Symptoms
<!--ID: 1732049305836-->
END

START
Basic
Extended Read / Write Times 
Back:
- drive degradation: bad sectors or general wear can slow down read/write performance 
- fragmentation or large file sizes: high fragmentation or large files may slow access times on mechanical drives 
- run diagnostics to identify failing sectors, defragment the drive (if HDD)
- consider upgrading to SSDs for faster access 
Tags: OBJ5.3, Extended_Read_Write_Times, Drive_Degradation, Fragmentation, Common_Symptoms
<!--ID: 1732049305841-->
END

START
Basic
Input / Output Operations Per Second (IOPS)
Back:
- IOPS measures the performance of a drive or RAID array based on its ability to handle read/write requests per second 
- low IOPS can indicate issues with drive performance or saturation of the RAID controller's capabilities 
	- more applicable to SSDs and enterprise RAID systems 
- to improve IOPS, use faster drives, upgrade RAID controllers, consider SSDs for higher IOPS requirements
Tags: OBJ5.3, Input_Output_Operations_Per_Second_IOPS, IOPS, RAID_Array, Common_Symptoms
<!--ID: 1732049305848-->
END

START
Basic
Missing Drives in OS
Back:
- connection issues: drives may be improperly connected or have loose cables 
- driver issues: missing or outdated drivers can prevent the OS from recognizing the drive 
- BIOS settings: if not enabled in BIOS, OS may not detect the drive 
- ensure all cables are securely connected 
- update/reinstall drivers 
- check BIOS settings to ensure all drives are enabled 
Tags: OBJ5.3, Missing_Drives_in_OS, BIOS, Common_Symptoms
<!--ID: 1732049305853-->
END