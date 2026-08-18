# Custom HTTP Server

**Category:** [Network Programming](../README.md) &nbsp;·&nbsp; **Stack:** http.server / socket &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A minimal HTTP server built from scratch to understand the protocol.

## Flow Diagram

```
Client browser -> TCP socket -> parse HTTP request line & headers -> build HTTP response -> send back
```

## How to Build It

1. Start from Python's `http.server.BaseHTTPRequestHandler` or raw sockets\n2. Parse the incoming request line and headers\n3. Implement `do_GET` and `do_POST` handlers\n4. Serve static files from a directory\n5. Add basic routing logic\n6. Return proper status codes and headers

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
