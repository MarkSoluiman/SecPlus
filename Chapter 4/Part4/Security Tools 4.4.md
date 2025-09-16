
---

## Security Content Automation Protocol (SCAP)

It is a protocol maintained by NIST. It allows tools to identify and act on the same criteria:
- Validate the security configuration.
- Confirm patch installs.
- Scan for a security breach.

If a NGFW, an IP, and a vulnerability scanner found a vulnerability, SCAP will allow them to identify the same exact vulnerability despite the difference in each of these systems.

## Using SCAP

SCAP content can be shared between tools. Focused on configuration compliance to easily detect applications with known vulnerabilities.

This is especially useful in large environments where many different OSs and applications exist and communicate with each other.

This specification standard enables automation between different tools. 

Automating types:
- Ongoing monitoring.
- Notification and alerting.
- Remediation of non-compliant systems. 

## Bechmarks

Benchmarks is applying security best-practices to a system/software.

For example, a benchmark for a mobile device will include: disable screenshots, disable screen recordings, prevent voice calls when locked, force encryption backup, etc. 

## Agents/ Agentless

Agents are softwares on systems that always check if the device is in compliance. 
An on-demand check can be performed on a device. This is called agentless device.

## Data Loss Prevention (DLP)

If organizations would like to stop sensitive data from being transferred across their network, then they should use data loss prevention. DLP is used to look for and block any type of data that organizations don't want running on their network like social security numbers, credit cards numbers, medical information, etc. 

## Simple Network Management Protocol (SNMP)

This is a database of data called **Management Information Base (MIB)**. Inside the MIB are series of metrics that are being monitored and instead of spelling out the individual name of each metric, **object identifiers** are used instead or **OIDs** which are a group of numbers. SNMP uses port UDP/161.

SNMP requests statistics from devices like servers, firewalls, workstations, routers, etc.

SNMP can be used to poll devices for info at fixed intervals to create historical performance graphs.

## SNMP Traps

SNMP traps can be used instead of the fixed polling way. SNMP traps can be configured on the monitoring device communicating over UPD/162. 

An example of a SNMP trap is setting a threshold for alerts. For example, if the number of CRC errors increases by 5, send a trap. 

## NetFlow

This is a more complex system than SNMP which gathers traffic statistics from all traffic flows.

NetFlow commonly works by first having a probe to compile this information for the traffic flow. This NetFlow probe may be built into the software that's included with a switch or router, or it may be included as a separate external probe. These probes may connect to the network with a monitoring port from a switch like a switched port analyzer or SPAN, or there may be a physical tap on the network that's providing the NetFlow probe with a copy of all network traffic flows.

These probes will then collect information and send a copy of those metrics down to a NetFlow collector, which can then be used to create reports and other details about the application traffic flows on the network. 