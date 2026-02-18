# MediaLaunchFX

MediaLaunchFX is a single-page cinematic boot-sequence generator for game media (disc, card, cartridge, tray, and spindle styles).

## Run locally

Because the app is static, you can open `index.html` directly or serve it with any static server.

### Option A: open directly

- Double-click `index.html`.

### Option B: serve with Python

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Notes

- The UI can auto-fetch title metadata from GameTDB via the AllOrigins proxy.
- Share URLs are generated from your selected platform, media ID, text style, and custom instructions.
- Reduced-motion preferences are respected when your OS/browser requests less animation.
