TARGET DECK: A+ Core 1::5.2 Troubleshoot Problems Related to Motherboards RAM CPU Power

START
Basic
Power Issues
Back:
Power button isn't connected properly to the motherboard 
Tags: OBJ5.2, Power_Issues
<!--ID: 1732046658485-->
END

START
Basic
Faulty Wall Outlet
Back:
- use a multimeter or voltmeter to test the power outlet:
	- 110-120V/60Hz US or Canada
	- 220-240V/50Hz Europe or Asia
Tags: OBJ5.2, Power_Issues, Faulty_Wall_Outlet 
<!--ID: 1732046658491-->
END

START
Basic
Faulty Power Cable
Back:
- positive pin
- negative pin
- grounding pin
Tags: OBJ5.2, Power_Issues, Faulty_Power_Cable
<!--ID: 1732046658497-->
END

START
Basic
Faulty PSU
Back:
- 12V DC
- 5V DC
- 3.3V DC
- a power supply tester has a small variation or tolerance:
	- bottom - largest connector
	- Top - 4, 6, 8 pin connectors/SATA/Molex
check if incorrect voltage setting on power supply unit
Tags: OBJ5.2, Power_Issues, 12V_DC, 5V_DC, 3.3V_DC
<!--ID: 1732046658502-->
END

START
Basic
Faulty PSU Power Cables
Back:
- when testing detachable cables, check each pin on each side of the cable to verify full continuity 
Tags: OBJ5.2, Power_Issues, Faulty_PSU_Pwr_Cables
<!--ID: 1732046658507-->
END

START
Basic
Power-On Self-Test (POST)
Back:
- Diagnostic program inside the system firmware
![[POST.png]]
	- POST beep codes are specific to motherboard's manufacturer 
	- POST-test expansion card ids which component on the motherboard is faulty and needs to be replaced
Tags: OBJ5.2, POST_Issues, Power_On_Self_Test_POST, POST
<!--ID: 1732046658513-->
END

START
Basic
Crash Screen 
Back:
- displays an error whenever the operating system has issue 
Tags: OBJ5.2, Crash_Screen
<!--ID: 1732046658517-->
END

START
Basic
Blue Screen of Death (BSOD)
Back:
- indicates there's a problem with the underlying hardware that Windows cannot solve
	- CRITICAL_PROCESS_DIED
		- SYSTEM_THREAD_EXCEPTION_NOT_HANDLED
	- IRQL_NOT_LESS_OR_EQUAL
		- VIDEO_TDR_TIMEOUT_DETECTED
	
	- PAGE_FAULT_IN_NONPAGED_AREA
		- SYSTEM_SERVICE_EXCEPTION 
		- DPC_WATCHDOG_VIOLATION
Tags: OBJ5.2, Blue_Screen_of_Death_BSOD, BSOD, Windows, Crash_Screen
<!--ID: 1732046658522-->
END

START
Basic
Pinwheel of Death (PoD)
Back:
- macOS (OS X)
Tags: OBJ5.2, Crash_Screen, MAC, Pinwheel_of_Death_PoD, PoD
<!--ID: 1732046658527-->
END

START
Basic
Kernel Panic
Back:
- the system display gives an exit code
Tags: OBJ5.2, Linux, Kernel_Panic
<!--ID: 1732046658532-->
END

START
Basic
Cooling Issues
Back:
**make sure all cooling components are working**:
1. shut down the system 
2. boot into UEFI or BIOS

In UEFI or BIOS, look at the temperature sensors inside of the system 

A thermal issue causes intermittent shutdowns or continual rebooting 
Tags: OBJ5.2, Cooling_Issues, UEFI, BIOS
<!--ID: 1732046658536-->
END

START
Basic
Physical Component Damage
Back:
Excessive exposure to the thermal loads can cause permanent damage 

Plugging or unplugging cables can cause wearing out, and pins getting bent or damaged 

The rancid smell comes from a blown or burst capacitor

When a capacitor starts emitting internal chemicals, it loses the ability to regulate electricity
Tags: OBJ5.2, Physical_Component_Damage
<!--ID: 1732046658541-->
END

START
Basic
Performance Issues
Back:
![[PerfIssues.png]]

Modern systems can protect against overheating

Overheating systems could reboot or shutdown 

Increasing the page size in Windows or the swap space in Linux 
Tags: OBJ5.2, Performance_Issues
<!--ID: 1732046658546-->
END

START
Basic
Inaccurate System Date/Time 
Back:
Motherboards have a battery to keep the real-time clock (RTC) in sync 

Most modern OS set the date and time automatically
Tags: OBJ5.2, Inaccurate_System_Date_Time, Real-time_Clock_RTC, RTC
<!--ID: 1732046658550-->
END

START
Basic
Complementary Metal-Oxide-Semiconductor (CMOS)
Back:
- non-volatile type of memory that stores the BIOS settings and is built into the motherboard  
Tags: OBJ5.2, Complementary_Metal_Oxide_Semiconductor_CMOS, CMOS, BIOS
<!--ID: 1732046658555-->
END

START
Basic
Non-Volatile RAM (NVRAM)
Back:
- stores data without being constantly refreshed 
	- CMOS 
	- Real-time clock 
Tags: OBJ5.2, Non-Volatile_RAM_NVRAM, NVRAM, CMOS, RTC
<!--ID: 1732046658559-->
END

