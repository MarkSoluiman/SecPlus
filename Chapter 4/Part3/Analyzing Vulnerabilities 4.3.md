
---

## Dealing With False Information

False positives is when a vulnerability is identified but it doesn't really exist. These are different than the low-severity vulnerabilities. These vulnerabilities are legit but can be dealt with later.

A false negative is the opposite. When a vulnerability exists but goes undetected.

## Common Vulnerability Scoring System (CVSS)

A list of known vulnerabilities can be found in a database online:`www.nvd.nist.gov`
It is synchronized with the CVE list.

## Vulnerability Classification

Vulnerabilities scans can scan for different types of vulnerabilities like application vulnerabilities, web application vulnerabilities, network vulnerabilities.

## Exposure Factor

Loss of value or business activity if the vulnerability is exploited. Usually expressed as a percentage. For example, if a small DDoS attack may limit access to a service half the time, it has 50% exposure factor.

## Environmental Variables

What type of environment is associated with this vulnerability? Internal server, public cloud, test lab, etc. 

If a database server in the public cloud and a device in an isolated test lab are vulnerable, the database has higher priority than the isolated device.

## Risk Tolerance


This is the amount of risk acceptable to a n organization because it is impractical to remove all risk. 

It would be ideal if organizations can immediately apply patches to systems. However, proper testing need to be done first before applying these patches. While going through the testing phase, the unpatched systems are still vulnerable, so the organization need to decide how much time they are willing to perform testing for.
 
