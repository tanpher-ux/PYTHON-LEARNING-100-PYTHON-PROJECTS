# Slack Bot

**Category:** [API Integration & Services](../README.md) &nbsp;·&nbsp; **Stack:** slack-sdk &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A Slack bot that listens for messages/commands and responds in a workspace.

## Flow Diagram

```
Slack Events API (webhook/socket mode) -> Bot handler -> slack-sdk -> post message back to channel
```

## How to Build It

1. Install: `pip install slack-sdk slack-bolt`\n2. Create a Slack App and get a Bot Token\n3. Use `slack_bolt.App` and enable Socket Mode\n4. Listen for events with `@app.event("message")`\n5. Respond using `say()`\n6. Add slash commands with `@app.command()`

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [API Integration & Services](../README.md) · [All 100 Projects](../../README.md)
