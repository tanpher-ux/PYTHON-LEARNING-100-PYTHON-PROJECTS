# Dynamic Dashboard (Dash)

**Category:** [Visualizations & Dashboards](../README.md) &nbsp;·&nbsp; **Stack:** Plotly Dash &nbsp;·&nbsp; **Difficulty:** Advanced

## What You'll Build

A multi-component dashboard with dropdowns/sliders that update charts live.

## Flow Diagram

```
User changes control (dropdown/slider) -> Dash callback fires -> recompute figure -> chart re-renders
```

## How to Build It

1. Install: `pip install dash pandas plotly`\n2. Define the app layout with `dcc` and `html` components\n3. Add input controls (Dropdown, Slider)\n4. Write a `@app.callback` connecting inputs to a Graph output\n5. Return an updated Plotly figure from the callback\n6. Run with `app.run_server(debug=True)`

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
