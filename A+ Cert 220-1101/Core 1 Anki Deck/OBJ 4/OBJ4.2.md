TARGET DECK: A+ Core 1::4.2 Summarize Aspects of Client Side Virtualization

START
Basic
Virtualization
Back:
- Host computer installed with a hypervisor that can be used to install and manage multiple guest operating systems or virtual machines (VMs)
	- Type1 Hypervisor (Bare Metal)
		- runs directly on the host hardware and functions as the OS
	- Type2 Hypervisor 
		- runs within the normal OS
- Ensure that each VM runs its own copy of an OS
Tags: OBJ4.2, Virtualization, Hypervisor, VMs, Type1_Hypervisor, Type2_Hypervisor
<!--ID: 1732042064342-->
END

START
Basic
Server-based (Terminal Services)
Back:
- Server-based solution that runs the application on servers in a centralized location
Tags: OBJ4.2, Server_Based, Terminal_Services
<!--ID: 1732042064347-->
END

START
Basic
Client-based (Application Streaming)
Back:
- client-based solution that allows an application to be packaged up and streamed directly to a user's PC
Tags: OBJ4.2, Client_Based, Application_Streaming
<!--ID: 1732042064352-->
END

START
Basic
Hypervisor 
Back:
- manages distribution of physical resources of a server to the VMs
	- Type 1
		- bare metal 
	- Type 2
		- Hosted 
Tags: OBJ4.2, Hypervisor, VM_Purpose, Type1_Hypervisor, Type2_Hypervisor
<!--ID: 1732042064358-->
END

START
Basic
Container-Based Virtualization (Containerization)
Back:
- each container relies on a common host OS as base for each container 
- Container-based virtualization has less resources because it doesn't require its own copy of the OS for individual container 
Tags: OBJ4.2, Container-Based_Virtualization, Containerization, VM_Purpose
<!--ID: 1732042064363-->
END

START
Basic
Hyperconverged Infrastructure
Back:
- allows for the full integration of the storage, network, and servers w/o hardware changes
Tags: OBJ4.2, Hyperconverged_Infrastructure, VM_Purpose
<!--ID: 1732042064368-->
END

START
Basic
Application Virtualization
Back:
- Encapsulates computer programs from the underlying OS on which they're executed 
Tags: OBJ4.2, Application_Virtualization, VM_Purpose
<!--ID: 1732042064372-->
END

START
Basic
Virtual Desktop Infrastructure (VDI)
Back:
- hosts desktop OSs within a virtualized environment hosted by a centralized server or server farm
Tags: OBJ4.2, VM_Purpose, Virtual_Desktop_Infrastructure_VDI, VDI
<!--ID: 1732042064378-->
END

START
Basic
Sandbox
Back:
- isolated environment for analyzing pieces of malware
- Separates running processes and programs to mitigate system failures or software vulnerabilities 
- used for testing software, conducting security analyses, running untrusted applications 
- Sandbox VM prevents malware/rogue programs from harming host OS
Tags: OBJ4.2, Sandbox, VM
<!--ID: 1732042064384-->
END

START
Basic
Sandbox Escape
Back:
- occurs when an attacker circumvents sandbox protections to gain access to the protected OS or other privileged processes 
	- patched
	- up to date 
	- strong endpoint software protection 
	- limited extensions or add-ons
Tags: OBJ4.2, Sandbox, Sandbox_Escape
<!--ID: 1732042064389-->
END

START
Basic
Test Development
Back:
- provides a controlled environment to develop, test, troubleshoot software/hardware w/o interfering w/ live systems 
- ideal for developers who need to simulate different operating environments (testing Windows app on both 10 & 11 VMs)
Tags: OBJ4.2, Test_Development
<!--ID: 1732042064394-->
END

START
Basic
Application Virtualization
Back:
- runs a single application in a VM, allows it to operate independently of host OS or other installed apps 
- useful for compatibility when running apps on OS versions or configs not originally designed for 
- minimizes potential software conflicts 
Tags: OBJ4.2, Application_Virtualization, VM
END

START
Basic
Legacy Software | OS Compatibility
Back:
- runs older software or legacy OS versions that may not be supported by newer hardware or OSs
- useful in business environments where old apps are critical but cannot be directly ran on modern systems (ex running Windows XP on a VM to support legacy software)
Tags: OBJ4.2, Application_Virtualization, Legacy_Software, OS_Compatibility
<!--ID: 1732042064402-->
END

START
Basic
Cross-platform Virtualization
Back:
- runs OSs or applications from different platforms on the same hardware (running Linux on a Windows host)
- beneficial for devs, testers, IT professionals who need to switch between multiple OSs w/o rebooting or setting up multiple computers 
- allows for testing/running of software applications for different OSs
	- Emulation
		- System imitation
	- Virtualization 
		- new "physical" machine 
Tags: OBJ4.2, Application_Virtualization, Cross-platform_Virtualization
<!--ID: 1732042064408-->
END

START
Basic
Second Level Address Translation (SLAT)
Back:
- improves the performance of virtual memory when running multiple virtual machines on a single physical host 
Tags: OBJ4.2, Resource_Requirements, Second_Level_Address_Translation_SLAT, SLAT
<!--ID: 1732042064414-->
END

START
Basic
Intel Extended Page Table (EPT)
Back:
- Extended Page Table (EPT)
Tags: OBJ4.2, Resource_Requirements, SLAT, Intel, Extended_Page_Table_EPT, EPT
<!--ID: 1732042064418-->
END

START
Basic
AMD Rapid Virtualization Indexing (RVI)
Back:
- Rapid Virtualization Indexing (RVI)
Tags: OBJ4.2, Resource_Requirements, SLAT, AMD, Rapid_Virtualization_Indexing_RVI, RVI
<!--ID: 1732042064424-->
END

