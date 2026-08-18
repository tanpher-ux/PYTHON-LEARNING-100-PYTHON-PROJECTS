# Chatbot (chatterbot)

**Category:** [Natural Language Processing (NLP)](../README.md) &nbsp;·&nbsp; **Stack:** ChatterBot &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A trainable conversational chatbot that learns from example dialogue.

## Flow Diagram

```
User message -> ChatterBot matches closest known statement -> returns best response -> conversation logged for future training
```

## How to Build It

1. Install ChatterBot (note: needs older Python compatibility) or use a modern alternative\n2. Create a `ChatBot()` instance with a storage adapter\n3. Train it with a corpus of example conversations\n4. Get responses with `chatbot.get_response(text)`\n5. Wrap it in a simple CLI or web chat UI\n6. Add custom training data for your domain

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Natural Language Processing (NLP)](../README.md) · [All 100 Projects](../../README.md)
