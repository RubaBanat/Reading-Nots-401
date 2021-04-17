#  AWS: Cloud Servers

![aws](imgs/aws-logo.png)

---

## 2 - What’s the difference between a FIFO and a standard queue?

**`FIFO queues` have essentially the same features as `standard queues`, but provide the added benefits of supporting ordering and exactly-once processing.` FIFO queues` provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers**

---

## 2 - How can the server be assured a message was properly received?

**Retrieves the Response from the server. Helps validate the Response received from the server. Internally this class uses HTTP builder library**

---

## 3 - What classic design pattern is best represented by event driven programming?

**Most modern programming-languages comprise built-in “event” constructs implementing the observer-pattern components.**

---

## 4 - How do you test an event driven system?

**With unit tests which test individual components of the system, as well as tests for verifying the server and clients are communicating back and forth**

---

## Important Terms


Word | Definition 
------------ | -------------
Server | A Web server is a program that uses HTTP (Hypertext Transfer Protocol) to serve the files that form Web pages to users, in response to their requests, which are forwarded by their computers' HTTP clients.
Pub/Sub |is an asynchronous messaging service that decouples services that produce events from services that process events.
WRRC | The web is a cycle of requests and responses that flow between clients and servers.


---

## Virtual Machines:

**a machine that runs simultaneously on another device by sharing its resources with the original device**

---

## AWS EC2

**Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the Amazon Web Services (AWS) Cloud. Using Amazon EC2 eliminates your need to invest in hardware up front, so you can develop and deploy applications faster. You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage. Amazon EC2 enables you to scale up or down to handle changes in requirements or spikes in popularity, reducing your need to forecast traffic.**

---

## Features of Amazon EC2 :

- Virtual computing environments, known as instances

- Preconfigured templates for your instances, known as Amazon Machine Images (AMIs), that package the bits you need for your server (including the operating system and additional software)

- Various configurations of CPU, memory, storage, and networking capacity for your instances, known as instance types

- Secure login information for your instances using key pairs (AWS stores the public key, and you store the private key in a secure place)

- Storage volumes for temporary data that's deleted when you stop, hibernate, or terminate your instance, known as instance store volumes

- Persistent storage volumes for your data using Amazon Elastic Block Store (Amazon EBS), known as Amazon EBS volumes

- Multiple physical locations for your resources, such as instances and Amazon EBS volumes, known as Regions and Availability Zones

- A firewall that enables you to specify the protocols, ports, and source IP ranges that can reach your instances using security groups

- Static IPv4 addresses for dynamic cloud computing, known as Elastic IP addresses

---

## AWS Elastic Beanstalk 

**AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.**

---

# THE END 