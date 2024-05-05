---
title: 04 - Red Team Engagement Structure
categories: [Red-Teaming, Red-Team-Fundamentals, The-Fundamentals]
author: Gatura
updated: 2024-03-11 05:41:25Z
created: 2023-05-15 10:37:30Z
---

A core function of the Red team is to emulate and adversary by assessing how an adversary would use their tactics techniques and procedures as well as tools in the network environment of a client. 
The red team can use a number of cyber kill chains to summarise the steps and procedures that they have taken in a particular assignment

The blue team on the other hand use cyber kill chains to map behaviours of adversaries and breakdown their actions during an attack. The blue team uses the cyber kill chains to map adversaries TTPs to the red team engagement

Examples of Cyber Kill Chains
- Lockheed martin cyber kill chain
- Unified kill chain
- Varonis Cyber Kill chain
- Active directory attack cycle
- MITRE ATT&CK Framework

For tryhackme red team we will use the Lockheed Martin Cyber Kill chain which focuses on a perimeter or external breach

![Screenshot 2023-05-15 at 13.45.13.png](../assets/_resources/Screenshot%202023-05-15%20at%2013.45.13.png)

| Technique | Purpose | Example |
|-----------|---------|---------|
| Reconnaissance | Obtain Information about the target |Harvesting emails and OSINT |
| Weaponization | Deliverable payload | malicious office documents |
| Delivery | How the exploit will be delivered to the target | Email, web, USB |
| Exploitation | Execute the code in the the target's environment | ZeroLogon, MS17-010 |
| Installation | Install malware and other tooling | Mimikatza rubeus |
| Command and Control | Control the compromised asset from a remote controller | Empire Cobalt strike |
| Actions on Objectives | any end objectives - ransomware data exfiltration | Conti Lockbit 2.0 |
