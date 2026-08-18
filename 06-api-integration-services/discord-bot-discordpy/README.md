# Discord Bot (discord.py)

**Category:** [API Integration & Services](../README.md) &nbsp;·&nbsp; **Stack:** discord.py &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A Discord bot that responds to commands and events in a server.

## Flow Diagram

```
Discord Gateway (WebSocket) -> Bot receives event -> command handler -> bot sends response
```

## How to Build It

1. Install: `pip install discord.py`\n2. Create a bot application + token in the Discord Developer Portal\n3. Initialize `commands.Bot(command_prefix="!")`\n4. Add commands with `@bot.command()`\n5. Add event listeners (`on_member_join`, etc.)\n6. Run with `bot.run(TOKEN)` — keep the token out of source control

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
