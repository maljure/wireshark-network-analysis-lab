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
<img width="852" height="585" alt="Wireshark-BruteForce-Traffic" src="https://github.com/user-attachments/assets/cf3b7954-2cb6-458f-b0ff-11a3e185de1d" />
<img width="1084" height="579" alt="Brute-Force-SSH-Log" src="https://github.com/user-attachments/assets/148155aa-742c-4313-bf47-3a5bb48dbc62" />
<img width="850" height="584" alt="Wireshark-TCP-Query" src="https://github.com/user-attachments/assets/6c54f36a-eefb-467c-a3de-44b04ee704b0" />
<img width="852" height="583" alt="Wireshark-Sus-Traffic-SYN-ACK" src="https://github.com/user-attachments/assets/ee2b2235-10e2-428f-b1e8-52b3fbb4ec64" />
<img width="1172" height="142" alt="Wireshark-Sus-Convo" src="https://github.com/user-attachments/assets/c8f18cbd-423e-4731-9085-26d2fd00d5d2" />
<img width="672" height="291" alt="Wireshark-Normal-Traffic-Statistic" src="https://github.com/user-attachments/assets/4fb741e6-9740-4131-9b2e-1540364f8933" />
<img width="854" height="582" alt="Wireshark-HTTP-Query" src="https://github.com/user-attachments/assets/fa3156f3-d302-4cbb-ac67-02aee79c0666" />
<img width="855" height="582" alt="Wireshark-DNS-Query" src="https://github.com/user-attachments/assets/bcdf4505-7e6e-4722-bf7e-e0044d6c52e0" />
