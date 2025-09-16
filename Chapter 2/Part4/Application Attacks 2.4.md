
---

We have touched on different types of application attacks such as: Buffer overflows, code injection, replay attack, privilege escalation, etc.

## Mitigating Privilege Escalation

Patch vulnerabilities. Update anti-virus/anti-malware software. Data execution prevention (only data in executable areas can run). Address space layout randomization, this to prevent a buffer overrun at a know memory address.

## Cross-Site Request Forgery

This is also called One-click attack, session riding, XSRF, CSRF (sea surf).

This attack takes advantage of the trust that a web application has for the user.
The website trusts the user's browser. Requests are made without the user's consent or knowledge. To prevent such attacks, websites need to use cryptographic token to prevent forgery.

## Scenario (Cross-Site Request Forgery)

An attacker creates a funds transfer request to a bank web server. The attacker sends this request to the victim as a hyperlink via email. That user may already be logged into the website. The victim then clicks on the link and unknowingly sends the transfer request to the bank website. The bank validates the transfer and sends the victim's funds to the attacker.

## Directory Traversal 

This is also called as path traversal. This allows the attacker to read files from a web server that are outside of the website's file directory. 
