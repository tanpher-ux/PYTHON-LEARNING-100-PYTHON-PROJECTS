# Advanced File Explorer

**Category:** [Desktop Applications (GUI)](../README.md) &nbsp;·&nbsp; **Stack:** Tkinter/PySide + os &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A dual-pane file browser with search, preview, and file operations.

## Flow Diagram

```
GUI tree/list widgets -> os/pathlib for filesystem access -> user actions (copy/move/delete/rename)
```

## How to Build It

1. Build a folder tree view with `ttk.Treeview`\n2. List files/folders of the selected directory\n3. Add copy/move/delete/rename using `shutil`/`os`\n4. Add a search box filtering the current listing\n5. Add a preview pane for text/image files\n6. Add keyboard shortcuts for common actions

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
