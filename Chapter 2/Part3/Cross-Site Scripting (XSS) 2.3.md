
---

Cross-site scripting commonly performed by JavaScript.

An attacker can provide their victim with a link to a trusted website. However, the website will have a malicious link which has been prepared previously by the attacker. Once the victim visits the website, the malicious script will be executed. This script can steal information from the victim and shows it to the attacker like session cookies, etc. 

## Non-Persistent (Reflected) XSS Attack

This happens when websites allow scripts to run in user input, similar to SQLi.
Attackers can email a link that takes advantage of this vulnerability. This will run a script that sends credentials, session IDs, or cookies to the attacker.

## Persistent (Stored) XSS Attack 


Attackers can post a message to a social network with a malicious link that contains a payload. 

Everyone gets the payload, hence the name persistent.   