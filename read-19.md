#  AWS: Events


## 1 - What’s the difference between a FIFO and a standard queue?

**`FIFO queues` have essentially the same features as `standard queues`, but provide the added benefits of supporting ordering and exactly-once processing. `FIFO queues` provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers**

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
Serverless API | is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers
Triggers |  is procedural code that is automatically executed in response to certain events on a particular table or view in a database.  
Dynamo vs Mongo | is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas
Dynamoose vs Mongoose| is a modeling tool for Amazon's DynamoDB (inspired by Mongoose)


---

## SQS and SNS Basics 

![sqs](imgs/sns.png)


**works closely with Amazon Simple Queue Service (Amazon SQS). These services provide different benefits for developers. Amazon SNS allows applications to send time-critical messages to multiple subscribers through a “push” mechanism, eliminating the need to periodically check or “poll” for updates. Amazon SQS is a message queue service used by distributed applications to exchange messages through a polling model, and can be used to decouple sending and receiving components—without requiring each component to be concurrently available. Using Amazon SNS and Amazon SQS together, messages can be delivered to applications that require immediate notification of an event, and also persisted in an Amazon SQS queue for other applications to process at a later time.**

---

**is a publisher subscriber network, where subscribers can subscribe to topics and will receive messages whenever a publisher publishes to that topic. AWS SQS is a queue service, which stores messages in a queue.**

---

## THE END