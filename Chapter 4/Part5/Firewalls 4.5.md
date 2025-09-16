
---

## Firewall Rules

Rules can be very general or very specific. Specific rules are usually at the top.

Most firewalls include a deny at the bottom. That means traffic will be denied by default unless specified otherwise. 

## Screened Subnet

A screened subnet commonly holds services and devices that need to be accessed by individuals on the internet. By putting these devices on ta screened subnet, all of the traffic from the internet will be directed to the screened subnet that doesn't contain any of the organization's sensitive data or devices.


## IPS Rules

These rules are usually integrated into an NGFW. Many of the rules built into an IPS use a signature. Some IPS can also detect anomalies in the traffic and don't just rely on signatures. The IPS may have been configured to recognize what a generic intrusion might look like such as a database injection.

