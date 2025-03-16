# ICMP Flooding Attack & Wireshark Analysis

## Project Overview
This project investigates a **Distributed Denial of Service (DDoS) attack** targeting XYZ Hospital’s records server. The attack, executed through **ICMP flooding**, resulted in **server downtime**, preventing medical staff from accessing critical patient records. Using **Wireshark**, the network traffic was analyzed to detect attack patterns, assess vulnerabilities, and propose security enhancements.

## Key Findings
  - **Wireshark Analysis Identified:**
   - An unusually high volume of **ICMP Echo Requests** (Type 8) from multiple IP sources.
   - No ICMP Echo Replies (Type 0), suggesting the server was overwhelmed.
   - Packets arriving within **extremely short intervals**, confirming a flood attack.

  - **Main Security Gaps:**
   - **Lack of ICMP rate limiting** allowed unlimited echo requests.
   - **No Intrusion Detection System (IDS)** to flag abnormal traffic patterns.
   - **Absence of cloud-based DDoS protection**, leaving the network vulnerable.

## Tools & Technologies Used
- **Wireshark** – Packet capture & network traffic analysis.
- **ICMP Protocol Analysis** – Identifying attack behavior in network traffic.
- **Firewall Security** – Reviewing packet filtering and rate limiting options.
- **Intrusion Detection Systems (IDS)** – Investigating security monitoring solutions.

## Security Recommendations
- **Implement ICMP Rate Limiting** – Restrict excessive echo requests to prevent overload. -- **Deploy Intrusion Detection System (IDS)** – Monitor for spikes in ICMP requests and trigger alerts.
- **Utilize Cloud-Based DDoS Protection** – Filter malicious traffic before it reaches the network.

## Skills Gained
- **Network Traffic Analysis** using Wireshark.
- **Understanding DoS/DDoS attack methodologies**.
- **Packet Behavior Analysis & Attack Detection**.
- **Firewall & Intrusion Detection Security Best Practices**.

  
**Disclaimer:**  
This repository contains only a summary of my **Wireshark Analysis project**. The full report was submitted as part of a university assignment and cannot be shared publicly due to academic integrity and copyright policies. 





