
---

## Physical Segmentation 

Two customers connected to two separate routers. If there is an air gap between these two routers, both customers can't communicate with each other. 

## Logical Segmentation with VLANs

Virtual Local Area Networks separate two places logically instead of physically. VLANs can't communicate between each other without a layer 3 device like a router.

## SDN (Software Defined Networking)

Networking devices have different functional planes of operation like data, control, and management planes. 

The infrastructure layer or the data plane is the part of the device doing the hard work. In routers and switches, processing the network frames and packets, forwarding, trunking, encrypting, etc, all fall under the data plane.

The control layer or control plane manages the actions of the data plane. It is responsible for routing tables, session tables, NAT tables, dynamic routing protocol updates. 

The application layer or management plane is responsible for configuring and managing the device. It is also responsible for SSH, browser, API, etc. 