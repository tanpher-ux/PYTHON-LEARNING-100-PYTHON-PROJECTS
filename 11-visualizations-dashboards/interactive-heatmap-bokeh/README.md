# Interactive Heatmap (Bokeh)

**Category:** [Visualizations & Dashboards](../README.md) &nbsp;·&nbsp; **Stack:** Bokeh &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A zoomable, hoverable heatmap rendered in the browser.

## Flow Diagram

```
DataFrame (pivoted) -> Bokeh figure + rect glyphs -> HoverTool -> interactive HTML output
```

## How to Build It

1. Install: `pip install bokeh pandas`\n2. Pivot your data into a 2D matrix (rows/cols/values)\n3. Create a `figure()` and add `rect()` glyphs colored by value\n4. Add a `HoverTool` to show values on mouseover\n5. Add a `ColorBar` for the value scale\n6. Output with `show()` or embed via `components()`

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Visualizations & Dashboards](../README.md) · [All 100 Projects](../../README.md)
