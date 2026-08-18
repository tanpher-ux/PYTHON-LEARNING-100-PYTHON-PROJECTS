# Interactive Map (Folium)

**Category:** [Visualizations & Dashboards](../README.md) &nbsp;·&nbsp; **Stack:** Folium &nbsp;·&nbsp; **Difficulty:** Beginner

## What You'll Build

Plots geographic points/routes on an interactive Leaflet-based map.

## Flow Diagram

```
Lat/Lon data -> folium.Map() -> add Markers/Layers -> save as HTML -> open in browser
```

## How to Build It

1. Install: `pip install folium`\n2. Create a base map: `folium.Map(location=[lat, lon])`\n3. Add markers with `folium.Marker()`\n4. Add polylines/routes if needed\n5. Style markers with popups and icons\n6. Save with `m.save('map.html')`

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
