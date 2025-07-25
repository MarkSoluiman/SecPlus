
---
![[Pasted image 20250716200609.png]]

This is an example for cloud responsibility matrix for SaaS, PaaS, IaaS, and On-Prem. 

SaaS is the most dependable on the service provider, in this case, Microsoft. Microsoft is responsible for most of the aspects of the cloud, including security. 

## Hybrid Considerations

This happens when we have more than one public or private cloud which adds more complexity. Network protection mismatches problems start to arise due to authentication across different platforms, firewall configurations, and server settings.

Different cloud providers have different logs with different terminology and view. Since cloud providers are constantly communicating with each other, data is more prone to leakage while being transferred across the internet.

## Infrastructure as Code

Infrastructure as code defines servers, network, and applications as code. It allows for easier modification of the infrastructure and version creation.

## Serverless Architecture

Aka **Function as a Service (FaaS)**. These  are applications separated into individual, autonomous functions. The functions run in a stateless compute container.

## Microservices and APIs 

Monolithic application is one big application that does everything. This application contains everything: UI, business logic, and data input and output. This creates code challenges  when it comes to installing and updating the application on multiple devices. 

In the cloud, we are able to use a more streamlined process that focuses on a microservice architecture. The API is the glue for the microservices as it connects multiple microservices together to the database and communicate the information back and forth between these databases and the client. This is approach is scalable  and resilient.



