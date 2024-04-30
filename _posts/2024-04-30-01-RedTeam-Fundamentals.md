---
title: 01 - Red Team Fundamentals
categories: [Red-Teaming, Red-Team-Fundamentals, The-Fundamentals]
updated: 2024-04-03 08:30:36Z
created: 2023-05-13 12:53:13Z
---

Cybersecurity is a constant race between white hat hackers and black hat hackers.

vulnerability assessments and penetration tests provide an overview of the technical security posture of a company. 

As important as vulnerability assessments and penetration tests are, they miss one crucial element, how to respond to an actual ongoing attack by a motivated adversary.

### Vulnerability Assessment

simplest form of security assessment

a vulnerability assessment focuses on scanning hosts for vulnerabilities as individual entities so that security deficiencies can be identified and effective security measures can be deployed to protect the network in a prioritized manner. Most of the work can be done with automated tools and performed by operators without requiring much technical knowledge.

Its main objective is to identify as many vulnerabilities in as many systems in the network as possible. 
As a result, concessions may be made to meet this goal effectively. For example, the attacker's machine may be allowlisted on the available security solutions to avoid interfering with the vulnerability discovery process.

### Penetration Test

Penetration tests add to vulnerability assessments by allowing the pentester to explore the impact of an attacker on the overall network by doing additional steps that include:

- Attempt to exploit the vulnerabilities found on each system. This is important as sometimes a vulnerability might exist in a system, but compensatory controls in place effectively prevent its exploitation. It also allows us to test if we can use the detected vulnerabilities to compromise a given host.
- Conduct post-exploitation tasks on any compromised host, allowing us to find if we can extract any helpful information from them or if we might use them to pivot to other hosts that were not previously accessible from where we stand.


Penetration tests might start by scanning for vulnerabilities just as a regular vulnerability assessment but provide further information on how an attacker can chain vulnerabilities to achieve specific goals. While its focus remains on identifying vulnerabilities and establishing measures to protect the network, it also considers the network as a whole ecosystem and how an attacker could profit from interactions between its components.

By analyzing how an attacker could move around our network, we also gain a basic insight on possible security measure bypasses and our ability to detect a real threat actor to a certain extent, limited because the scope of a penetration test is usually extensive and Penetration testers don't care much about being loud or generating lots of alerts on security devices since time constraints on such projects often requires us to check the network in a short time.

### Advanced Persistent Threats and why Regular Pentesting is not Enough

Vulnerability Assessments and Penetration tests cover the finding of most technical vulnerabilities, however they have limitations that would help a company prepare for real adversaries. These are
- Limited Time
- Budget
- Limited Scope
- Non Disruptive
- Heavy IT Focus

This makes vulnerability assesments and penetration tests differ from a real attack

- Penetration tests are LOUD: 
- Non-technical attack vectors might be overlooked
- Relaxation of security mechanisms: 

Nowadays there are is a calibre of highly skilled attackers, usually sponsored by nations or organised criminal groups primarily target critical infrastructure, financial organisations, and government institutions.They are called persistent because the operations of these groups can remain undetected on compromised networks for long periods.

If a company is affected by an APT, how would it be prepared to respond effectively? Could they detect the methods used to gain and maintain access on their networks if the attacker has been there for several months? 

What if the initial access was obtained because John at accounting opened a suspicious email attachment? What if a zero-day exploit was involved? Do previous penetration tests prepare us for this?

To provide a more realistic approach to security, red team Engagements were born.
