
---

## Trusted Platform Module (TPM)

This is a cryptographic hardware on a device that has a processor to generate random numbers and keys.

The TPM has persistent memory because it's using unique keys burned during manufacturing. 

It also has versatile memory to store keys, hardware configuration information and securely store BitLocker keys. 

TPM is also password protected so it's not prone to dictionary attacks.

## Hardware Security Module (HSM)

It's used in large environments. It's used as clusters of devices and should be used with Uninterruptible Power Supply (UPS).  They securely store thousands of cryptographic keys. 
They are high-end cryptographic hardware like a plugin card or separate hardware device.

They also can be equipped with cryptographic accelerators to speed up the process of encrypting and decrypting.

## Key Management System.

These are applications that store passwords and secrets within an organization.

## Secure Enclave

Often implemented as a hardware processor which is isolated from the main processor of the device.

It provides extensive security features, since it has its own boot ROM, monitors the system boot process, it can generate true random numbers, it can perform real-time memory encryption, it has root cryptographic keys, it performs AES encryption in hardware. 
