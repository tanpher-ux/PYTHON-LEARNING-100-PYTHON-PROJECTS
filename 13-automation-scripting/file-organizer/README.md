# File Organizer

**Category:** [Automation & Scripting](../README.md) &nbsp;·&nbsp; **Stack:** os / shutil / pathlib &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Automatically sorts files in a folder into subfolders by type or date.

## Flow Diagram

```
Scan folder -> for each file, read extension/date -> move into matching subfolder -> log actions
```

## How to Build It

1. Use `pathlib.Path` to list files in a target directory\n2. Map extensions to category folders (images, docs, etc.)\n3. Create destination folders if they don't exist\n4. Move files with `shutil.move()`\n5. Handle name collisions (append a counter)\n6. Add a dry-run mode that only prints planned moves

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
