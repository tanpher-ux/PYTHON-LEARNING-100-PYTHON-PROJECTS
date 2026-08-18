# Async API Gateway

**Category:** [Web Development Frameworks](../README.md) &nbsp;·&nbsp; **Stack:** FastAPI + httpx &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

An async gateway that routes and aggregates requests to multiple backend services.

## Flow Diagram

```
Client -> Gateway\nGateway -> Service A (httpx async)\nGateway -> Service B (httpx async)\nGateway merges responses -> Client
```

## How to Build It

1. Install: `pip install fastapi httpx uvicorn`\n2. Define route mappings to backend service URLs\n3. Use `httpx.AsyncClient` to forward requests concurrently with `asyncio.gather`\n4. Add basic auth/rate-limiting middleware\n5. Add response caching for repeated calls\n6. Test with multiple mock backend services

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
