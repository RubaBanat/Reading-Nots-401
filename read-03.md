# Express REST API

![rest](imgs/rest-api.jpg)

---

1. **Name 3 real world use cases where you’d want to change the request with custom middleware**

- Data management
- Authentication
- Error handling

---

2. **True or false: The route handler is middleware?**

False 

3. **In what ways can a middleware function end the process and send data to the browser?**

*If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.*

---

4. **At what point in the request lifecycle can you “inject” middleware?**

*in the requests and responses*

5. **What can cause express to error with “Request headers sent twice, cannot start a second response”**

*The problematic middleware sets the response header without calling response.end() and calls next(), which confuses connect's server.*

---

##  Vocabulary Terms

Word | Definition 
------------ | -------------
Middleware |  is software that bridges gaps between other applications, tools, and databases in order to provide unified services to users.
Request Object | The request object allows you to submit a POST or GET request to an URL. Essentially it provides a way to make REST API requests to another URL.
Response Object | One of the most important objects in ASP is the Response object. It is the object which communicates between the server and the output which is sent to the client.
Application Middleware | Middleware that plays a role in the function of the application.
Routing Middleware | a middleware that works on router level router.use
Test Driven Development | s a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases
Behavioral Testing | Testing of the external behavior of the program.

---

# THE END