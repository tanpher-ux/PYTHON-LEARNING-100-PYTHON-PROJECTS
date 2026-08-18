# Remote Shell Client (Paramiko)

**Category:** [Network Programming](../README.md) &nbsp;·&nbsp; **Stack:** Paramiko &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Connects to a remote server over SSH and executes commands programmatically.

## Flow Diagram

```
Python script -> Paramiko SSHClient -> SSH connection -> Remote server executes command -> returns output
```

## How to Build It

1. Install: `pip install paramiko`\n2. Create an `SSHClient()` and set a host-key policy\n3. Connect with `client.connect(host, username, password/key)`\n4. Run commands with `exec_command()`\n5. Read stdout/stderr streams\n6. Close the connection cleanly with `client.close()`

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
