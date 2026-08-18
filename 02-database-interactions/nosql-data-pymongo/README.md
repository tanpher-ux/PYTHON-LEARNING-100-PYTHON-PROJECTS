# NoSQL Data with pymongo

**Category:** [Database Interactions](../README.md) &nbsp;·&nbsp; **Stack:** MongoDB + pymongo &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A script/app that stores and queries documents in MongoDB.

## Flow Diagram

```
App -> pymongo client -> MongoDB collection (JSON-like documents)
```

## How to Build It

1. Install: `pip install pymongo`\n2. Run/connect to a MongoDB instance (local or Atlas)\n3. Connect: `MongoClient('mongodb://localhost:27017')`\n4. Insert documents with `insert_one` / `insert_many`\n5. Query with `find()` and filters\n6. Add indexes for frequently queried fields

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
