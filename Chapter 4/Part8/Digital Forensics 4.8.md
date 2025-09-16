
---

## Legal Hold

A **legal hold** is a process used to preserve information that may be relevant to a legal case. It’s usually started by a lawyer or legal authority, who sends a document describing what data must be kept and in what quantity.

This request is sent to a **data custodian**, the person responsible for the data. The custodian reviews the legal hold, determines where the data is, and begins collecting it.

Most organizations have a dedicated storage area for **ESI** (Electronically Stored Information). The required data is copied into this secure repository. However, collection isn’t always as simple as copying files — data might be part of a larger database or stored in a format that must be converted before saving. For example, emails may be stored in a proprietary format that needs to be converted to plain text.

Because this data may be used in court, it must be **preserved exactly as it was** (pristine condition). This means having processes in place to maintain integrity from the moment it’s collected.

## Chain of Custody

Multiple people may need access to the data, so a **chain of custody** is used to record who accessed it and when. In the digital world, this is done with hashes and digital signatures. This ensures that the data you examine later is identical to the original.

Sometimes you know exactly what needs to be collected, but in larger security incidents you may need to gather many types of data:

- Data on disks, in memory, or in firmware.
- Files from multiple systems, servers, or network devices.
- Firewall logs or virtual machine snapshots.
- Hidden data in log files, recycle bins, browser bookmarks, saved passwords, or temporary files.

## Acquisition 


Acquisition of data is the first step. Data may be obtained from different sources like hard disk, RAM, firmware, OS files, servers, network data, firewall logs, etc.

For virtual systems, a snapshot of the the VM should be obtained which has all of the files and settings in the system. 

## Reporting

**Documentation is essential.** You must record how the data was acquired in detail so that anyone reviewing it later can verify its authenticity. Reports should include:
1. A summary of the event and why the data was collected
2. A step-by-step record of the acquisition process
3. Any integrity checks performed

After data is collected, you may be asked to provide a **factual analysis** describing its structure and how it relates to the case. If it’s part of a security investigation, you might also include conclusions about what happened.

## Preservation

Proper **storage and preservation** is critical. Always work on copies, not the original, to prevent accidental changes. This is especially important for mobile devices, which could be remotely wiped. Data is often collected while systems are still running to avoid encryption locks that activate when powered off.

## E-Discovery

This is the process of collecting, preparing, reviewing, interpreting, and producing electronic documents. This only has to do with collecting of data and providing it to a third-party which will do the analysis step.





