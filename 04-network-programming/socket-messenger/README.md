# Socket Messenger

**Category:** [Network Programming](../README.md) &nbsp;·&nbsp; **Stack:** socket &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A simple client-server chat app using raw TCP sockets.

## Flow Diagram

```
Server: socket.bind() + listen() + accept()\nClient: socket.connect() -> send()/recv() both ways
```

## How to Build It

1. Import the built-in `socket` module\n2. Server: create a socket, `bind()` to host/port, `listen()`, `accept()`\n3. Client: `connect()` to the server's address\n4. Use `send()`/`recv()` in a loop for messages\n5. Use `threading` to handle multiple clients\n6. Add a clean way to disconnect

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Network Programming](../README.md) · [All 100 Projects](../../README.md)
