# Music Player (PySide)

**Category:** [Desktop Applications (GUI)](../README.md) &nbsp;·&nbsp; **Stack:** PySide6 + QMediaPlayer &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A desktop music player with playlists, play/pause/skip, and a progress bar.

## Flow Diagram

```
GUI controls -> QMediaPlayer -> audio output\nPlaylist model -> QMediaPlayer.setSource() on track change
```

## How to Build It

1. Install: `pip install PySide6`\n2. Build the UI with play/pause/next/prev buttons and a slider\n3. Use `QMediaPlayer` + `QAudioOutput` to play audio files\n4. Build a playlist (`QListWidget`) of tracks\n5. Sync the progress slider with playback position\n6. Add volume control and shuffle/repeat modes

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Desktop Applications (GUI)](../README.md) · [All 100 Projects](../../README.md)
