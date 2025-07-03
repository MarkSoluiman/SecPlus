
---

## Collision 

Hash functions take input of any size and always produce the same length output. 

The hash should be unique, different inputs should  never create the same hash. If they do, it's a collision.

For example, MD5 hashing algorithm has a collision problem and it shouldn't be used. 

Hashing algorithms used in verifying downloaded files. Compare the downloaded file's hash with the hash posted.

Hashes are also used when it comes to storing passwords. 

## Salt

Salt is random data added to a password when hashing. Every users gets their own random salt. That means if multiple users provided the same password, they will end up with different hashes for their passwords.

Rainbow tables don't work with salted hashes.

## Digital Signatures 

Digital signatures prove the message was not changed. Prove the source of the message. Make sure the signature is not fake.

The user will use their private key to create the digital signature. When that signature is sent to another party, they will be able to verify the signature using the public key of the signer. 
