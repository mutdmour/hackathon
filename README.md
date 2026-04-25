# Hackathon 3D Viewer

Interactive browser-based viewer for the project's GLB 3D models (Brandenburg, Hamburg, North Germany, Ruhr).

## Requirements

- Python 3 (ships with macOS) — used as a local HTTP server
- A modern browser (Chrome, Firefox, Safari, Edge)

## Launch

```bash
cd hackathon
python3 -m http.server 8765
```

Then open **http://localhost:8765/viewer.html** in your browser.

> The viewer must be served over HTTP (not opened as a local file) because the browser blocks loading GLB assets from `file://` URLs.

## Controls

| Action | Input |
|--------|-------|
| Rotate | Left-click + drag |
| Zoom | Scroll wheel |
| Pan | Right-click + drag |

## Files

```
Exp 3D-Modells/          # GLB 3D models
Project Data/            # CSV project data (two datasets)
viewer.html              # Three.js viewer (single file, no install needed)
```
