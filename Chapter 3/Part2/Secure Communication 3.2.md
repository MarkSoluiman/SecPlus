
---

## VPN

They encrypt data traversing a public network.

VPN uses a concentrator that acts as a connection point for users who are using the VPN. This is often integrated into a firewall.

VPN  can be a specialized hardware or a software-based solution or even integrated into the OS.

## Encrypted Tunnel

An original packet will have an IP Header and raw data. We need to encrypt the IP Header and data to send them across the public internet. Since the IP Header has info on where the data originated and where it is going, we need to add new headers. IPsec Header and an IPsec Trailer will be added and to point the entire packet to the right IPsec concentrator, a new IP header will be added as well. 

## SSL/TLS VPN (Secure Sockets Layer /Transport Layer Security)


SSL/TLS uses port tcp/443.

It is used usually in remote access communication. There are no requirements for digital certificates or share passwords (like IPsec).

Can be run from a browser or from a (usually light) VPN client.

## Site-to-Site IPsec VPN

Some organizations will build an encrypted tunnel between remote locations so everyone at a remote site will be able to communicate back to the corporate network over an encrypted channel that is provided automatically through firewalls acting as VPN concentrators.

## SD-WAN

**Software Defined Networking in a Wide Area Network**. This was specifically designed to address some of the challenges we have with connecting to cloud-based applications.

Before the cloud, we used to have every service in one place that has all of the servers hosting the services and the other remote sites have to connect remotely to these servers. 

But now, we can build out dynamic networks that are able to communicate to our web-based applications hosted on the cloud by using SD-WAN.

## Secure Access Service Edge (SASE)

They are the next-gen VPNs. They allow us to connect securely to the cloud from anywhere we want. It relies on Network as a Service, and Security as a Service.