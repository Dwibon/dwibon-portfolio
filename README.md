# Dwibon Bhargab Deka — Portfolio

A static portfolio showcasing work across AI/ML, cybersecurity, and applied research. The visual experience uses a locally bundled Three.js renderer and scene assets.

## Project structure

- `index.html` — portfolio entry point and full-window iframe host.
- `landing-pages/kage.html` — portfolio content, interactions, and Three.js scene.
- `landing-pages/secret-pathways-assets/` — Three.js runtime, fonts, generated scene images, and foreground layers.

## Run locally

Serve the project root with any static HTTP server, then open the local URL. For example:

```sh
python3 -m http.server 8000
```

The portfolio is then available at `http://localhost:8000/`. The iframe uses same-origin access to apply typography overrides, so serve the files over HTTP rather than opening `index.html` directly from disk.

## Deploy

GitHub Pages serves the static site from the `main` branch root. No build step is required.
