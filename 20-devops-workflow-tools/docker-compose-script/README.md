# Docker Compose script

**Category:** [DevOps & Workflow Tools](../README.md) &nbsp;·&nbsp; **Stack:** PyYAML + docker &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A Python tool that generates and manages a docker-compose.yml for a project.

## Flow Diagram

```
Service definitions (Python dicts) -> serialize to docker-compose.yml -> `docker compose up` -> running services
```

## How to Build It

1. Install: `pip install pyyaml`\n2. Define services (app, db, cache) as Python dictionaries\n3. Serialize them into a valid `docker-compose.yml` with `yaml.dump()`\n4. Add networks/volumes as needed\n5. Validate by running `docker compose config`\n6. Add a CLI to add/remove services programmatically

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [DevOps & Workflow Tools](../README.md) · [All 100 Projects](../../README.md)
