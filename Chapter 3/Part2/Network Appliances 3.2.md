
## Jump Server

This is a device that is connected to the private network and also can be accessed from outside. The jump server must be hardened by security procedures due to its connection to the inner network. 

Connecting to the jump server usually requires two-step process. The external client or user will first connect to the jump server and from the jump server they will connect to the internal network using SSH or VPN.

## Proxies

A proxy is designed to sit in the middle of a conversation between of two devices and make request on behalf of one of these users. 

A proxy will usually sit between an inner network and the outer internet. A user will need to send request first to the proxy before the proxy passing this request to the outer internet. The same will happen but backwards when the user receives a response back from the internet. 

Proxies are useful for caching information, access control, URL filtering, content scanning.

There are two types of proxies: **explicit proxy and invisible or transparent proxy**. Explicit proxy must be configured in the OS that is being used. It is called explicit because we are explicitly naming the IP address or name of the proxy that we are communicating with. The invisible proxy is the one that sets in the middle between a network and the outer internet. The user  may not know that a proxy exist.

## Application Proxies

One of the simplest proxies is **Network Address Translation NAT** which is a network-level proxy.

Most proxies in use are application proxies. The proxy understands the way the application works. A proxy may only know one application like HTTP. Many proxies are multipurpose proxies: HTTP, HTTPS, FTP, etc. 

## Forward Proxy

This is an internal proxy commonly used to protect and control user access to the internet by examining the traffic coming from the internet to the inner network.

## Reverse Proxy

Reverse proxy works in a similar way to the forward proxy but it manages inbound traffic to a specific service. For example, there might be users on the internet that would like to communicate to a web server that's inside an internal network. Instead of having the users directly communicate to the web server, they connect to a proxy server. The proxy server then makes a request on the user's behalf. The response will be sent form the web server to the proxy server then it will be sent to the users on the internet. This proxy can act as a cache to save the responds coming back from the web server. 

## Open Proxy

These are proxies controlled by third-party which is a significant security concern. They are often used to void existing security controls. 

## Load Balancer

Load balancer will take a load coming from one source and distribute it across multiple services or servers.

These are used in large-scale implementations, like web server farms, database farms.

Load balancers are tolerant to fail. If a server connected to a load balancer was to fail, the load balancer would recognize that server was no longer communicating and would split the load among the remaining servers.

## Active/Active Load Balancer

All of the servers connected to the load balancer are all active and being used by the load balancer. The load balancer can also provide TCP offloading which means that it doesn't have to set up an individual TCP communication session for every user connecting to the servers. Instead it will keep one single TCP connection open all the time and simply distribute the load without having to recreate separate TCP sessions each time.

Load balancers can also perform SSL offload. Instead of having the servers manage the decryption individually, all the decryption can be done on the load balancer, which then sends in the clear or decrypt traffic down to the servers. On the way back, the load balancer will encrypt the response and sends it back to the user.

Load balancers can also perform caching. They can also prioritize traffic depending on the protocol or source it came from. They can also perform content switching, which means they recognize the type of requests being made and can send certain requests to specific web servers that are connected to the load balancer. 

## Active/Passive Load Balancer

That means some servers are currently working as usual, and others are not working and are on stand-by. If an active server fails, the passive server takes its place.


## Sensors and Collectors

Sensors can be integrated into switches, routers, servers, firewalls, etc. 

All of the details gathered from the sensors are sent to one central database called a collector. Sometimes this is a proprietary console that is written specifically to work with certain types of devices, for example, an IPS or a firewall. 
