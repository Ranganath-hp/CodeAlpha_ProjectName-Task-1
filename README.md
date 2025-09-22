Name:A Ranganath
Company:CODE ALPHA
ID:CA/SE1/5376
Domain:Cyber security
Duration:Sept to Aug 2025

Overview of Project

Project:Exploration of Cyber security

Objective

The main objective of this project is to capture and analyze network traffic packets in order to:
-Understand how data flows through the network.
-Learn the basics of protocols such as Ethernet, IP, TCP, UDP, ICMP.
-Extract useful information like source/destination IPs, ports, protocol type, and payloads.
-Gain hands-on experience with packet capturing tools and libraries

Key Activities

Environment Setup:
Installed Python 3 and required libraries (scapy).
Configured permissions to allow raw packet capture.

Packet Capture:
Captured live traffic from a specified network interface.
Implemented filtering (e.g., only TCP/UDP/ICMP packets).

Packet Analysis:
Extracted important fields: source IP, destination IP, protocol type, and ports.
Displayed packet payload in a readable hexdump format.

Data Logging & Storage:
Option to save captured packets into a .pcap file for offline analysis using Wireshark.
Collected summary statistics (protocol counts, total packets).

Program Enhancement:
Added raw-socket fallback in case Scapy is unavailable.
Ensured graceful stop with Ctrl+C and printed final summary.

Technologies Used

Programming Language: Python 3
Libraries:
-scapy → for packet sniffing, analysis, and saving .pcap files.
-socket & struct (raw sockets) → for fallback packet capture and parsing headers manually.

Tools:
-Wireshark (optional) for advanced visualization of .pcap files.

Operating Systems:
Linux/macOS/Windows (requires admin/root privileges for packet capture).

<img width="1839" height="798" alt="Screenshot 2025-09-22 190334" src="https://github.com/user-attachments/assets/ff24a7d4-5b50-4d12-aa24-90594afe38ce" />
