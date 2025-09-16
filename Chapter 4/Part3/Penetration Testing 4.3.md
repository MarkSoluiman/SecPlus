
---

Pen-testing is to simulate a real attack on a system or an application to find and report vulnerabilities to fix them before a real attack can happen. 

## Rules of Engagement

This is an important document that defines purpose and scope of the pen-testing. Makes everyone aware of the test parameters. 

These rules might contain the type of testing and schedule. For example, on-site physical breach, internal test, external test, etc. The pen-test should start at what time? normal working hours, after 6 PM only, etc.

The rules might contain these rules as well: IP address range, emergency contacts, how to handle sensitive information, in-scope and out-of-scope devices or applications.

## Exploiting Vulnerabilities

During the exploiting of found vulnerabilities process, some actions that pen-testers can perform can bring the whole system down like performing a buffer overflow attack in order to gain privilege escalation. 

## The Process

After finding a vulnerability, the first step is to exploit it to get foothold into the system. The next step is lateral movement where the pen-tests moves from system to system.

Pen-testers can put a backdoor in the exploited system to get access later. This is called persistence. 

Pen-testers can pivot from the outer device that they have gained access to to one of the devices in the inner network. This is called pivoting. 