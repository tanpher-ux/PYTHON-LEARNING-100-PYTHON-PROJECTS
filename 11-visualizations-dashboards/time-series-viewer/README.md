# Time Series Viewer

**Category:** [Visualizations & Dashboards](../README.md) &nbsp;·&nbsp; **Stack:** Plotly &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

An interactive, zoomable viewer for time-indexed data with range selection.

## Flow Diagram

```
Time series DataFrame -> Plotly line chart -> add Range Slider/Selector -> interactive browser output
```

## How to Build It

1. Install: `pip install plotly pandas`\n2. Load time-indexed data into a DataFrame\n3. Create a line chart with `plotly.express.line`\n4. Add a range slider with `fig.update_xaxes(rangeslider_visible=True)`\n5. Add preset range buttons (1M, 6M, 1Y, All)\n6. Export as standalone HTML

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
