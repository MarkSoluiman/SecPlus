
---


## Virus

A virus in a computer can reproduce itself through file systems or the network.

There are different types of viruses, like **program viruses** which is malicious code part of an application. **Boot sector viruses** run when a device is booted. **Script viruses** can be ran by the operating system or by a web browser or anything that can run scripts. **Macro viruses** which are common in Microsoft Office.

Another kind of viruses is a **fileless virus** which don't use any files stored in the operating system as they don't write any software or malicious code to the storage drives. They usually go undetected by anti-viruses softwares. These viruses operate in memory.

A common way to get infected with a fileless virus is to click on a malicious website link which will exploit some type of vulnerability to force the device to run a powershell/bash script that downloads the payload in RAM. These viruses usually add an auto-start to Registry to run whenever the users starts their device.

## Worms

Worms are malwares that can replicate them self's. Worms don't need any interaction from the users and they use the network to spread quickly. Firewalls and IDS/IPS can mitigate the spread of worms