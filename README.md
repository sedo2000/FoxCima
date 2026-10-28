# FoxCima

A responsive Arabic/English entertainment discovery landing page with a black-and-orange visual identity.

## Files
- `index.html` — page structure and Cinemana link/embed attempt.
- `styles.css` — responsive visual design.
- `app.js` — language toggle and basic search UI.
- `manifest.json`, `fox.svg` — PWA metadata and app mark.
- `sw.js` — lightweight offline shell cache.

## Run locally
Open `index.html` in a browser, or serve this folder using any static web server.

## Deploy
Import this repository into Vercel as a static site. No build command is required; the output directory is the repository root.

## Important limitations
The search UI is a front-end placeholder, not a real movie database. Connect a licensed/authorized catalog before presenting actual titles or streaming functionality. The Cinemana iframe is only an embedding attempt: the remote site may block framing through its security headers or browser policies. If blocked, use the direct official-site link. FoxCima does not bypass those controls or host/copy third-party streams.
