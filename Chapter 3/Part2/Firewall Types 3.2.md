
---

## Network-Based Firewalls 

Filter traffic by port number or application. The traditional network-base firewalls can only filter traffic based on transport layer (OSI layer 4) like TCP port or a UDP port. However, **Next-Gen Firewalls (NGFW)** can manage traffic based on OSI layer 7 so they can allow or disallow traffic based on the application being use over the network. Firewalls can encrypt traffic between sites and act as VPN.

Most firewalls can be layer 3 devices (routers). They are commonly sit on the edge of the network and control the traffic flows between the internal network and the external network. They often can provide NAT functionality and other types of routing protocols. 

## UTM / All-in-one security appliance

Unified Threat Management (UTM) / Web security gateway. These are old firewalls.

They have multiple features:
- URL filter/ Content inspection
- Malware inspection
- Spam filter
- Router, Switch
- Firewall
- IDS/IPS
- Bandwidth shaper
- VPN endpoint

## Next-Gen Firewall (NGFW)

They operate at the OSI application layer, so they are able to make forwarding decisions. They can be also called: Application layer gateway, stateful multilayer inspection, or Deep packet inspection.

They require some advanced decodes. Every packet must be analyzed and categorized before a security decision is determined.

They control traffic flows based on the application. They act as IPS, they identify the application and apply application-specific vulnerability signature to the traffic.

They can be used to filter the content, for example, they can prevent users from visiting gambling websites or some social media websites.

## Web Application Firewall (WAF)

This is not like a normal firewall. It allows or denies based on expected input like SQLi 