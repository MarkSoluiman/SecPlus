
---

## Mail Gateway

To prevent email spoofing, multiple security layers are configured. First one is mail gateway.

It evaluates the source of inbound email messages. If an organization has a mail gateway server on premises, the server will be in a screened subnet as the server will have to communicate directly with the outer internet. Mail gateway can be also a third party solution on the cloud.

## Sender Policy Framework (SPF)

 In this protocol, the sender configures a list of all servers authorized to send emails for a domain. A list of authorized mail servers are added to a DNS TXT record which will be used by the receiving mail servers to check if incoming mail really did come from an authorized host.

## Domain Keys Identified Mail (DKIM)

This is a signature added to outgoing mails for the receiving mail servers to identify the author of the mails. The public key is in the DKIM TXT record.

## Domain-based Message Authentication, Reporting,  and Conformance (DMARC)

This is an extension of SPA and DKIM in case of the receiving mail servers didn't properly validate the SPA and DKIM. 

The domain owner decide what receiving email servers should do with emails not validated with SPF and DKIM. That policy is written into a DNS TXT record. Actions can include: accept all, send to spam, or reject the email. 

DMARC can also used to send a report to the email administrator informing them of the number of accepted and rejected emails.