START
Basic
x86
Back:
- 32-bit processor 
	- 32-bit OS can only access 4GB of RAM
Tags: OBJ4.2, Resource_Requirements, x86, 32-bit
<!--ID: 1732042064430-->
END

START
Basic
x64
Back:
- 16 exabytes of RAM
	- 32-bit processor can't run a 64-bit application 
Tags: OBJ4.2, Resource_Requirements, x64, 16_Exabytes, 32-bit
<!--ID: 1732042064436-->
END

START
Basic
ARM
Back:
- reduced instruction set and computer architecture in a computer processor 
Tags: OBJ4.2, Resource_Requirements, ARM
<!--ID: 1732042064442-->
END

START
Basic
System Memory
Back:
- amount of physical memory installed on a physical server 
- barebones windows installation takes 20-40 GB of space
- Linux takes 4-8 GB of space 
- Mac takes 20-40 GB of space 
Tags: OBJ4.2, Resource_Requirements, System_Memory, Windows, Linux, Mac
<!--ID: 1732042064446-->
END

START
Basic
NIC Teaming Configuration
Back:
- allows multiple cards for higher speeds
- CPU, processor,  and capabilities
- System memory 
- Networking 
- Storage 
Tags: OBJ4.2, Resource_Requirements, Security_Requirements, NIC_Teaming_Configuration
<!--ID: 1732042064451-->
END

START
Basic
VM Escape
Back:
- threat attempts to get out of isolated VM and send commands to the underlying hypervisor
- VM escape is easier to perform on Type2 hypervisor than Type1 hypervisor
	- Patched 
	- up to date
Tags: OBJ4.2, Security_Requirements, VM_Escape, VM, Type1_Hypervisor 
<!--ID: 1732042064458-->
END

START
Basic
VM Hopping
Back:
- threat attempts to move from one VM to another on same host 
	- VM hopping:
		- VM to VM
	- VM escape 
		- VM to hypervisor or host OS
			- up to date
			- patched 
			- securely configured
Tags: OBJ4.2, Security_Requirements, VM_Hopping, VM, VM_Escape
<!--ID: 1732042064463-->
END

START
Basic
Isolation
Back:
- each VM should be isolated from the host and other VMs to prevent spread of malware/unauthorized access 
- use hypervisor settings/permissions to limit access, ensuring VMs can't interfere with eachother or host system 
Tags: OBJ4.2, Security_Requirements, Isolation, VM, Hypervisor
<!--ID: 1732042064468-->
END

START
Basic
Live Migration
Back:
- Migrates the VM from one host to another while it's running 
- Ensure that live migration only occurs on trusted networks or utilizes encryption
Tags: OBJ4.2, Security_Requirements, Live_Migration, VM
<!--ID: 1732042064473-->
END

START
Basic
Data Remnants
Back:
- leftover pieces of data that my exist in the hard drive which are no longer needed 
	- encrypt VM storage location
	- destroy encryption key
Tags: OBJ4.2, Security_Requirements, Data_Remnants, VM
<!--ID: 1732042064478-->
END

START
Basic
VM Sprawl
Back:
- uncontrolled deployment of VMs
Tags: OBJ4.2, Security_Requirements, VM_Sprawl, VM
<!--ID: 1732042064483-->
END

START
Basic
Access Control and Permissions
Back:
- restricting access ensures only authorized users can launch, configure, modify VMs
- use secure authentication methods and restrict VM management functions to specific users/groups
Tags: OBJ4.2, Security_Requirements, Access_Control_Permissions, VM
<!--ID: 1732042064488-->
END

START
Basic
Data Protection
Back:
- regularly back up VMs, use encryption for stored VM data, enable VM snapshotting to save current state w/o losing data if issues occur 
Tags: OBJ4.2, Security_Requirements, Data_Protection, VM
<!--ID: 1732042064493-->
END

START
Basic
Network Security
Back:
- use firewalls, apply patches, monitor network activity 
- configure VMs with private IPs when possible 
- separate VM network traffic from the main network network to limit exposure
Tags: OBJ4.2, Security_Requirements, Network_Security, VM
<!--ID: 1732042064497-->
END

START
Basic
Creating Safe Environment Using VirtualBox
Back:
	1. visit www.virtualbox.org and download for appropriate host software 
	2. open file for installation
	3. make sure Command Line Utilities are being installed 
	4. open virtual box
	5. download ubuntu
	6. figure out how to install onto virtual machine
	7. yay use as project

	Using Encryption & Disabling Sharing Between Host/VM to Better Secure VMS from Outside Environment 
	use as ex project 
Tags: OBJ4.2, Security_Requirements, Safe_Env_VirtualBox
<!--ID: 1732042064503-->
END

START
Basic
VM VirtualBox Settings
Back:
with virtualbox and OS installed onto a created VM
	1. open settings for VM
		1. disk encryption
		2. enable
		3. chose AES-XTS256-PLAIN64 encryption cypher 
		4. create long/strong password and keep it
	2. open settings again>shared folders
		1. add directories from host machine to be used on VM
		2. add as auto-mount
	3. boot VM and enter encryption password 
	4. open file explorer>network> see VBOX server there? cool
		1. open it to see all the hosts shared files/directories 
		2. DANGEROUS FOR HOST MACHINES
			1. open VM settings on host 
			2. delete shared connections between VM and host 
			3. KEEP THE VM ISOLATED FROM HOST (added security with VMs)
Tags: OBJ4.2, Security_Requirements, VirtualBox_VM_Settings
<!--ID: 1732042064508-->
END
