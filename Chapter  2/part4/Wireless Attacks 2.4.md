
---

## 802.11 Management Frames 2.4

These frames are important for the wireless connection to work. They determine how to find access points, manage Quality of Service  (QoS), associate/disassociate with an access point, etc.

Original wireless standards didn't add protection for management frames. The frames were sent in clear, no authentication or validation. 

This protocol is vulnerable to deauthentication attacks where the attacker can send deauth packets to the victim's device to disconnect the device from the wireless network.

This vulnerability has been patched in the 802.11ac protocol. Now, the disassociate, deauthenticate, channel switch announcements, etc are not encrypted. However, beacons, probes, authentication, and association are not encrypted. 

## Radio Frequency (RF) Jamming

This is a denial of service attack that prevents wireless communication for every device that is connected to the wireless network. The attacker transmit interfering wireless signals to decrease the signal-to-noise ration at the receiving device. The receiving device cant hear the good signal and instead it receives mostly noise. 

This attack has many types: 
- constant or random bits of legitimate frames.
- Data sent at random times - random data and legitimate frames.
- Reactive jamming - only when someone else tries to communicate.

The attacker needs to be close for this attack to be effective. 