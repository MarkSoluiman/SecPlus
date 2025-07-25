
---

## Extensible Authentication Protocol (EAP) 


EAP is an authentication framework. Manufacturers can build their own EAP methods.

The most common integration of EAP is with 802.1X which is an IEE (**Institute of Electrical and Electronics Engineers**) standard that manages the authentication process for users and device onto a network.

## IEEE 802.1X

Port-based **Network Access Control (NAC)**. Users who connect to a port in a switch can't access until they authenticate. 

EAP and 802.1X used in conjunction with an authentication database like: RADIUS, LDAP, TACACS+, Kerberos, etc.

This process has three components: supplicant (the user), authenticator (device that provides access), and authentication server (validate the client credentials). 

The supplicant will first connect to the authenticator, but no access will be permitted to the user. Once the authenticator sees this initialization, it will send a message back to the supplicant asking for a login credentials. This is called an EAP request. The supplicant will send its username to the authenticator in a form of EAP response. The authenticator will send this response to the authentication server to see if the username exist in the database. Once the authentication server validates the username, it will ask the supplicant through the authenticator for their credentials. Once the supplicant provides the authentication server with valid credentials, the authentication server will reply with a successful login allowing the supplicant to have access to the network.  