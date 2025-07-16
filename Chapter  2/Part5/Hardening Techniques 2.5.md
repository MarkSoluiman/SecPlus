
---

## System Hardening 

Always apply the security updates for OSs.

Secure user accounts with strong password criteria (length, characters included, etc ), and set account limitations.

Limit network access by adding a range of IP addresses that can't access the device/server.

Always monitor the system and secure it with anti-virus/anti-malware.

## Endpoint Detection and Response (EDR) 2.5

They detect a threat by signatures of malware stored in their DB. They also perform behavioral analysis using machine learning and process monitoring to identify new suspicious processes that can appear. 

EDRs can also preform root cause analysis to identify how the malware entered the system.

EDRs can finally make a decision by isolating the system, quarantine the threat, rollback to a previous config.

## Host-Based Firewall

This is a software-firewall that allows or disallows incoming or outgoing application traffic. These firewalls can stop malware before it can start by preventing incoming malicious traffic. 

## Finding Intrusions 

**Host-Based Intrusion Prevention System (HIPS)** look for known attack types on the network. They are often built into the EDR or anti-malware software to watch all of the traffic that is inbound to the system to look for a known vulnerability. HIPS can also secure applications and OS configs. 

HIPS identify attacks and vulnerabilits by signatures, heursitics, and behavioral. 
It can also identify buffer overflow, registry updates, writing files to the Windows folder when they happen.

## Open Ports and Services

Every port is a possible entry point for attackers. Every port should be closed except the required ports. Firewall should be installed and configured to watch the traffic running on these ports. 


