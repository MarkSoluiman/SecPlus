
---

This is also called Man-In-The-Middle attack.

The attacker redirects the traffic to them then passes it on to the destination. 
The victim never knows their traffic was redirected.

Another type of on-path attack is ARP poisoning. The attacker needs to be in the same network. 

## Scenario (ARP Poisoning)

A victim tries to communicate with a router that has an IP address and a MAC address. The victim's device will send an ARP request to the router to know the router's MAC address. The device will ask: "For the device that has this IP address:192.x.x.x, what is your MAC address?". The router that matches that IP address will respond back with:"I have this IP address, here is my MAC address.".
The victim's device will then save the MAC address in ARP cache.

Since the attacker is in the same network, they know the IP address of the router and the victim's device. The attacker will send an ARP response claiming that they have the IP address that the victim asked for but it will change the MAC address to match their device. Now, the victim will communicate with the attacker's device instead of the router. 

## On-Path Browser Attack

This is a malware within the victim's device that sends everything the victim does on their browser to the attacker. 