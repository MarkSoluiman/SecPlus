
---

## Onsite vs. Offsite Backups

Onsite backups:
- No internet link required.
- Data is immediately available.
- Generally less expensive than off site.

Offsite backups:
- Transfer data over internet or WAN link.
- Data is available after a disaster.
- Restoration can be performed from anywhere.

## Frequency 

How often to backup, every week, day, or hour?

Some systems might not need very frequent backup as they don't change much over time.

## Encryption

Protect backup data using encryption. Everything on the backup media is unreadable and a recovery key is required to restore the data. 

## Snapshots

This is an instant backup of an entire system that saves the current configuration and data of a VM.

## Replication

An ongoing, almost real-time backup. Keeps data synchronized in multiple locations. 

## Journaling

Say a power goes out while writing data to storage. In this case, the stored data is probably corrupted. 

To avoid the corruption and loss of data, make a journal entry before writing to storage. After a journal is written, write the data to storage. 



