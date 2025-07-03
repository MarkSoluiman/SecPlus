
---

It is the process of making something unclear or much harder to understand.

 Obfuscation can be reversed if the way is known. 

One example of obfuscation is **steganography**, which is hiding information inside of an image. 

A common steganography technique is to embed messages in TCP packets. 

## Tokenization

This is another technique of obfuscation which is to replace sensitive data with a non-sensitive placeholder. For example, if we have a credit card number, we can replace the number with a random number but behind the scene we can match the two numbers together. 


## Scenario (Tokenization)

A user registers a credit card on their phone. The card is registered with the token service server. The token service server provides a token instead of the real credit card number.
The user can use their phone at a store checkout paying with their credit card using NFC. The phone will use the token that it got from the token service server. The merchant payment server will take this token then send it to the token service server. Finally, the token service server will match the token it got with the credit card info and send the response back to the merchant payment server. 

The token is only used once. The token service server will need to provide the user with a new token every time the user uses their credit card 
