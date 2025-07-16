
---

Malware can be hidden inside of the memory of a device.

Memory contains running processes:
- DLLs (Dynamic Link Libraries).
- Threads.
- Buffers.
- Memory Management Functions.

Malware can run in its own process, or it can inject itself into a legitimate process.

Malware that has been injected in a process, can escape malware detection softwares and it will have access to the data in that process.

## DLL Injection

This is a Windows library containing code and data which many applications can use.

Attackers will inject a path to a malicious DLL. To do this, the attacker will put the path of the malicious DLL somewhere in the process. 