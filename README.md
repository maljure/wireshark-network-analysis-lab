# Network Traffic Analysis Lab (Wireshark)

## Overview
This project simulates real-world network activity and cyber attacks in a controlled virtual lab environment. Wireshark was used to capture and analyze traffic to identify normal behavior and detect malicious activity. I have two VM's (Kali Linux and Ubuntu) to help similate attacks. 

---

## Objectives
- Analyze normal network traffic to make sure everything is functioning.
- Detect reconnaissance activity using Nmap.
- Identify SSH brute-force authentication attacks using Hydra.
- Develop packet-level analysis skills and get Hands-on experience using Wireshark, Nmap, and Hydra. 

---

## Lab Environment
- **Attacker:** Kali Linux (IP: 192.168.20.129)
- **Victim:** Ubuntu (IP: 192.168.20.128) 
- **Network:** NAT (isolated virtual network)  
- **Tools:** Wireshark, Nmap, and Hydra. 

---

## Attack Scenarios

### 1. Baseline Traffic
- DNS queries (google.com)
- HTTP requests (http://example.com)
- ICMP (ping)

### 2. Port Scan (Nmap)
- SYN scan used to identify open ports

### 3. SSH Brute Force (Hydra)
- Multiple login attempts targeting port 22

---

## Key Findings

- Identified many TCP SYN scans that indicate reconnaissance  
- Detected repeated SSH connection attempts consistent with brute-force attacks  
- Observed normal DNS and HTTP traffic for baseline comparison  

---

## Skills Demonstrated
- Packet analysis using Wireshark
- Ability to use Nmap and Hydra to simulate attacks.
- Network protocol analysis (TCP/IP, DNS, HTTP, ICMP)  
- Threat detection and pattern recognition  
- Cybersecurity lab development  

---

## Screenshots
