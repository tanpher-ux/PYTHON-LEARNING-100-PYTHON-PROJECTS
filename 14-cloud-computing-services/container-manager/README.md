# Container Manager

**Category:** [Cloud Computing & Services](../README.md) &nbsp;·&nbsp; **Stack:** docker (Python SDK) &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A CLI tool to list, start, stop, and inspect Docker containers programmatically.

## Flow Diagram

```
Script -> docker-py client -> Docker Engine API -> container operations
```

## How to Build It

1. Install: `pip install docker`\n2. Create a client: `docker.from_env()`\n3. List containers with `client.containers.list()`\n4. Start/stop containers by name or ID\n5. Stream logs with `container.logs(stream=True)`\n6. Add a simple CLI menu wrapping these actions

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Cloud Computing & Services](../README.md) · [All 100 Projects](../../README.md)
