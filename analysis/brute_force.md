# SSH Brute Force Analysis

## Overview
This analysis focuses on network traffic generated during a simulated SSH brute-force attack. The goal was to identify patterns associated with repeated authentication attempts.

---

## Attack Description
A brute-force attack was executed from the attacker machine (Kali Linux) targeting the SSH service (port 22) on the victim machine (Ubuntu) using Hydra.

---

## Observations

### Repeated Connection Attempts
- Multiple TCP connections to port 22 were observed  
- All connections originated from a single source IP  
- High frequency of connection attempts within a short time period  

### Session Behavior
- Connections were short-lived  
- No sustained sessions were established  
- Repeated attempts indicate automated activity  

---

## Traffic Pattern Analysis
- Consistent targeting of SSH service  
- Rapid succession of connection attempts  
- Lack of normal user interaction patterns  

---

## Indicators of Compromise (IOCs)
- Repeated connections to port 22  
- High volume of traffic from a single source  
- Short-lived TCP sessions  

---

## Conclusion
The observed traffic is consistent with an SSH brute-force attack. The attacker repeatedly attempted to authenticate using multiple credentials, which is characteristic of automated tools such as Hydra.

---
