# Speech-to-Text

**Category:** [Deep Learning & AI](../README.md) &nbsp;·&nbsp; **Stack:** SpeechRecognition / Whisper &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

Transcribes spoken audio into text.

## Flow Diagram

```
Microphone/audio file -> audio preprocessing -> ASR model -> transcribed text
```

## How to Build It

1. Install: `pip install SpeechRecognition` (or `openai-whisper`)\n2. Capture audio from mic or load an audio file\n3. Feed audio into the recognizer/model\n4. Handle different audio formats (convert with `pydub` if needed)\n5. Print/save the transcription\n6. Add basic error handling for unclear audio

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Deep Learning & AI](../README.md) · [All 100 Projects](../../README.md)
