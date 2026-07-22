**Incident report analysis**

| Summary | The organization experienced a cybersecurity incident when its network services became unavailable without warning. After investigation, the security team determined that the outage was caused by a Distributed Denial-of-Service (DDoS) attack that overwhelmed the network with a large volume of ICMP packets. To regain control, the team blocked the malicious traffic and temporarily disabled non-essential network services, allowing critical systems to resume normal operation.  |  |  |
| :---- | :---- | ----- | ----- |
| Identify | The attack originated from one or more malicious sources that launched an ICMP flooding attack against the organization's infrastructure. The excessive traffic impacted the entire internal network, making key services inaccessible. The primary objective was to protect critical assets and restore essential network functionality.  |  |  |
| Protect | To strengthen defenses against similar attacks, the cybersecurity team introduced firewall rules that restricted the rate of incoming ICMP traffic. They also deployed an Intrusion Detection and Prevention System (IDS/IPS) to identify and block suspicious ICMP packets before they could affect network performance.  |  |  |
| Detect | The team enhanced monitoring capabilities by enabling source IP validation on the firewall to identify spoofed IP addresses associated with incoming ICMP packets. In addition, network monitoring tools were configured to continuously observe traffic and generate alerts whenever unusual activity or abnormal traffic patterns were detected.  |  |  |
| Respond | To improve incident handling in the future, the cybersecurity team plans to immediately isolate affected systems to contain the attack and minimize its impact. Critical applications and services will be restored as a priority, followed by a thorough review of network logs to identify malicious activity and determine the attack's origin. Any significant incidents will be documented and reported to management and relevant legal or regulatory authorities when necessary.  |  |  |
| Recover | Recovery from an ICMP flood attack focuses on restoring normal network operations while minimizing further disruption. Firewall protections should be used to block malicious ICMP traffic at the perimeter, and non-essential services should remain offline until the attack subsides. Once the network is stable, critical systems should be restored first, followed by the gradual reactivation of remaining services after malicious traffic has stopped.  |  |  |

---

| Reflections/Notes: |
| :---- |

