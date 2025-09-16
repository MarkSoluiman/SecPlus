
---

## Input Validation

Document all input methods like forms, fields, and type.

Check and correct all input (normalization). For example, a zip code should only be X characters long with a letter in the X column.

Fuzzers will find vulnerabilities easier. 

## Secure Cookies

Cookies may have personal information about the user. Websites should use secure cookies which means browsers will only end cookies over HTTPS.

## Static Code Analyzers 

**Static Application Security Testing (SAST)**. This can find many security vulnerabilities like buffer overflows, database injections, etc.

Not everything can be identified through analysis.

Still have to verify each finding. False positives are an issue.

## Sandboxing

This means when the application begins executing, it only has access to the data necessary for that application to work.

Sandboxing commonly used during development.

## Application Security Monitoring

Many developers will build monitoring into the applications that they are creating. This allows them to monitor the use of the application and any secure concerns that may arise. For example, they can see if anyone is trying to perform any type of SQLi attacks or take advantage of any vulnerability that exist. 

The activities will be saved in logs to be used for security analyses of the application.

