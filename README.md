# HolyAds promotional homepage

Static, HTML-only marketing site for the [HolyAds](https://github.com/sniffis-commits/holyads) self-hosted ad network.

## Contents

- `index.html` — single self-contained page (HTML + inline CSS + inline JS, no build step)
- `assets/screenshots/` — real screenshots captured from the running HolyAds app
- `assets/video/how-it-works.mp4` — 16-second silent product tour assembled from those screenshots

## View locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

No PHP, no Composer, no Node, no frameworks.
