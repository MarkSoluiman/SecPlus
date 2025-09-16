
---

Code injection is when an attacker add their own information into a data stream due to bad programming. 

SQL injection is when an attacker puts their own SQL request into a text input field like username or password. 

An example of SQLi:

`Select * From users Where name= `'Mark' OR '1' ='1';`

This will always return true since 1=1. If this logic was using in validation of user's credentials, this will give an attacker the access to  the user's account without providing a password.

Other malicious actions can be performed as well.