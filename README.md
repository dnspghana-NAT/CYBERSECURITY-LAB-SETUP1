# CYBERSECURITY-LAB-SETUP1
## 🎯Project Purpose and introduction
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

## ⚙️Laboratory Architecture/Resources
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

## 🚀Virtual Laboratory Setup
The Theoretical workflow of virtual Laboratory Setup:
1. Download and Install 7-zip
2. download and install Oracle VirtualBox
3. Configure the VirtualBox Nat Network
4. Download and import Kali Linux
5. configure and enable Kali Linux Nat Network
6. configure Kali Linux Ip settings
7. Take snapshot of the VM

## 🚀 Practical Workflow of Laboratory Setup

**Step1. Installation of 7-zip**

**What was Done**
7-zip  was downloaded and installed. This was necessary for file management and extraction. The Kali Linux was downloaded in zip format, which needed to be extracted before importation into the VirtualBox.

**Step 2. Oracle VirtualBox Installation**

**What was Done**
The VirtualBox was downloaded from their official website and installed. The VirtualBox provide a Virtual space necessary for Cybersecurity practices. It also creates a platform to run multiple Virtual Machine in addition to Kali Linux.

**Below was an Image of the VrtualBox Installation**

![ Image of VirtualBox Installation phase](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/f33377384b6f6eeceb193fc9fcfe41ed0ad7ae6d/Virtual%20Box%20Installation%20phase.PNG) 
![ImageofVirtualBoxInstallation](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/1b7457d3b27b1a3c40a3549709947c2e8d42c74f/Virtual%20Box%20Installation%20phase1.PNG)

*⚙️*Step 3. Nat Network Configuration**

**what was Done**
Nat Network of Ipv4 of 10.0.0.0/24 was configured and DHCP also enabled on the VirtualBox. This helps create a controlled space for multiple Virtual Machine communicate with each other as well as the external Cyberspace.

**The Result of the configuration is Shown Below**

![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/301de8426cb266ee285b8c8b6fa26fc121f964e4/Virtual%20Box%20Nat%20Network%20Set%20Up.PNG)

**Step 4. Kali Linux Virtual Machine Setup**

**What was Done**
Kali Linux was downloaded from their website. extracted with 7-zip and imported into the VirtualBox. After the importation the Kali Linux Virtual Machine was booted in order to commence the IPV4 Network configuration

**The Image of Kali Linux Virtual Machine after Booting up**

![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/00fb9731863137210558062f8b3e9762af39845c/Kali%20Linux%20Desktop%20Preview.PNG)

**⚙️Step 5. Kali Linux Network Configuration**

**What was Done**
The Kali Linux Virtual Machine Network was manually set; gateway and DNS configure. This is necessary to enable the Kali Linux have connectivity and communication with other Virtual Machines that will set in the future.

**The Image Below was the result of the Configuration**

![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/012c4705bb7e2b99348e66b177e036761d5f6cd4/Kali%20Linux%20Network%20Adapter%20configuration.PNG)
![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/3ba35c8eee49d4248eb823fb879517a819b5530c/Kali%20Linux%20Network%20configuration.PNG)

**Creation of a clean Kali Linux Virtual Machine Snapshot**

**What was Done**
The final configuration of Kali was initiated by taking a snapshot of the virtual machine which represent a clean baseline for the virtual space for Cybersecurity practices, and this is necessary because it serves a backup for any damage that may occur during process testing. 

**The shot was dated for easy record as depicted in the graphical image below:**

![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/79ab68dcbe53a457a9e20d155cf7e322cf5824b6/Kali%20Snapshot.PNG)

**✅Step 6. Laboratory Setup Verification and Functionality**
|TEST|COMMAND|EXPECTED RESULT|
|----|-------|---------------|
|Check Kali IP|IPa| ![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/c16e330eb7a841a84ea10855f10fc4ca80af0052/Kali%20ip%20check.PNG)          |
|Gateway|ping 10.0.0.1|![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/9dc15d33246c9f4e9b59b171c185daff0aa7e23e/ping%20gateway.PNG)       |
|Internet connectivity|ping 8.8.8.8|![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/2cd4422d9ac61b4a7d96625cba6ec0a97720497b/ping%208.8.8.8.PNG)    |
|DNS Resolution|nslookup www.networkwalks.com|![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/ddd79adff66c51c293d5127499fdad426ceb4ff6/nslookup.PNG)    |
|Verify Nmap| Nmap--v|![](https://github.com/dnspghana-NAT/CYBERSECURITY-LAB-SETUP1/blob/4107bdb2fca97caba5ff45a1e2a278b4c790823a/Nmap%20v.PNG)                      |

**🔑Key lessons Learned**

1.	I learned how to use the host system resource to create a virtual space for Cybersecurity practices
2.	A NAT Network allows multiple Virtual Machines connected to the same virtual network to communicate with one another while providing network address translation for external connectivity.
3.	I have also learned how to upgrade my old installed virtual box to version 7.2.14 without uninstalling the old one but rather moving to control panel on the host machine, programs, clicking on the old one and then click on remove and back to run the new version on the desktop. The interesting thing was that ,step did not delete my previously install window 10 from the virtual machine
4.	Finally I learned that taking a snapshot of the VM serve as  backup for recovering in case of virtual machine failure.

**Challenges and Solution**

1.	After the manual configuration of IPV4 address of the Kali Linux  the command ip a was only displaying the loopback and other. However after entering the command eth0 down and eth0 up the Kali IP address 0f 10.0.0.6 was displayed
2.		Screen recording of the procedure or the steps of the configuration was key challenge I face notwithstanding I reverted to taking screenshots
   
**🔒Security and Ethical use**

The laboratory was purposefully designed and build for only ethical hacking and educational practices

**👨‍🏫Mentor**

Waqas Karim [CCIE]
I appreciate your Technical Insight and guidance throughout the internship. I can never forget your passion and the drive which have been a pillar of motivation since I started this journey with you.

**Author**

Nathaniel Apuru Avaraako

Cybersecurity Professional B082.

IT Diploma B080.6

Linked in: www.linkedin.com/in/nathaniel-apuru-avaraako-7b9620404
