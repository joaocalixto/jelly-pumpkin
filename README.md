# Jelly Pumpkin

Squishy 3D jelly pumpkins you can drag, stretch and toss around, built with
[three.js](https://threejs.org/) and [cannon-es](https://pmndrs.github.io/cannon-es/).

**Play it:** https://joaocalixto.github.io/jelly-pumpkin/

## Controls

| Action | What it does |
| --- | --- |
| Drag | Stretch a pumpkin like taffy and toss it |
| Double-click | Drop a new pumpkin (or make the one you clicked hop) |
| Space | Make every pumpkin bounce |
| R | Reset the scene |

## Running locally

It is a single static `index.html` with no build step — any static server works:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.
