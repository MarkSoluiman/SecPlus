
---

## Intrusion Prevention System (IPS)

This is a system that watches over the network traffic. The IPS can immediately block intrusions like exploits against OS, applications, etc. It can also prevent attacks such as buffer overflow, or SQLi. 

IPS is different than an intrusion detection system (IDS). IPS can detect and prevent attacks while IDS can only detect them.

## Failure modes

Eventually, security devices will fail. This such a device was inline, one of these scenarios will happen to the network traffic:
- **Fail-open**: when a system fails, data continues to flow.
- **Fail-closed**: when a system fails, data doesn't flow.

## Device Connections

The IPS can be connected to the network in two ways or two modes: active monitoring or passive monitoring.

In active monitoring, the IPS will get all of the network traffic pass through it before making a decision of passing the traffic or blocking it.

In passive monitoring, the network traffic will go to the devices connected and the IPS will get a copy of the network traffic that passed through the network. In this case, the IPS will be limited in its ability to block malicious traffic. This design is called an IDS design. The copy of the traffic is communicated to the IPS using the port, and in this case, the port will be refereed to as a **port mirror or switch port analyzer (SPAN)**. 