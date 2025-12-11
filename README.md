# Week 2: Nmap & Scapy Network Analysis Lab

Author: Hamza Bacha  
Date: 11 December 2024  
Target: 192.168.75.132 (VMware Virtual Machine)

 Objectives
- Perform comprehensive network reconnaissance using Nmap
- Understand packet crafting and analysis with Scapy
- Document real-world cybersecurity scanning techniques
- Practice safe and ethical penetration testing methods

 Tools Used

- Nmap - Network discovery and security auditing
- Scapy - Interactive packet manipulation tool
- Target Environment - VMware virtual machine (192.168.75.132)

 Lab Summary

Nmap Scanning Exercises

1. Host Discovery - Verified target availability using ping and Nmap
2. Port Scanning - Identified open ports (quick scan and full 65,535 ports)
3. Service Detection - Determined running services and versions
4. OS Fingerprinting - Identified operating system characteristics
5. Vulnerability Assessment - Used NSE scripts to find potential weaknesses
6. UDP Scanning - Checked for UDP services

 Scapy Packet Analysis

1. Basic Packet Creation - Built IP and ICMP packets from scratch
2. Ping Implementation - Sent custom ping packets and received responses
3. ARP Requests - Resolved IP to MAC address (00:0c:29:b7:91:0e)
4. Packet Sniffing - Captured and analyzed live network traffic

📊 Key Findings

Open Ports Discovered:
- Port 21 (FTP)
- Port 22 (SSH)
- Port 80 (HTTP)
- Port 3306 (MySQL)
- Additional services identified via service detection

Network Information:
- IP: 192.168.75.132
- MAC: 00:0c:29:b7:91:0e
- Vendor: VMware, Inc.

 What I Learned

 Technical Skills
- How to perform systematic network reconnaissance
- Understanding of TCP/IP packet structure
- Practical application of different scan types
- The importance of ethical hacking boundaries

 Key Insights
- Nmap: is powerful for automated scanning and vulnerability detection
- Scapy: provides granular control over packet crafting
- Different scan types reveal different information (stealth vs aggressive)
- Port scanning must always be done with proper authorization

Challenges Faced
1. Scapy Syntax** - Initially struggled with layer stacking (IP/ICMP notation)
2. Permissions** - Needed sudo for raw packet access
3. nderstanding Flags** - Learning TCP flags (SYN, ACK, RST)
4. Response Interpretation** - Distinguishing between open, closed, and filtered ports

Security Considerations
Important:** All scans were performed in a controlled lab environment with proper authorization. Never scan networks or systems you don't own or have explicit permission to test.

Repository Contents
- `nmap-scans/` - All Nmap command outputs and screenshots
- `scapy-labs/` - Scapy exercise documentation and screenshots
- `scripts/` - Python scripts created during the lab
🔗 References
- [Nmap Documentation](https://nmap.org/docs.html)
- [Scapy Documentation](https://scapy.net/)


