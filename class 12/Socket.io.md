## Socket.io

### Web Sockets

**What is a Web Socket?**

A WebSocket is a communication protocol that provides full-duplex communication between a client and a server over a single, long-lived connection. It enables real-time, bidirectional communication between a web browser (or any other client application) and a web server.

**Describe the Web Socket request/response handshake and what happens once the connection is established.**

The WebSocket protocol starts with an initial handshake process that follows the HTTP protocol
1-Client initiates the handshak
2-Server acknowledges the handshake
3-WebSocket connection is established
4-Data exchange
5-Data framing
6-Real-time communication
7-Connection termination

**Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.**

Web Sockets provide a standardized way for the server to send content to a client without first receiving a request (or response) from that client.

### Socket.io Tutorial

**What does the event handler io.on() do?**

on() method is used to define event handlers for various events emitted by the Socket.IO server

**Describe some possible proof of life or proof that the code works as expected**

1-Test Cases: Create a suite of test cases that cover different aspects of your code's functionality.
2-Code Review: Engage in a code review process where other experienced developers review your code for logic errors, adherence to best practices, and potential bugs.
3-User Acceptance Testing: Involve end-users or stakeholders to perform user acceptance testing.

**What does socket.emit() do?**

socket.emit() is used to send custom events from the client to the server (or vice versa) using Socket.IO, enabling real-time communication between the client and server over a WebSocket connection.

### Socket.io vs Web Sockets

**What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).**

WebSocket is a lower-level protocol that enables real-time bidirectional communication, while Socket.IO is a higher-level library that abstracts WebSocket and provides additional features, fallback mechanisms, and ease of use for real-time applications. Socket.IO builds upon WebSocket to offer a more comprehensive and flexible solution for real-time communication.

**When would you use Socket.IO?**

Socket.IO is commonly used in scenarios where real-time, bidirectional communication is required between clients and servers

**When would you use WebSockets?**

WebSocket is beneficial in various scenarios that require real-time, bidirectional communication between a client and a server.

### OSI Model Explained

**What are a couple of key takeaways from this video?**

1-Protocol Stacks: The OSI model describes a protocol stack, which is a set of protocols organized into layers
2-Interoperability: The layered structure of the OSI model enables interoperability between different vendors and technologies.

### TCP Handshakes Explained

**Translate the gist of this video to a non-technical friend**

The Three-way handshake is like a conversation between two computers before they start sending data to each other. Imagine you and your friend want to exchange some messages.