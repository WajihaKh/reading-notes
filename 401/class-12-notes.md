# Socket.io

**What is a Web Socket?**
A Web Socket is a way for websites or apps to talk to each other in real-time. It's like a phone line that stays open all the time.

**Web Socket handshake and connection:**
1. **Handshake**: The client asks the server if they can talk using Web Sockets.
2. **Connection**: If the server agrees, they switch to Web Sockets. Now, they can send messages back and forth instantly.

**Web Sockets for sending content:**
Web Sockets allow the server to send stuff to the client without waiting for the client to ask.

**What does `io.on()` do?**
`io.on()` listens for messages from clients. When a client sends a message, the server can do something in response.

**Proof that the code works:**
- Messages saying "connected" or "received" in the console.
- Seeing real-time updates on the website or app.

**What does `socket.emit()` do?**
It sends a message from the server to a specific client.

**WebSocket vs. Socket.IO:**
- WebSocket is like the basic phone line for real-time communication.
- Socket.IO is like a fancy phone system built on top of WebSocket, adding extra features.

**When to use Socket.IO?**
Use it for real-time stuff like chat apps or games, where instant updates are important.

**When to use WebSockets?**
Use Web Sockets when you need fast, real-time communication between a client and server, like in stock tickers or live sports updates.

**Key takeaways from OSI Model:**
1. The OSI Model has seven layers, each with a specific job.
2. It helps devices in a network communicate effectively.
