# Building a PC (Virtual)

## Objective: 
To demonstrate proficiency in hardware assembly, system configuration, and troubleshooting by simulating the fabrication of a PC, including OS installation and basic system setup.

A+ CORE 1 Objectives:
- 3.1: Explain basic cable types, features, and their purposes 
- 3.2: Identify connectors associated with peripheral devices 
- 3.3: Install and configure storage devices 
- 3.5: Install and configure motherboards, CPUs, and add-on cards 

---
- Showcase hardware assembly and system setup 
document components: list CPU, RAM, motherboard, storage, PSU, etc
document installation in proper order 
install the OS 
Configure: 
	in game: can only install OS and drivers/apps no actual configuration 
	Install Drivers / Basic Applications 
## Tools Used 
Software:
- PC Building Simulator 2
- Rufus/Etcher (Windows/Windows, macOS, Linux)
- VirtualBox (VM)

Documentation Tools: 
- Windows Snipping Tool 
- ShareX
### Steps Taken 
##### 1. Preparation 
- Identified and listed all components
   - CPU, RAM, motherboard, storage, PSU, GPU, case, fans, processor
- Created a bootable USB with a Windows/Linux ISO or OS using Rufus/Etcher
##### 2. Assembly / Simulation 
- Installed components in the following order:
  1. motherboard 
  2. CPU Installation and cooling setup 
  3. RAM seating 
  4. Storage Mounting 
  5. PSU & Cable management
  6. component connections 
##### 3. System Boot and OS Installation 
- Powered on the system entered BIOS/UEFI settings on VM:
  - ensured BIOS current version 
  - Configured boot order 
  - partitioned / formatted drives 
  - Installed necessary drivers (chipset, GPU, audio)
  - Installed OS from bootable USB
  - Added basic applications like browser, text editor, cleaner, etc 
##### 4. Documentation 
- capture images/ss of key steps 
- component list and assembly process 
- BIOS/UEFI and OS installation screens 
- final setup with OS running: both PCBS2 & VM

---
### Outcome
Successfully simulated the fabrication of a functional PC. Demonstrated ability to assemble hardware, troubleshoot issues, and configure a system from scratch.

---
### Screenshots


### Challenges & Solutions 
Challenges:
- Difficulty seating RAM correctly
- Encountered a black screen on initial boot 
- BIOS did not detect the bootable USB 

Solutions: 
- Reseated the RAM and ensured alignment with the slot 
- Checked and reconnected GPU cables to resolve the black screen 
- Reformatted the USB with the correct bootable ISO settings using Rufus 



### **Using Virtual Machines**

1. **Set Up a Virtual Machine:**
    
    - Install a free VM software like **VirtualBox** or **VMware Workstation Player**.
    - Create a new virtual machine and configure it to boot from a USB or ISO.
2. **Simulate the Issue:**
    
    - Misconfigure the VM settings to mimic common problems, such as:
        - Set the boot order so the USB or ISO is not prioritized.
        - Attach a non-bootable USB image or ISO.
        - Use a corrupted ISO file to mimic a boot failure.
3. **Troubleshoot and Solve:**
    
    - Enter the VM’s BIOS/UEFI setup (usually by pressing keys like `F2`, `DEL`, or `ESC` during startup).
    - Adjust the boot order to prioritize the USB or ISO.
    - Verify that the ISO is bootable and correctly formatted for the VM (e.g., UEFI vs. Legacy boot mode).
    - Recreate the bootable USB or use a different ISO.

---

### **Document Hypothetical Troubleshooting Steps**

If you’re relying solely on PC Building Simulator or a real-world scenario:

1. **Describe the Problem:**
    
    - BIOS/UEFI does not recognize the USB in the boot options.
2. **Possible Causes:**
    
    - USB is not bootable.
    - Incorrect boot mode (e.g., Legacy vs. UEFI).
    - Faulty USB port or drive.
    - BIOS settings not configured correctly.
3. **Solutions:**
    
    - **Check Bootable USB:**
        - Recreate the USB using **Rufus** or another tool, ensuring the correct partition scheme (MBR for Legacy, GPT for UEFI).
    - **Verify BIOS Settings:**
        - Enter the BIOS and:
            - Enable USB booting if disabled.
            - Set the boot order to prioritize USB.
            - Match the boot mode (Legacy/UEFI) with the USB’s partition style.
    - **Test USB and Ports:**
        - Try the USB on another computer to verify functionality.
        - Switch to a different USB port (preferably a USB 2.0 port for older systems).

---

### **How to Showcase the Solution**

1. **Screenshots/Photos:**
    
    - Show BIOS settings and changes you made (e.g., boot order or enabling USB booting).
    - Include screenshots of the USB creation process.
2. **Write-Up:**
    
    - Document the issue, how you diagnosed it, and the steps you took to resolve it.
3. **Reflection:**
    
    - Note how this troubleshooting process is crucial for IT roles and real-world scenarios.

This simulation and documentation will effectively showcase your troubleshooting skills, even without direct USB functionality in the simulator.
