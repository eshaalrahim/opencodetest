# AGENTS.md – Bunny Café website

## Project constraints (for AI coding agents)

- **File set**: Only `index.html`, `style.css`, and `script.js`. No npm packages, no CDN imports.
- **Hosting**: Serve locally only (e.g., `python -m http.server`). No deployment.
- **Responsiveness**: Must work at narrow (mobile) and wide (desktop) browser widths.
- **Accessibility**: Keyboard‑navigable focus, ARIA labels, `aria-pressed` on theme button, semantic HTML.
- **Interaction**: Single button toggles a light/dark theme using CSS custom properties; no external JavaScript.
- **Design**: Pastel palette, indie‑web early‑2000s aesthetic, pixel‑bunny accent, card‑style sections.
- **No external dependencies**: All CSS and JS are hand‑written, self‑contained.
- **Git workflow**: All changes performed on a dedicated working branch (`bunny-cafe`). Do not commit, push, or merge without explicit approval.
- **Environment**: Add `.env`, `node_modules/`, and `.DS_Store` to `.gitignore`.

## How to run locally

```bash
# 1. Checkout the working branch
git checkout bunny-cafe

# 2. Start a simple HTTP server (Python 3 built‑in)
python -m http.server

# 3. Open http://localhost:8000 in a browser
```

No `npm install`, no `yarn`, no `vite`, no `webpack`. The three files are stand‑alone.