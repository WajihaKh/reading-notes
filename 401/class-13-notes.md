# Message Queue

**What does the Chat Example do?**
It's like a digital chat room where people can talk to each other in real-time.

**What proof of life do we get from the backend?**
We see messages on the server confirming connections and messages received from clients.

**How do we send a message to everyone except one person?**
Use `io.emit()` with the `broadcast` flag.

**What is a room and why is it useful?**
A room is like a separate chat group. It helps organize users based on topics or roles.

**How do you join or leave a room?**
You can join a room with `socket.join()` and leave with `socket.leave()`.

**What is a Namespace and what can it do?**
It's like a separate area for communication. Each one can have its own events, groups, and connections.

**When might you use separate namespaces?**
You might use them to organize different parts of an app, like separate chat rooms or game features.