START
Basic
Smoke Test
Back:
ensuring everything connected and working properly booting to BIOS and OS
1. plug PSU into surge protected outlet, turn on
2. everything works/spinning and no smoke? good job
Tags: OBJ5.2, Smoke_Test, BIOS
<!--ID: 1732046658564-->
END

START
Basic
POST Beeps
Back:
- diagnostic sounds indicating hardware status during system startup
different beep sequences signify various hardware problems like
	RAM 
	CPU 
	Motherboard Errors 
		refer to motherboard manual for exact meaning of each beep code: different each manufacturer
Tags: OBJ5.2, Common_Symptoms, POST_Beeps
<!--ID: 1732046658568-->
END

START
Basic
Black Screen Potential Causes
Back:
- **loose connections**: check display cables and connectors on both monitor and PC
- **Graphics card failure**: ensure the GPU is seated correctly or try reseating it 
- **Motherboard/BIOS issues**: if the system doesn't boot to BIOS, the motherboard or CPU could be malfunctioning 
- test system with different monitor or cable to isolate display issues 
- check for POST beeps or error codes 
Tags: OBJ5.2, Black_Screen_Causes, Loose_Connections, Graphics_Card_Failure, Motherboard_BIOS_Issues, Common_Symptoms
<!--ID: 1732046658574-->
END

START
Basic
No Power Causes
Back:
- **faulty power supply**: PSU may have failed or lack sufficient power 
- **defective power button or cable**: ensure the power button connects correctly to the motherboard 
- confirm power outlet is working: test with another power supply and verify PSU connections to the motherboard 
Tags: OBJ5.2, No_Power_Causes, Faulty_PSU, Common_Symptoms
<!--ID: 1732046658580-->
END

START
Basic
Sluggish Performance Causes
Back:
- **overloaded CPU or RAM**: high CPU or memory usage can lead to performance lag 
- **insufficient cooling**: high temperatures can throttle CPU performance 
- **failing hard drive**: disk errors or fragmentation can slow system response 
- check resource usage in TASK MANAGER 
- increase RAM if usage is consistently high 
- ensure proper cooling 
Tags: OBJ5.2, Sluggish_Performance_Causes, Overloaded_CPU, Overloaded_RAM, Insufficient_Cooling, Failing_Hard_Drive, Common_Symptoms
<!--ID: 1732046658585-->
END

START
Basic
Overheating
Back:
- **dust buildup**: dust can obstruct fans and heat sinks, reducing cooling efficiency 
- **faulty fans**: check if all fans are operational 
- **poor ventilation**: ensure adequate airflow within the case 
- clean the system to remove dust, check thermal paste on the CPU, verify fan operation 
Tags: OBJ5.2, Overheating, Dust_Buildup, Faulty_Fans, Poor_Ventilation, Common_Symptoms
<!--ID: 1732046658590-->
END

START
Basic
Burning Smell
Back:
- **electrical short**: could be caused by exposed wiring or damaged components 
- **overheating components**: failed components may emit burning smells 
- power off immediately and inspect for damaged capacitors or burnt cables 
- replace any damaged components before restarting 
Tags: OBJ5.2, Common_Symptoms, Electrical_Short, Overheating_Components, Burning_Smell
<!--ID: 1732046658595-->
END

START
Basic
Intermittent Shutdown
Back:
- **power supply issues**: an inadequate or failing PSU may cause random shutdowns 
- **overheating**: high temperatures can trigger auto-shutdown to prevent damage 
- **loose components**: loose motherboard or CPU can interrupt power 
- test with another PSU
- inspect cooling solutions
- ensure all components are securely connected 
Tags: OBJ5.2, Intermittent_Shutdown, PSU_Issues, Overheating, Loose_Components, Common_Symptoms
<!--ID: 1732046658600-->
END

START
Basic
Application Crashes
Back:
- **insufficient memory**: not enough RAM can cause applications to crash 
- **driver issues**: outdated or incompatible drivers can lead to instability 
- **corrupted files**: damaged files or malware can cause applications to malfunction 
- update drivers, run diagnostics, ensure sufficient RAM 
- consider reinstalling the application or running a virus scan 
Tags: OBJ5.2, Application_Crashes, Insufficient_Memory, Driver_Issues, Corrupted_Files, Common_Symptoms
<!--ID: 1732046658605-->
END

START
Basic
Grinding Noise
Back:
- **mechanical drives**: HDDs may produce grinding sounds when failing 
- **fans**: worn-out fans or debris can also cause grinding noises 
- identify the noise source 
- replace/clean noisy fans
- back up data immediately if the hard drive is failing 
Tags: OBJ5.2, Common_Symptoms, Grinding_Noise, Mechanical_Drives, Fans
<!--ID: 1732046658609-->
END

START
Basic
Capacitor Swelling
Back:
- **aging or failing capacitors**: swollen or leaking capacitors indicate component failure on the motherboard or PSU
- replace the affected component
	- motherboards: consult a professional if capacitors need repair
Tags: OBJ5.2, Common_Symptoms, Capacitor_Swelling, Aging_Failing_Capacitors
<!--ID: 1732046658614-->
END

START
Basic
Inaccurate System Date Time
Back:
- **failed CMOS battery**: the CMOS battery powers the BIOS/UEFI and retains system time when the computer is off 
- replace the CMOS battery on the motherboard to maintain accurate time and BIOS settings 
Tags: OBJ5.2, Common_Symptoms, Inaccurate_System_Date_Time, Failed_CMOS, CMOS
<!--ID: 1732046720675-->
END