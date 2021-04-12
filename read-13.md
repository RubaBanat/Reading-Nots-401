# Message Queues

![MQ](imgs/sqs.png)

---

## 1 - What does it mean that web sockets are bidirectional? Why is this useful?

**Because its enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time**

---

## 2 - Does socket.io use HTTP? Why?

**a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js**

---

## 3 - What happens when a client emits an event?

**Event will be sent to the server, and start listening for the event when it's connected**

---

## 4 - What happens when a server emits an event?

**When its listening to the server , so then it will response**

---

## 5 - What happens if a client “misses” an event?

**Unhandled messages are ignored**

---

## 6 - How can we mitigate this?

**by always having handlers installed and decalcify what to do whit this message**

---

##  Vocabulary Terms


Word | Definition 
------------ | -------------
Socket | is one endpoint of a two-way communication link between two programs running on the network
Web Socket | is a computer communications protocol, providing full-duplex communication channels over a single TCP connection
Socket.io | is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers.
Client|   program separate from the server that initiates requests for services or info from the server
Server |  provides function, info, or service back to the client, acts as the main hub for communication
OSI Model |s a conceptual framework used to describe the functions of a networking system
TCP Model | is the conceptual model and set of communications protocols used in the Internet and similar computer networks.
TCP | is a standard that defines how to establish and maintain a network conversation through which application programs can exchange data
UDP | is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet.
Packets | is a small amount of data sent over a network, such as a LAN or the Internet. Similar to a real-life package, each packet includes a source and destination as well as the content (or data) being transferred

---

# socket.io Cheat Sheet

// sending to sender-client only
- socket.emit('message', "this is a test");

// sending to all clients, include sender
- io.emit('message', "this is a test");

// sending to all clients except sender
- socket.broadcast.emit('message', "this is a test");

// sending to all clients in 'game' room(channel) except sender
- socket.broadcast.to('game').emit('message', 'nice game');

// sending to all clients in 'game' room(channel), include sender
- io.in('game').emit('message', 'cool game');

// sending to sender client, only if they are in 'game' room(channel)
- socket.to('game').emit('message', 'enjoy the game');

// sending to all clients in namespace 'myNamespace', include sender
- io.of('myNamespace').emit('message', 'gg');

// sending to individual socketid (server-side)
- socket.broadcast.to(socketid).emit('message', 'for your eyes only');

// join to subscribe the socket to a given channel (server-side):
- socket.join('some room');

// then simply use to or in (they are the same) when broadcasting or emitting (server-side)
- io.to('some room').emit('some event'):

// leave to unsubscribe the socket to a given channel (server-side)
- socket.leave('some room');

---

# THE END