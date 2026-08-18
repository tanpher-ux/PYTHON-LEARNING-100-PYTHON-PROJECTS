# Real-time Chat (FastAPI)

**Category:** [Web Development Frameworks](../README.md) &nbsp;·&nbsp; **Stack:** FastAPI + WebSockets &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A multi-user chat room built on FastAPI's native WebSocket support.

## Flow Diagram

```
Client A --ws--> FastAPI Server\nClient B --ws--> FastAPI Server\nServer broadcasts message to all connected clients
```

## How to Build It

1. Install: `pip install fastapi uvicorn`\n2. Create a `ConnectionManager` class to track active WebSocket clients\n3. Define a `/ws/{client_id}` WebSocket endpoint\n4. On message received, broadcast to all connected clients\n5. Build a minimal HTML/JS page to test it\n6. Run with `uvicorn main:app --reload`

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Web Development Frameworks](../README.md) · [All 100 Projects](../../README.md)
