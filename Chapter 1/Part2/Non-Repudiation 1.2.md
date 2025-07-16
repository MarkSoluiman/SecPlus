
---

Non-repudiation means that the receiver of the message can verify the message came from the sender. For example, when signing a contract, the signature adds non-repudiation confirming that the person really signed the contract and others can see the signature.

In the cyber security field, this acts as a proof of integrity and a proof of origin, with high assurance of authenticity.

**Proof of integrity means the verification of data didn't change**

To achieve integrity, we can use a hash. If the data changes, the hash changes. However, this doesn't necessarily associate data with an individual.

Proof of origin consists of three principles: Integrity, Authentication, and Non-repudiation.

Integrity is proving that the message was not changed. Authentication is proving the source of the message. Non-repudiation is making sure the signature is not fake.

For this to happen, we use public and private key for encryption and decryption.

### Scenario: (Verifying a digital signature)

Alice is trying to send a message to Bob saying: "Hello Bob". Alice will first use a hashing algorithm to get a **hash text** of the message. Then, Alice will use his **Private key** to encrypt the hash text that he got creating the **digital signature**. Finally, Alice will send the plain text message along side the digital signature to Bob. 

When Bob receives the message with the digital signature, Bob will use Alice's **Public Key** to decrypt the digital signature. This will give Bob the hash text of the plain text message. Bob can perform the hashing algorithm on the plain text message and compare the two hashes he gets. Same hashes means that the message wasn't changed and the author of the message is indeed Alice.