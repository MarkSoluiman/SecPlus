
---

A public key certificate binds a public key with a digital signature and other details about the key holder. 

PKI uses certificate authorities for additional trust. 

Certificate creation can be built into the OS. For example, part of Windows Domain services or many third party options. 

The standard format for a digital certificate is **X.509**. The certificate will include:
- Serial number.
- Version.
- Signature algorithm.
- Issuer.
- Name of the cert holder.
- Public key.
- Extensions.
- And more...


## Root of Trust

Root of trust is when we trust a third party because something that we have or control trusts this third party entity. For example, if we are visiting a website for the first time, we can trust this website because our web browser trusts this website.

Our web browser trusts the website because a certificate authority has digitally signed the website certificate. Since our web browser trusts the CA, and we trust our web browser, then we can trust the website. 

## Scenario (Certificate Signing Requests)

We will purchase a certificate signature for our website to be trusted by web browsers. 

On our end as applicants, we will use our public key with our identifying information (name of our organization, what server the website will be connected to, etc), to create a **certificate signing request (CSR)**. The CSR will be sent to the CA. 

On the CA end, they will verify the information in the CSR. After that, the CA will digitally sign the certificate with their private key. 

---
## Internal CA

In many medium-to-large organizations, they prefer to create their own certificates using CA software to create their own CA public certificate to be installed within the organizations devices. This is done for security and privacy reasons. 

Windows Certificate Services, and OpenCA are examples of CA softwares  that can be used in these cases. 

## Wildcard Certificates

This can also referred to as **Subject Alternative Name (SAN)**. This allows a certificate to support many different domains. For example, if we have this SAN: \*.cyber.com. This will cover for these domains: `www.cyber.com`, support.cyber.com, more-info.cyber.com, etc. 

## Key Revocation

If we want to revoke a certificate, we can use a **Certificate Revocation List (CRL)**. 
This is maintained by the CA. 

This might be needed for multiple of reasons. 

A CVE that happened in 2014 called **Heartbleed** discovered a flaw in OpenSSL logic. 
OpenSSL was leaking the private keys of websites or other sensitive data like credit cards info. 

OpenSSL was patched, every web server certificate was replaced. Older certificates were moved to the CRL.

## OCSP

**Online Certificate Status Protocol (OCSP).** This protocol states that every certificate holder verify their own status. The status information is stored on the certificate holder's server.

OCSP status is **stabled** into the SSL/TLS handshake. The OCSP is digitally signed by the CA to validate the status of the certificate.





