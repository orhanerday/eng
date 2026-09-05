# Grammar Practice PWA

Files:
- `index.html` — app
- `manifest.webmanifest` — install metadata
- `service-worker.js` — offline app-shell cache
- `icons/` — PWA/app icons

Run locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

PWA/service-worker features do not run from `file://`. GitHub Pages works because it serves over HTTPS.
