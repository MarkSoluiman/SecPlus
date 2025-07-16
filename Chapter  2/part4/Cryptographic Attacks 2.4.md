
---

## Birthday Attack

This is also called hash collision. Some times, two different strings will result in the exact same hash. This is done by brute force.

To prevent this type of attacks, a large hash output size should be used. 

## Downgrade Attack

Downgrade attack happens when a system is using a secure encryption but the implementation is not secure.

SSL stripping is a from of such an attack. This combines an on-path attack with a downgrade attack. It is difficult to implement. The attacker has to be in the middle of the connection between the victim and the server. When the victim sends HTTPS request to the server, the server will respond back but the attacker will capture the response. The attacker will then send this response back but with out the encryption. If the user provided sensitive information, the attacker will be able to see it. 