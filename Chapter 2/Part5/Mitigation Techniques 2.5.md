
---

## Patching

Always run the most recent patches from the OS/ application provider to mitigate vulnerabilities and exploits. 

## Encryption

It is good practice to encrypt files on OS. This is called file level encryption and in Windows is called **Encrypting File System (EFS)**. A higher level than that is to encrypt the whole disk. This is called **Full Disk Encryption (FDE)**.  Some apps encrypt data used by them. 

## Monitoring

Monitors can be built-in sensors, separate devices, integrated into servers, switches, routers, firewalls, etc. 

All of these monitors produce logs of different events. To collect all of these logs in one place for easier access and further analyses, a **Security Information and Event Manager (SIEM)** is used. 

## Least Privilege

Rights and permissions should be set to the bare minimum. Users only get exactly what's needed to complete their objective. All user accounts must be limited. Applications should run with minimal privileges. 

## Configuration Enforcement

Perform a posture assessment each time a device connects to the network. It checks if the system is running the latest version of OS, If the latest patches are installed, if the firewall/EDR is up to date and check for other security features. 

If the system is out of compliance, it might get quarantined in a private VLAN with limited access.

