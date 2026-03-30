# Port Scan Analysis

## Overview
This analysis examines network traffic generated during a simulated port scan using Nmap. The objective was to identify reconnaissance behavior through packet-level inspection.

---

## Attack Description
A SYN scan was launched from the attacker machine (Kali Linux) targeting the victim machine (Ubuntu) to identify open ports.

---

## Observations

### TCP SYN Packets
- A high volume of TCP SYN packets was observed  
- Packets originated from a single source IP address  
- Multiple destination ports were targeted in rapid succession  

### Connection Behavior
- Many connections were not fully established  
- SYN packets were not consistently followed by full TCP handshakes  

---

## Traffic Pattern Analysis
- Rapid scanning of multiple ports  
- No sustained communication sessions  
- Repetitive connection attempts within a short time frame  

---

## Indicators of Compromise (IOCs)
- Single source IP scanning multiple ports  
- High frequency of SYN packets  
- Incomplete TCP connections  

---

## Conclusion
The observed traffic is consistent with a TCP SYN scan (Nmap). This type of activity is commonly used by attackers to perform reconnaissance and identify open services on a target system.

---

## Supporting Evidence
- Wireshark filter used:  
