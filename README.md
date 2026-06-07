# Java Chat Server

A multi-client terminal chat server built with Java sockets and threads.

## How it works

The server accepts multiple client connections simultaneously. Each client gets its own thread. Messages are broadcast to all other connected clients in real time.

## Run it

**1. Compile**
```bash
javac Server.java ClientHandler.java Client.java MessagePrinter.java
```

**2. Start the server**
```bash
java Server
```

**3. Connect clients** (each in a separate terminal)
```bash
java Client
```

> Make sure `Client.java` has the right IP. For local testing use `localhost`.

## Type `bye` to disconnect.
