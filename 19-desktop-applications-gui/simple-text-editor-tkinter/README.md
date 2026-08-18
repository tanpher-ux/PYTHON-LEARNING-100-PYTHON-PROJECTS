# Simple Text Editor (Tkinter)

**Category:** [Desktop Applications (GUI)](../README.md) &nbsp;·&nbsp; **Stack:** Tkinter &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

A Notepad-style text editor with open/save/find and basic formatting.

## Flow Diagram

```
Tkinter window -> Text widget -> Menu (File/Edit) -> filedialog for open/save -> read/write file
```

## How to Build It

1. Tkinter ships with Python — no install needed\n2. Create the main window and a `Text` widget\n3. Add a menu bar with File > Open/Save using `filedialog`\n4. Implement Open (`read()`) and Save (`write()`)\n5. Add Find/Replace with `Text.search()`\n6. Add a modified-indicator in the title bar

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
