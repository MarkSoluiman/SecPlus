
---


Encrypting stored data is also called **Encryption at rest**. This is to protect data on storage devices. Full disks or volumes are entirely  encrypted using BitLocker or FileVault, etc. This can also be done on singles files or folders which is called **Encrypting File System (EFS)**. 

## Database Encryption 

**Transparent encryption** is when all the database information is encrypted using a symmetric key. 

**Record-level encryption** is to encrypt individual columns within tables of data and to use separate symmetric keys for each column.

## Transport Encryption 

This is to encrypt data while traversing the network. 

Encrypting in the application is done by browsers using HTTPS.

VPN encrypts all data transmitted over the network, regardless of the application. 

This can be done on a client-based VPN using SSL/TLS, or Site-to-site VPN using IPsec.

## Key Lengths

The larger the key used to decrypt the data, the harder it is to decrypt the data using brute-force. 128-bit or larger symmetric keys are common. 

## Key Stretching

Key stretching is making the key stronger by performing multiple processes. 
For example, if we have a password, we can hash the password then we hash the hash of the password for multiple times.


