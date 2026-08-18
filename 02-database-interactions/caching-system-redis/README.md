# Caching System (redis-py)

**Category:** [Database Interactions](../README.md) &nbsp;·&nbsp; **Stack:** Redis &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A caching layer that speeds up expensive lookups using Redis as a key-value store.

## Flow Diagram

```
Request -> Check Redis cache\nCache HIT -> return cached value\nCache MISS -> compute -> store in Redis -> return
```

## How to Build It

1. Install: `pip install redis`\n2. Connect: `redis.Redis(host='localhost', port=6379)`\n3. Wrap an expensive function with a cache-check decorator\n4. Use `SETEX` to set values with an expiry (TTL)\n5. Add cache invalidation on updates\n6. Benchmark with vs without cache

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Database Interactions](../README.md) · [All 100 Projects](../../README.md)
