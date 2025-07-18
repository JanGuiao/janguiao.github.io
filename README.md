# Former System Administrator | Life-long learner 

#### Skills: Office 365 | Asset Management | Security Event Management | Patch Management | Power BI | Network Configuration (TCP/IP, DNS, DHCP, LAN/WAN) Powershell | RDP | Active Directory | VoIP | ServiceNow

# Education
- B.S., Cybersecurity Technology | University of Maryland Global Campus | GPA 3.94/4.0 (_May 2024_) 						       	
- A.A.S, Cloud Computing and Networking Technology | Montgomery College (_May 2022_) 

# Work Experience

**System Administrator, Ministry of Health - Saudi Arabia | Washington D.C. (_December 2024 - June 2025_)** 
- Provided comprehensive technical support and infrastructure management for 35–40 end-users, ensuring 99.9% uptime across 
workstations, servers, and network systems. 
- Liaised with Saudi Ministry of Health (MOH) officials to scope and plan a nationwide medical data infrastructure project 
aimed at enhancing case tracking and remote advising for Saudi patients in the U.S. 
- Delivered both remote and on-site training to improve user digital literacy, onboarding efficiency, and system compliance. 
- Led an office-wide network infrastructure upgrade project, planning and executing structured cabling, cradlepoint integration, 
and physical layer redundancies for scalability.


**Help Desk Intern, John F. Kennedy (_December 2018 - May 2019_)**
- Expedited resolution of technical issues through application of foundational IT knowledge, resulting in a substantial 50% improvement in system operation.
- Led strategic initiatives involving diagnosis, repair, and replacement of an average of 10-15 devices.
- Achieved a notable 30% reduction in downtime and a significant boost in operating productivity.
- Collaborated with students and users to swiftly resolve issues, boosting satisfaction, strengthening trust, and achieving an 80% increase in user experience. Implemented impactful user training and awareness initiatives for IT service.
- Led independent optimization of troubleshooting processes, reducing resolution times by 20% and mitigating recurring issues, enhancing overall efficiency in help desk environment.
  

# Personal Projects

### Personal Homelab Environment
This is my personal homelab! It is currently a work-in-progress (WIP) as I will continually upgrade it. 

### Utilities 

- **Rackmate T1 (8U)** (Server Rack) 

- **Icy Dock 6-Bay 2.5" SATA Enclsoure** -- WIP 🚧

- **Dell Optiplex 3060** (Will run Proxmox VE, a free hypervisor installed from a bootable USB. Used to create virtual machines (VMs) and LXC containers for sandboxed environments like malware testing or OS/application experimentation. Managed via a browser-based web UI over local network.)

- **Dell Optiplex 3070** (Also running Proxmox VE. This node will host Docker contaienrs or VMs for services like a media server (Jellyfin), game servers (TBD), or self-hosted tools (e.g., Bookstack, Portainer). Network services and RDP access will be enabled for remote access from other devices on LAN.)

- **Managed PoE 8-Port Switch** 
(Used as the primary network switch, connecting all devices via Cat6 Ethernet cables. It supports VLAN configuration, port isolation, and traffic monitoring via its web interface. Although PoE is not needed yet, it prepares myself for future PoE-capable devices like IP cameras or Raspberry Pi with PoE HATs.)

- **KVM Switch** (Enables local control of both Optiplexes using one monitor, keyboard, and mouse. I'll physically connect the KVM to each Optiplex via HDMI/DisplayPort and USB, allowing to toggle between machines during OS installations and maintenance.)

## TBD equipment: 

- **Motherboard ITX**: (ASRock J5040-ITX or newer alternative) - (Acts as the dedicated system board for my NAS/server node, hosting TrueNAS SCALE (an open-soruce NAS OS based on Debian with ZFS support - TrueNAS - ZFS - Web UI Management - SMB/NFS shares - possible RAID) 

- **PCIe x1 SATA Expansion Card (2 ports)**: - (Extends the number of SATA ports on the ITX motherboard (from 4 to 6 total) to fully utilize all 6 drive bays in the **ICY Dock** enclosure)

- **PSU**: (PSU that powers the ITX mobo and the ICY DOCK enclosure. Should have enough SATA power connectors to supply 6 drives for stable power delivery) 


<p align="center"> 
<img src="https://github.com/user-attachments/assets/3992afe0-26f0-4812-9c91-94bffcd2bfe5" width="300"/> 
</p>




# Cont. Projects... (see github repositories)

### [SIEM in Microsoft Azure (_Sentinel_)](https://github.com/JanGuiao/SIEM-In-Microsoft-Azure-Sentinel-/tree/main)
Spun up a Windows 10 VM in Azure, locked it down with custom firewall rules, and let the simulated cyberattacks begin. Wired it into Log Analytics to catch every event, then used PowerShell and a geolocation API to track where the failed RDP logins were coming from. Wrapped it all up with Azure Sentinel’s interactive maps to visualize threat patterns in real time and turn raw data into security insights.

### [Active Directory Home Lab (_Windows_)](https://github.com/JanGuiao/ActiveDirectoryLab)
Set up a fully functional domain controller using Windows Server 2019 in a virtualized environment. Configured internal and NAT networking to create a secure, isolated lab for testing. Automated user creation with PowerShell to streamline administration tasks. Connected a Windows 10 client to the domain and validated network connectivity for smooth domain operations.


### [File System Watcher (_PowerShell_)](https://github.com/JanGuiao/FileSystemWatcher) 
Developed a PowerShell script using the System.IO.FileSystemWatcher object to monitor a directory for real-time changes—such as file edits, creations, deletions, and renames. Integrated event handlers to trigger custom alerts and logging whenever changes occurred. Validated the script through controlled testing, confirming its accuracy in detecting and reporting critical file system activity.


### [Minecraft Pi via (_Raspberry Pi OS_)](https://github.com/JanGuiao/Minecraft-Pi/tree/master)
Developed and executed Python scripts to perform various tasks within Minecraft, such as sending messages, manipulating player position, and altering the game environment. Implemented advanced game modifications, including creating structures and experimenting with game physics through code. Demonstrated ability to troubleshoot and resolve issues related to both software and hardware configurations.


# **Certifications**
- [CompTIA Security+ (April 2024)](https://www.credly.com/badges/8dc121ca-f3d8-4252-aed4-10e2101fe8fa/public_url)


# **Others**
- Dean's List at University of Maryland Global Campus (UMGC) 
- Tau Chapter of Alpha Sigma Lambda





