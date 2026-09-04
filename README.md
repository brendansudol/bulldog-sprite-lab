# Bulldog Sprite Lab

An interactive static-site prototype for exploring a 4×3 bulldog mascot sprite sheet. It includes selectable reactions, responsive sizing, app-state examples, hover and click interactions, and simple frame animation.

## Run locally

Serve the repository root with any static file server, for example:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Project structure

- `index.html` — the complete demo UI, styles, and interactions
- `assets/bulldog-sprite-sheet.png` — the 1536×1152 source sprite sheet

## Deployment

Pushes to `main` deploy automatically to GitHub Pages through the included GitHub Actions workflow.
