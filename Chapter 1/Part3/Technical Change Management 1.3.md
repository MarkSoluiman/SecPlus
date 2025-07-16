
---

Technical change is about the **how** to change it .

## Allow List / Deny List

Any application can be dangerous. An application might have vulnerabilities, Trojan horses, malware, etc.

Security policy can control app execution. A security policy that is following an allow list, will only allow applications listed and block anything else. This is more restricted (Deny as default).

A security policy that is following a deny list, will deny listed applications and allow anything else. This is less restricted (Allow as default).

## Restricted Activities

The scope of a change is important. Defines exactly which components are covered. 
A change approval isn't a permission to make any change. The change approval must be very specific. 
The scope may need to be expanded during the change window. It is impossible to prepare for all possible outcomes.
The change management process determines the next steps. There are processes in place to make the change successful. 

## Downtime

Services will eventually be unavailable. Usually scheduled during non-production hours. 
If possible, prevent any downtime. This can be done by switching to secondary system, upgrade the primary, then switch back.

Minimize any downtime events. The process should be as automated as possible. Switch back to secondary if issues appear. Should be part of the backup plan.
Notify others by sending emails or calendar updates.

## Dependencies

To complete A, B must be completed. Likewise, a service will not start without the other active services. An application requires a specific library version.

Sometimes, modifying one component require changing or restarting other components which can be challenging to manage.

Dependencies may occur across systems. For example, firewall needs to be updated. In this case, the code of the firewall needs to be updated first then the firewall management software can be updated next.

## Documentation 

It can be challenging to keep up with changes. Documentation can be outdated very quickly. Documentation is required with the change management process.

Updating diagrams comes when modifications to network configurations happen.

Updating policies/procedures comes when a adding new systems happen.
 
## Version Control 

Version control allows the tracking of changes to files or configuration data over time. Easily revert to a previous setting.
