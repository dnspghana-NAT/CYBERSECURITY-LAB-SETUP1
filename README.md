# CYBERSECURITY-LAB-SETUP1
## Project Purpose and introduction
Cybersecurity involves the practice of protecting computers, servers, mobile devices, networks, and data from digital attacks, theft, or unauthorized access. Its main goal is to keep private information safe and stop hackers from breaking into electronic systems. Some of the key preliminary stages of Cybersecurity entails mobilization and organization of digital resources necessary for the creation and building of virtual space which provide an isolated and a controlled environment for penetration testing and ethical hacking practice. The secure virtual space is crucial for the following Cybersecurity practices:
1. Foot printing and reconnaissance.
2.  Network and port scanning
3. vulnerability assessment and penetration testing
4. packet analysis
5. 	web testing

## 🎯 Project Objectives
The project objectives are:
1.	Install and configure virtual box 
2.	Download/unzip/import and install Kali Linux as a virtual machine
3.	Create private Nat network for virtual machine connectivity
4.	Configure network connectivity for Kali Linux
5.	Assign a permanent IP address to Kali Linux virtual machine
6.	Verify network connectivity and DNS resolution through ping command
7.	Take a clean Kali Linux virtual machine for recovery

## System Laboratory Architecture/Resources
|System components| Resources and configuration|
|-----------------|----------------------------|
|Host OS          |Windows                     |
|Host Ram         |12 Gigabytes                |
|host processor   |Intel core i3 4th generation|
|Hypervisor       |Virtual box 7.2.14          |
|Security OS      |Kali Linux 2026.2           |
|Kali Linux Ram   |2048         |
|Kali Linux virtual Network| Nat Network|
|Network address|10.0.0.0/24|
|Kali Linux IP address|10.0.0.6|
|Default gateway|10.0.0.1|
|Dynamic Name Server -DNS|8.8.8.8|

## 🛠️ Tools and Resources
1. 7-zip: https://7-zip.org/download.hml
2. VirtualBox: https://virtualbox.org/wiki/download/dowmloads
3. Kali Linux: https://kali.org/get-kali

## 🎢 Methods and Steps
1. 7-zip
2. Oracle VirtualBox
3. Kali Linux
4. Nat Network
5. Kali Linux VM Networking
6. IPV4 Addressing
7. Kali Linux VM Snapshot

## Virtual Laboratory Setup
The Theoretical workflow of virtual Laboratory Setup:
1. Download and Install 7-zip
2. download and install Oracle VirtualBox
3. Configure the VirtualBox Nat Network
4. Download and import Kali Linux
5. configure and enable Kali Linux Nat Network
6. configure Kali Linux Ip settings
7. Take snapshot of the VM

## Practical Workflow of Laboratory Setup
**Step1. Installation of 7-zip**

**What was Done**
7-zip  was downloaded and installed. This was necessary for file management and extraction. The Kali Linux was downloaded in zip format, which needed to be extracted before importation into the VirtualBox.

**Step 2. Oracle VirtualBox Installation**

**What was Done**
The VirtualBox was downloaded from their official website and installed. The VirtualBox provide a Virtual space necessary for Cybersecurity practices. It also creates a platform to run multiple Virtual Machine in addition to Kali Linux.

**Below was an Image of the VrtualBox Installation**

![ Image of VirtualBox Installation phase](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/f33377384b6f6eeceb193fc9fcfe41ed0ad7ae6d/Virtual%20Box%20Installation%20phase.PNG) 
![ImageofVirtualBoxInstallation](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/1b7457d3b27b1a3c40a3549709947c2e8d42c74f/Virtual%20Box%20Installation%20phase1.PNG)

**Step 3. Nat Network Configuration**

**what was Done**
Nat Network of Ipv4 of 10.0.0.0/24 was configured and DHCP also enabled on the VirtualBox. This helps create a controlled space for multiple Virtual Machine communicate with each other as well as the external Cyberspace.

**The Result of the configuration is Shown Below**

![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/301de8426cb266ee285b8c8b6fa26fc121f964e4/Virtual%20Box%20Nat%20Network%20Set%20Up.PNG)

**Step 4. Kali Linux Virtual Machine Setup**

**What was Done**
Kali Linux was downloaded from their website. extracted with 7-zip and imported into the VirtualBox. After the importation the Kali Linux Virtual Machine was booted in order to commence the IPV4 Network configuration

**The Image of Kali Linux Virtual Machine after Booting up**

![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/00fb9731863137210558062f8b3e9762af39845c/Kali%20Linux%20Desktop%20Preview.PNG)

**Step 5. Kali Linux Network Configuration**

**What was Done**
The Kali Linux Virtual Machine Network was manually set; gateway and DNS configure. This is necessary to enable the Kali Linux have connectivity and communication with other Virtual Machines that will set in the future.
**The Image Below was the result of the Configuration**
![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/012c4705bb7e2b99348e66b177e036761d5f6cd4/Kali%20Linux%20Network%20Adapter%20configuration.PNG)
![]()





