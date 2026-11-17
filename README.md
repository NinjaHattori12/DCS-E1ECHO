# Experiment 1: Multi-Threaded Echo Server & Client

A simple Java TCP socket client-server program that echoes messages back to clients until `Exit` is sent.

---

## ⚡ Commands & Sequence

### 1. Compile (Any Terminal)
```bash
javac EchoServer.java EchoClient.java
```

### 2. Start Server (Terminal 1)
```bash
java EchoServer
```

### 3. Start Client (Terminal 2)
```bash
java EchoClient
```
*(You can open additional terminals and run `java EchoClient` to test multiple clients simultaneously.)*

### 4. Stop / Exit
Type `Exit` in the client terminal to disconnect. Press `Ctrl + C` in the server terminal to stop the server.

---

## 🖥️ Example Output

### Terminal 1: Server
```text
$ java EchoServer
Echo Server started...
Waiting for clients...
Client 1 connected.
Client 1: Hello Server
Client 1: Exit
Client 1 disconnected.
```

### Terminal 2: Client
```text
$ java EchoClient
Connected to Echo Server.
Enter message: Hello Server
Echo from Server: Hello Server
Enter message: Exit
```
