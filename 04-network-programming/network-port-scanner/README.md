# Network Port Scanner

**Category:** [Network Programming](../README.md) &nbsp;·&nbsp; **Stack:** socket + threading &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Scans a host for open TCP ports within a given range.

## Flow Diagram

```
for port in range: socket.connect_ex((host,port)) -> open/closed
```

## How to Build It

1. Import `socket` and `threading`\n2. Loop through a range of ports\n3. For each port, attempt `connect_ex((host, port))`\n4. A return value of 0 means the port is open\n5. Use a `ThreadPoolExecutor` to scan ports in parallel\n6. Print a clean report of open ports

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
