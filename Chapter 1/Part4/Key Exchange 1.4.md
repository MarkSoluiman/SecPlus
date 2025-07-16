
---

A logistical challenge is to share a decryption key across an insecure medium without physically transferring the key. 

One of the ways to exchange keys is **Out-of-band**. The key is not shared over the network, but rather it is shared by telephone, courier, in-person, etc. 

This is inconvenient way to share keys and it's rarely used. 

To solve this problem, the key shared is protected with additional encryption like using asymmetric encryption to deliver a symmetric key. 

## Real-Time Encryption/Decryption

When two parties are communicating with each other, they need to start a secure session to encrypt messages between each other. 
- The client encrypts a random (symmetric) key with a server's public key.
- The server decrypts this shared key and uses it to encrypt data.

Sessions keys are **ephemeral keys** which means they need to be changed often.

Another way to share keys is to use public and private key to create a symmetric key.

## Scenario (Symmetric Key from Asymmetric Keys)

Bob and Alice want to get the same symmetric key. Bob will use his private key  with Alice's public key to get the symmetric key. Alice on the other side will use her private key  with Bob's public key to get the symmetric key. Since Bob and Alice are using keys mathematically related, they both end up with the same symmetric key.

This is called **key exchange algorithm**.
