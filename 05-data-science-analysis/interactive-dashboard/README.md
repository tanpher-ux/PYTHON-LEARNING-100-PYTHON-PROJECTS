# Interactive Dashboard

**Category:** [Data Science & Analysis](../README.md) &nbsp;·&nbsp; **Stack:** Streamlit &nbsp;·&nbsp; **Difficulty:** Intermediate

## What You'll Build

A browser-based dashboard for exploring a dataset with filters and charts.

## Flow Diagram

```
User -> Streamlit UI widgets (filters) -> Pandas filtering -> Matplotlib/Plotly chart -> rendered live
```

## How to Build It

1. Install: `pip install streamlit pandas`\n2. Load a dataset with Pandas\n3. Add sidebar filters with `st.selectbox`, `st.slider`\n4. Filter the DataFrame based on selections\n5. Render charts with `st.line_chart` / `st.bar_chart`\n6. Run with `streamlit run app.py`

## Files in This Folder

- `README.md` — this file
- `starter.py` — a minimal scaffold to build from
- `requirements.txt` — suggested packages to install first

## Stretch Goals

- Add error handling for edge cases you hit while building this.
- Write a couple of unit tests for the core logic (see the Testing & QA category).
- Package it so someone else could install and run it with one command.

---
⬅ Back to [Data Science & Analysis](../README.md) · [All 100 Projects](../../README.md)
