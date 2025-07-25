
---

This is another form of on-path attack. The victim will send their credentials to the server that they want to authenticate to. However, the attacker will get this request as well. The attacker will then re-send this request posing as the victim having access to the server.

This attack is also called Pass the has, since the attacker will get the password hashed. 

To avoid this attack, the user should use salt or encryption. Using a session ID with the password hash will create a unique authentication hash each time. 

## Browser Cookies and Session IDs

Cookies have lots of information about the user used for tacking, personalization, and session management.  Session IDs are often stored in the cookie. If the attacker got access to the cookie, they will be able to pose as the victim without providing any credentials. This is also called **Session Hijacking**. 

## Prevent Session Hijacking

Encryption end-to-end is the solution to prevent such attacks.



