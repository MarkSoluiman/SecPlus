
---

There are two types of encryption methods.

## Symmetric Encryption

Symmetric encryption uses a single shared key between the sender and the receiver. The same key is used for encryption and decryption. If the key gets out, another key will be needed. The key used can be also called **shared secret**. This method doesn't scale very well with multiple users when it comes to distributing the key. However, it is very fast to use.

## Asymmetric Encryption

This way has two or more mathematically related keys. The public key is used to encrypt the data and the private key used to decrypt the data.


## Scenario (Asymmetric Encryption)

Bob is sending a message to Alice. Bob uses the public key of Alice to encrypt the message. Alice will use her private key to decrypt the message that Bob has sent.

---

## Key Escrow

This is a third party that manages private keys for multiple users. 