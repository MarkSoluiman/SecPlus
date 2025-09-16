
---

## Security Log Files

These files contain detailed security-related information like: blocked and allowed traffic flow, exploit attempts, blocked URL categories, DNS sinkhole traffic,etc.

## Firewall Logs

These logs have the traffic flow information through the firewall: source/destination IP, port numbers, disposition (accepted or blocked),etc.

## Application Logs

These logs are specific to that application that was created by. For example, Windows Event Viewer logs, Linux/ macOS /var/log directory. 

## Endpoint Logs

Logs can contain policy changes, logon events, system events, processes, account management , etc. This all can be stored in a SIEM. 

## IPS/IDS Logs

These logs are usually integrated into an NGFW. Logs contain information about predefined vulnerabilities like known OS vulnerabilities  and generic security events. The logs also contain common data points like timestamps, type of class of attack, source and destination of IP and ports, etc.

## Network Logs

These logs are created by switches, routers, access points, VPN concentrators, and other infrastructure devices. 

They contain routing updates, authentication issues, network security issues, etc.

## Metadata

Data that describes other data sources. For example, emails contain header details, sending servers, destination address, etc.   

## Automated Reports

Most SIEMs include a report generator or they can be created by third-party report generators. 
