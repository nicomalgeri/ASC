# After Sports Consultancy static site

A direct Webflow export of the After Sports Consultancy site, cleaned up for a repo with predictable names.

## Structure
- `index.html` – main static page (formerly `ASC Home.html`).
- `assets/` – all exported CSS/JS/image assets (formerly `ASC Home_files/`).

## Run locally
You can open `index.html` directly in a browser, or start a quick local server to avoid any browser security restrictions:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000 in your browser
```

Or use npm (added here for convenience):

```bash
npm install   # first time only
npm run dev   # serves the site on http://localhost:8000
```

## Deployment
There is no build step. Any static host (GitHub Pages, Netlify, Vercel, S3/CloudFront, etc.) can serve the files by pointing the host to the repo root or uploading `index.html` plus the `assets/` directory.
