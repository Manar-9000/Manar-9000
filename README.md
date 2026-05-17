# Manar Mohsin


## Projects

---

## Projects

### [Windows Server Active Directory Home Lab](https://github.com/Manar-9000/Windows-Server-AD-Lab-macOS)
A complete virtualization of a corporate network environment designed to simulate 
real-world IT enterprise infrastructure, identity management, and endpoint security enforcement.

* **Core Technologies:** Windows Server 2022, Windows 11, VMware Fusion, Active Directory (AD DS), DNS, Group Policy (GPO), NTFS File Systems
* **Key Achievements:**
  * **Identity & Access Management:** Configured a centralized Domain Controller (`manar.local`) and built custom Organizational Units (OUs) to enforce the Principle of Least Privilege for non-administrative accounts
  * **Automated Security Policies:** Engineered and deployed custom Group Policy Objects (GPOs) to restrict system access across endpoint environments, verified via `gpupdate /force`
  * **Network Administration:** Implemented static IPv4 routing, configured internal DNS mapping, and diagnosed Layer 3 connectivity roadblocks caused by host-level firewall configurations
  * **Data Integrity Enforcement:** Provisioned network file shares with strict Read-Only NTFS permissions to protect departmental assets from unauthorized modifications

[View Full Lab Documentation](https://github.com/Manar-9000/Windows-Server-AD-Lab-macOS)

---

### [IT Help Desk Troubleshooting Lab](https://github.com/Manar-9000/Troubleshooting-Lab)
A collection of real-world corporate IT support scenarios diagnosed and resolved within 
a live Active Directory environment (`manar.local`). Each ticket follows a structured 
Problem → Investigation → Resolution format mirroring enterprise help desk workflows.

* **Core Technologies:** Windows Server 2022, Windows 11, Active Directory, Group Policy, DNS, Print Management
* **Tickets Resolved:**
  * **Ticket #1 — DNS Misconfiguration:** Diagnosed a broken network share caused by a misconfigured DNS pointing to Google (`8.8.8.8`) instead of the internal Domain Controller. Resolved via `ipconfig /flushdns` and DNS reconfiguration
  * **Ticket #2 — Account Lockout Remediation:** Investigated and resolved an Active Directory account lockout for user `jdoe`, performed administrative password reset with forced change at next logon to maintain security integrity
  * **Ticket #3 — Automated Printer Deployment via GPO:** Deployed a network printer to all domain users using Group Policy. Diagnosed and resolved a PrintNightmare-related Point and Print security block by modifying trusted server policy on the Domain Controller

[View Full Ticket Documentation](https://github.com/Manar-9000/Troubleshooting-Lab)

---

### [PowerShell SysAdmin Scripts](https://github.com/Manar-9000/PowerShell-SysAdmin-Scripts)
A collection of real-world PowerShell automation scripts written, tested, and verified 
in a live Windows Server 2022 Active Directory environment. Demonstrates the shift from 
manual GUI administration to scalable, repeatable automation.

* **Core Technologies:** PowerShell, Windows Server 2022, Active Directory, WMI
* **Scripts Built:**
  * **Bulk AD User Creator:** Reads a CSV file and automatically provisions multiple Active Directory user accounts in seconds, replacing hours of manual GUI work
  * **Locked Account Checker:** Proactively scans the entire domain for locked accounts and reports username, full name, and bad logon attempt count, enabling detection before users call the help desk
  * **System Info Report:** Pulls hostname, OS version, IP address, uptime, and RAM stats from any Windows machine instantly, eliminating the need to ask users for basic system information during support calls

[View Full Script Documentation](https://github.com/Manar-9000/PowerShell-SysAdmin-Scripts)

---

## Certifications
* CompTIA A+
* Currently studying: CompTIA Security+ | AWS Cloud Practitioner

## Technical Skills
* **Operating Systems:** Windows Server 2022, Windows 11, macOS
* **Identity & Access:** Active Directory, Group Policy, NTFS Permissions, OU Management
* **Scripting & Automation:** PowerShell, CSV automation, WMI queries
* **Networking:** DNS, DHCP, Static IP, NAT, TCP/IP troubleshooting
* **Virtualization:** VMware Fusion, VM networking, Snapshots
* **Hardware:** CompTIA A+ certified: PC assembly, peripherals, troubleshooting
