---
title: 02 - Red Team Engagements
categories: [Red-Teaming, Red-Team-Fundamentals, The-Fundamentals]
updated: 2023-05-13 13:35:39Z
created: 2023-05-13 13:17:30Z
---

Red Team engagements don't replace traditional penetration tests, but complement them by focusing on detection and response rather than prevention.

red team engagements focuses on measuring defensive team's capabilities at detecting and responding to a real threat actor. 

Red team engagements also improve on regular penetration tests by considering several attack surfaces:
- Technical Infrastructure
- Social Engineering
- Physical Intrusion


Red team engagements consist of emulating a real threat actor's Tactics, Techniques and Procedures (TTPs) so that we can measure how well our blue team responds to them and ultimately improve any security controls in place.

A red team engagement will start by defining clear goals for example making a swift transaction. The red team will do everything they can to achieve the goals while remaining undetected and evading any existing security mechanisms like firewalls, antivirus, EDR, IPS and others. A real attacker would only need to find a single path to its goal and is not interested in performing noisy scans that the blue team could detect.

the blue team is not informed of the red team activities to avoid introducing any biases in their analysis. 

It is important to note that the final objective of such red team should never be for the red team to "beat" the blue team, but rather simulate enough TTPs for the blue team to learn to react to a real ongoing threat adequately.

Depending on the resources available, the red team exercise can be run in several ways:

- **Full Engagement:** Simulate an attacker's full workflow, from initial compromise until final goals have been achieved.
- **Assumed Breach:** Start by assuming the attacker has already gained control over some assets, and try to achieve the goals from there. As an example, the red team could receive access to some user's credentials or even a workstation in the internal network.
- **Table-top Exercise:**  An over the table simulation where scenarios are discussed between the red and blue teams to evaluate how they would theoretically respond to certain threats. Ideal for situations where doing live simulations might be complicated.
