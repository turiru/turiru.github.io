---
title: 01 - Defining Scope and Objectives
categories: [Red-Teaming, Red-Teaming-Fundamentals, Red-Team-Engagements]
updated: 2024-04-03 08:42:17Z
created: 2023-05-15 13:01:07Z
---

Engagements can be complex and bureaucratic and the ky to a successful engagement is Clear defined client objectives. 
There should be a mutual agreement between the Red team and Client after having discussions. These objectives form the basis of the entire engagement from here onwards

Without clear objectives, preparations and execution become unstructured and unplanned. 

When assessing the objectives stated by the client during planning, we will need to determine how focused the assessment is. 

Engagements can vary from internal penetration assessment to a focused adversary emulation which would go further to define a specific threat actor group or APT. 
Selecting a threat actor can be based on the industry of the client for example finacial institutions would select [APT38](https://web.archive.org/web/20230325143301/https://content.fireeye.com/apt/rpt-apt38)

![Screenshot 2023-12-08 at 17.13.33.png](../../../_resources/Screenshot%202023-12-08%20at%2017.13.33.png)

Internal network test will be less focused on threat groups and focus on general TTPs

Client objectives will affect the rules of engagement and the scope. These objectives only provide a highlight of the engagement, as the project moves along, the project will be expounded according to the objectives. 

### Scope

The next element to a successful and transparent is the determination of a scope. This will usually vary from company to company depending on their infrastructure. 
While the objectives can be discussed by the client with the Red Team, the scope can only come from the client. 
The input from the Red Team about the scope is when they are having challenges and would therefore raise a grievance on how the scope is affecting their work.

The scope provides the Red Team a clear understanding of the Client's network and their implications of their assessment. 
The wording of the scope can be different, some examples of the scope includes
- No exfiltration of data
- Production Servers are offlimits
- 10.0.3.8/18 is out of scope
- 10.0.0.8/20 is in scope
- System downtime is not permitted under any circumstance
- Exfiltration of PII is prohibitied

It is important to understand the meanings and implications provided in the Objectives and Scope provided by the client. 
If the Red team sets its own objectives, it should do so from bare reading of the scope and objectives of the client. This provides a dynamic approach of the to how the Red Team approaches engagements


### Scenario - Global Enterprises

**Objectives**
- Identify System Misconfigurations and network weaknesses
	- Focus on external facing systems
- Determine the effectiveness of endpoint detection and response systems
- Evaluate the posture of the SIEM and overall response
	- SIEM and Detection Measures
	- Remediation
	- Segmentation of DMZ and Internal Servers
- Use of whitecards is permitted depending on the length of downtime
- Evaluate the impact of data exposure and exfiltration

**Scope**
- System Downtime is not permitted under any circumstances
	- Any form of DoS or DDoS is not permitted
	- Use of malware is prohibited including ransomeware
- Exfiltration of PII is prohibited. Exfiltrate arbitrary data
- 10.0.12.0/22 subnet is out of scope and should not be attacked
- 10.0.4.0/22 subnet is in scope and can be attacked
- Bean Enterprises will closely monitor interaction with the DMZ and critial/production systems
	- any interaction with `*.betheexchange.xyz` is prohibited
	- any interaction with `*.globalenterprises.thm` is permitted



The key to a successful red team engagement is well coordinated planning and communication between all parties the involved. 

Another factor to a successful red team engagement is clearly defined client objectives or goals. The client and the red team should discuss what is expected of each party as well as what will be provided, Objectives set the tone for the rest of the engagement.

The client objectives sets a basic definition of the client's goals of the engagement. The specific engagement plans will expand upon the client objectives and determine the specifics of the engagement

