
---

## The WPA2 PSK problem 

WPA2 has a PSK brute-force problem. 

The attackers listen to the four-way handshake to capture the hash. With the hash, attackers can brute force the pre-shared key (PSK).

## WPA3 and GCMP

A more secure wireless protocol is Wi-Fi Protected Access 3 (WPA3). Introduced in 2018.

**Galois/Counter Mode Protocol (GCMP)** is a block cipher mode. This is a stronger encryption than WPA2.

GCMP includes data confidentiality with AES and **Message Integrity Check (MIC)** with **Galois Message Authentication Code (GMAC).**

## SAE


WPA3 changes the PSK authentication process. It includes mutual authentication. Creates a shared session key without sending that key across the network. No more four-way handshakes, no hashes, not brute force attacks.

**Simultaneous Authentication of Equals (SAE)** which is a Diffie-Hellman derived key exchange with an authentication component. Everyone uses a different session key, even with the same PSK. The SAE included in the IEEE standards and might be refereed as the dragonfly handshake.

## Wireless Authentication Methods

There are usually two ways to connect to a wireless network. Providing the shared password or pre-shared key (PSK), or by centralized authentication (802.1X) protocol which is used in corporates and organizations. Users will be prompt to provide their usernames and passwords to access the network. Every user will use their own credentials to access the same network.

## Wireless Security Modes

Open system: No authentication password is required.

WPA3-Personal / WPA3-PSK: WPA2 or WPA3 with a pre-shared key. Everyone uses the same 256-bit key.

WPA3-Enterprise / WPA3-802.1X: Authenticates users individually with an authentication server like RADIUS.

## AAA Framework

The centralized authentication server is referred to as an AAA server. The AAA framework begins with identifying the person who is trying to connect to the network.

First comes authentication. The user must provide valid set of credentials to prove that they are who they are claiming to be.

Then authorization. Based on the authentication, the server determines what access should be given to this user. 

Finally, Accounting. This is a list of metrics associated with the login session. This can be the time the user logged in, how much data was sent and received and the time user logged out. 

## RADIUS (Remote Authentication Dial-in User Service)

 One of the most common AAA protocols. Supported on a wide variety of platforms and devices.

Every time a user connects to routers, switches, firewalls, or remote VPN access. RADIUS is involved in the authentication, authorization, and accounting procedure.   

