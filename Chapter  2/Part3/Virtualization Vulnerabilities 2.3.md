
---

Virtual machines, just like physical machines, can be vulnerable to local privilege escalations, command injection, information disclosure, etc. 

Attackers can escape the virtual machine that they are currently on and interact with other virtual machines in the same hypervisor (the software that controls virtualization). 

## Resource Reuse

Resources which are available to the hypervisor to allocate for virtual machines can intertwine. For example, if we a hypervisor that has access to 4GB of RAM while there are three VMs with 2GB of RAM each. The hypervisor will still be able to manage the available resources for the VMs.

In some cases, VMs will share its data with each other if no proper resources management settings were applied by the hypervisor.  