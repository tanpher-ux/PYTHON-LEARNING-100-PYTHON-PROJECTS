# Auto Email Sender

**Category:** [Automation & Scripting](../README.md) &nbsp;·&nbsp; **Stack:** smtplib &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Sends templated emails automatically (e.g. reports, reminders, alerts).

## Flow Diagram

```
Trigger (schedule/event) -> build email (MIME) -> smtplib SMTP connection -> send -> log result
```

## How to Build It

1. Use the built-in `smtplib` and `email.message` modules\n2. Build an `EmailMessage` with subject/body/attachments\n3. Connect to your SMTP server with TLS\n4. Send with `server.send_message(msg)`\n5. Store credentials in environment variables, not in code\n6. Add retry logic for transient failures

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Automation & Scripting](../README.md) · [All 100 Projects](../../README.md)
