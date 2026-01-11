# Metasploitable2-PenetrationTest
penetration testing lab on Metasploitable 2 (Educational)

📌 Project Overview

This project demonstrates a basic penetration testing workflow conducted in a controlled lab environment using Metasploitable 2. The goal is to identify vulnerable services, research known vulnerabilities, and perform exploitation using industry-standard tools.

⚠️ Disclaimer: This project was performed in a legal and isolated lab environment for educational purposes only.

🧪 Lab Environment

Attacker Machine: Kali Linux

Target Machine: Metasploitable 2

Network: Local lab (VirtualBox / VMware)

🛠️ Tools Used

Nmap (Service & version scanning)

Searchsploit (Vulnerability research)

Metasploit Framework (Exploitation)

🔍 Scanning & Enumeration

Initial service and version scan was performed using:

nmap -sV <target-ip>

Discovered services included:

FTP (vsftpd 2.3.4)

SSH

Telnet

MySQL

🔎 Vulnerability Research

Known vulnerabilities were researched using:

searchsploit vsftpd 2.3.4

The service was identified as vulnerable to a backdoor command execution vulnerability.

💥 Exploitation

Exploitation was performed using Metasploit Framework

Successful exploitation resulted in bind shell access on the target system

📽️ Video Demonstration (Unlisted):

Add your YouTube link here

🛡️ Impact

Unauthorized remote access

Potential full system compromise

🔐 Mitigation Recommendations

Update vulnerable services to latest versions

Disable unused services (FTP / Telnet)

Apply firewall rules and network segmentation

📚 What I Learned

Service enumeration and version detection

Vulnerability research using public databases

Practical exploitation using Metasploit

Importance of patch management and secure configuration
