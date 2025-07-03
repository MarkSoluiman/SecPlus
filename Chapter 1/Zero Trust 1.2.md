
---

Zero trust is about securing every layer within the network. That covers every device, process, and every person. That means nothing is inherently trusted which is applied by multiple methods: Multi-factor authentication, encryption, system permissions, additional firewalls, monitoring and analytics, etc. 

We can split the network into segments called **functional planes**.

### Data Plane

- Process the frames, packets, and network data.
- Processing, forwarding, trunking, encrypting, NAT.

### Control Plane

- Manages the actions of the data plane.
- Define policies and rules.
- Determines how packets should be forwarded.
- Routing tables, session tables, NAT tables.

## Controlling Trust

### Adaptive Identity

- Consider the source and the requested resources.
- Multiple risk indicators: relationship to the organization, physical location, type of connection, IP address, etc.
- Make the authentication stronger if needed.
### Threat Scope Reduction

- Decrease the number of possible entry points.
### Policy-Driven Access Control

- Combine the adaptive identity with a predefined set of rules.


Since security is more than one-to-one relationship, security zones are needed to make it easy to manage users when they try to access different resources. This is done by determining where the user is coming from and where they are going:
- Trusted, untrusted.
- Internal network, external network.
- VPN 1, VPN 5, VPN 11.
- Marketing, IT, Accounting, Human Resources.

Using the zones may be enough by itself to deny access. For example, **untrusted** or **trusted** zone traffic.

Some zones are implicitly trusted. For example, **trusted** or **internal** zone traffic.

## Policy Enforcement Point 

A gate keep must be standing as a security point between the system or the subject (end users, applications, devices). and the resources. Here, comes the use of policy enforcement point (PEP).

After that comes the **Policy Decision Point** (PDP) which contains **Policy Engine** and **Policy Administrator**. The policy engine evaluates each access decision based on policy and other information sources: Grant, deny, or revoke.

The policy administrator then communicates with the policy enforcement point and provides it with the decision coming from the policy decision point. Access tokens may be created by the policy administrator to give back to the policy enforcement point.