
---

## Edge VS. Access Control

Edge is the area between the outer internet and the inner network of an organization. It is primarily managed through firewall rules.

Access control manages wherever the user is, whether outside or inside the network.
Access can be based on many rules like users, groups, location, application, etc.
These rules are often changed or revoked.

## Posture Assessment

This is an assessment done any every device to check if it is up to the latest standards of security technologies. A good time to perform a posture assessment is when a device is first connects to the network or logs in to the network remotely. 

## Health Checks / Posture Assessment 

**Persistent agents** are permanently installed onto the system. These agents can run at anytime and not just during the login process and they can monitor any file and any application running on that system.

**Dissolvable agents** only run during the posture assessment and they don't require installation.

Another type of security control is an **Agentless Network Access Control (Agentless NAC)**. This type of agent is integrated with the Active Directory and it only runs when users login or logout of the AD database. 

## Failing the Security Assessment

Devices that fail the security assessment should be quarantined and be given enough network access to fix the issue. Once resolved, the device should be assessed again. 

## Endpoint Detection and Response (EDR)

EDR shifts from signatures only to behavioral analysis, machine learning, and process monitoring. It is a lightweight agent on the endpoint.

EDR takes this one step further than antiviruses and anti-malwares by providing root-cause analysis. 

EDR can automatically respond to incidents. If a virus is detected on a device, the EDR will isolate the device, quarantine the thread, rollback to a previous config, etc. 

## Extended Detection and Response (XDR)

This is an evolution of EDR 

