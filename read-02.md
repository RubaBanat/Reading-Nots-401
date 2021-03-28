# Review, Research, and Discussion

1. **What’s the difference between PUT and PATCH?**

*`PUT` is for checking if resource is exists then update , else create new resource. `PATCH` is always for update a resource`*

---

2. **Provide links to 3 services or tools that allow you to “mock” an API for development**

- [MongoDB](https://www.mongodb.com/)
- [Postman](https://www.postman.com/)
- [Stoplight](https://stoplight.io/)

---

3. **Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?**


*HTTP response status codes indicate whether a specific HTTP request has been successfully completed. Responses are grouped in five classes:*

- Informational responses (100–199)
- Successful responses (200–299)
- Redirects (300–399)
- Client errors (400–499)
- Server errors (500–599)

---

4. **Compare and contrast SOAP and ReST**

SOAP | REST
------------ | -------------
Simple Object Access Protocol | Representational State Transfer
Standardized protocol with pre-defined rules to follow | Architectural style with loose guidelines and recommendations.
Function-driven (data available as services, e.g.: “getUser”) | Data-driven (data available as resources, e.g. “user”).
WS-Security with SSL support. Built-in ACID compliance | Supports HTTPS and SSL.
High security, standardized, extensibility. | Scalability, better performance, browser-friendliness, flexibility.
Poorer performance, more complexity, less flexibility | Less security, not suitable for distributed environments.

---

##  Vocabulary Terms

wWrd | Definition 
------------ | -------------
Web Server | The term web server can refer to hardware or software, or both of them working together
Express | Express is a back end web application framework for Node.js It is designed for building web applications and APIs
Routing | refers to determining how an application responds to a client request to a particular endpoint, which is a URI (or path) and a specific HTTP request method.
WRRC |  a cycle of requests and responses that flow between clients and servers.


---

## TDD 

*“Test-driven development” refers to a style of programming in which three activities are tightly interwoven: coding, testing ( and design .*

---

## CI / CD

![ci/cd](imgs/cicd.jpg)

*`CI/CD `generally refers to the combined practices of continuous integration and either continuous delivery or continuous deployment. CI/CD bridges the gaps between development and operation activities and teams by enforcing automation in building, testing and deployment of applications.*

---

## THE END