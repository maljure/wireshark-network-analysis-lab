# Baseline Network Traffic Analysis

## Overview
This analysis examines normal network traffic captured in a controlled virtual environment. The goal is to establish a baseline of expected behavior to compare against potential malicious activity.

---

## Traffic Generation
The following actions were performed to generate baseline traffic:
- Ping requests to external domains
- DNS queries (e.g., google.com)
- HTTP requests using curl

---

## Protocol Analysis

### DNS (Domain Name System)
- Observed standard query-response behavior  
- Queries sent to resolve domain names such as google.com  
- Responses returned valid IP addresses  

**Conclusion:** DNS traffic behaved normally with no anomalies.

---

### ICMP (Ping Traffic)
- ICMP echo requests and replies were observed  
- Successful responses confirmed connectivity between systems  

**Conclusion:** Network connectivity is stable with no packet loss detected.

---

### HTTP (Web Traffic)
- HTTP GET requests were captured in plaintext  
- Server responses included requested web content  

**Conclusion:** HTTP traffic is visible and unencrypted, allowing full packet inspection.

---

### TCP (Transmission Control Protocol)
- Standard 3-way handshake observed:
  - SYN → SYN-ACK → ACK  
- Connections were successfully established and terminated  

**Conclusion:** TCP connections function normally with no irregular patterns.

---

## Traffic Patterns Observed
- Consistent request-response communication  
- No excessive retries or failed connections  
- No unusual spikes in traffic volume  

---

## Protocol Distribution
(Refer to Wireshark Protocol Hierarchy statistics)

- Majority of traffic consisted of:
  - TCP
  - DNS
  - ICMP  

---

## Key Takeaways
- Normal traffic follows predictable and structured patterns  
- DNS queries resolve quickly with valid responses  
- TCP connections complete full handshakes  
- No suspicious or anomalous behavior observed  

---

## Conclusion
The captured traffic represents a normal operating baseline. This baseline will be used to identify deviations and detect malicious activity in subsequent attack simulations.
