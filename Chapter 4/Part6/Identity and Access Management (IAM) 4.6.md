
---

Every entity (human or a device) gets a digital identity. An entity only gets access to what they need. Entities must prove they are who they claim to be. Entity's resource access must be tracked. 

## Provisioning/de-Provisioning User Accounts

This is the creation and deletion of a user account process. This is the core of the IAM process as it acts as the initial checkpoint to limit access. Not every user gets administrator access.

## Permission Assignments

Each entity gets limited permissions. Just enough to do their job. Group assignments are common. 

Storage and files can be private to that user. Even if another person is using the same computer.

No privileged access to the OS for regular users.

## Identity Proofing

The IAM process should confirm who the user is. This is called **resolution**.

Then, the IAM process will gather information from the user (password, security questions, etc). This is called **Validation**. 

Some IAM will require additional details to verify the user. This is called **Verification/Attestation**. This can be done by passport, in-person meeting, etc. Automated verification is also an option. 

## Single Sign-on (SSO)

This is the process where the user would login one time to the network, and from that point forward, the user gains access to all of the resources that they might need. This access is usually limited by time. 

## LDAP (Lightweight Directory Access Protocol)

Protocol for reading and writing directories over an IP network. 

LDAP is the protocol used to query and update an X.500 directory. Used in Windows AD, Apple OpenDirectory, Novell eDirectory, etc.

## X.500 Distinguished Names

Most specific attribute is listed first

| Attribute | Field               | Usage                                                     |
| --------- | ------------------- | --------------------------------------------------------- |
| CN        | Common Name         | Identifies the person or object                           |
| OU        | Organizational Unit | A unit or department within the organization              |
| O         | Organization        | The name of the organization                              |
| L         | Locality            | Usually a city or area                                    |
| ST        | State               | A state, province, or county within a country             |
| C         | Country             | The country's 2-character ISO code (such as c=US or c=GB) |
| DC        | Domain Component    | Components of the object's domain                         |
 

## Security Assertion Markup Language (SAML)

Open standard for authentication and authorization. It is the bridge between the identity provider (IdP) and the service provider (SP). SAML what makes SSO possible.

SAML is not designed to be used for mobile apps.

## The SAML Authentication Flow

When the browser of the user wants to access an application URL, the resource server will respond with a signed/encrypted SAML request, which redirects the user to the authentication server. The user will need to login. After the user is authenticated, the authorization server will send a SAML token back to the user which they can present to the resource server to gain access. 

## OAuth 

This is an authorization framework. Determines what resources a user will be able to access. 

Since this is not an authentication framework, OpenID is used in conjunction with OAuth to combine both the authentication and the authorization. 

## Federation

Provide network access to resources through third-parties. Used in authentication and authorization between two organizations.

Famous example is when a user wants to use an application. Instead of creating an account in the application, the user will use their Google account to use the application.

