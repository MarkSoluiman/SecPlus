
---

## AAA Framework

### Identification

- This is who you claim to be.
- Usually your username.
### Authentication

- Prove you are who you say you are.
- Password and other authentication factors.
### Authorization

- What you have access to or what you can do.
### Accounting

- Resources used, login time, data sent and received, logout.


## Scenario (Authenticating People)

When a client wants to authenticate with an internal server within an organization's network, the client sends their login details to the Firewall / VPN Concentrator. The concentrator doesn't have any info about users. The concentrator sends the login info to an AAA Server. The server will validate the credentials and sends back a response to the concentrator allowing or denying access to the user.

---

## Certificate Authentication

An organization has a trusted Certificate Authority (CA). Most organizations maintain their own CAs.

The organization creates a certificate for a device and digitally signs the certificate with the organization's CA.

The certificate can now be included on a device as an authentication factor. The CA's digital signature is used to validate the certificate.

## Authorization Models

The user or device has now authenticated. To what do they now have access?

Uses and services have access to data and applications. The challenge is to how to create this relationship in a form that's able to easily scale for tens, hundreds or thousands of users. To achieve this, we put an authorization model between the users and services and the data and applications. The model is defined by roles, organizations, attributes, etc.


## Scenario (No Authorization Model)

If we have a user that can access resources but without an authorization model.  This has some issues like difficulty to understand why an authorization may exist and this doesn't scale.

Manually giving access to multiple of users to multiple of different resources is pretty difficult to achieve.

---

To solve this problem, we add an authorization model or an abstraction. This creates a clear relationship between the user and the resource.

