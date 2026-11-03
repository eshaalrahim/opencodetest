# Bunny Café

A cozy one‑page website for a cute bunny‑run café, designed as a resting place between work sessions. Inspired by indie‑web aesthetics of the early 2000s pastel and pixel‑art style.

## Purpose & Audience

- **Audience**: Students and remote workers taking a short, calming break.
- **Purpose**: Showcase a menu of bunny‑themed drinks and a short story about the café’s vibe, with a colour‑theme switch for light/dark reading.

## Local setup

```bash
# 1. Make sure you’re on the bunny‑cafe branch
git checkout bunny-cafe

# 2. Start a local HTTP server (Python 3 built‑in)
python -m http.server

# 3. Open http://localhost:8000 in your browser
```

No npm, no CDN. Only `index.html`, `style.css`, and `script.js` are used.

## How to stop the server

In the terminal running the server, press **`Ctrl +C`**.

## Browser & accessibility

- The layout adapts from a single‑column stack (narrow) to a two‑column grid (wide, ≥ 600 px).
- The theme‑toggle button is keyboard‑focusable (`Tab`/`Shift‑Tab`) and has a `focus‑visible` outline.
- `aria‑pressed` is updated when the theme changes, for screen‑reader clarity.