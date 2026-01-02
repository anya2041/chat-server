# chat-server
A simple chat server and client project made using Python and socket programming

## Features

- TCP-based communication using Python sockets
- Multi-client support via threading
- Real-time message exchange between server and clients
- Minimal dependencies (Python standard library only)

---

## Technologies Used

- **Python 3**
- `socket` module for network communication
- `threading` module for concurrent client handling

---


## How It Works

-The server listens on a fixed IP address and port.
-Multiple clients can connect to the server simultaneously.
-Each client connection is handled in a separate thread.
-Clients send messages to the server, and the server responds to each message independently.
-Communication occurs over TCP, ensuring reliable and ordered data transmission.


---

## Running and Testing the Application

### Step 1: Start the Server

In one terminal window, run:

```bash
python server.py
```

The server will begin listening for incoming connections.

### Step 2: Start One or More Clients

In separate terminal windows, run:

```bash
python client.py
```

Each client will connect to the server and allow message exchange.

### Step 3: Test Concurrent Clients

Multiple clients can run simultaneously. Each client:

- Maintains its own connection
- Communicates independently with the server
- Is handled in a separate thread on the server side

This demonstrates basic concurrency in networked systems.

---
