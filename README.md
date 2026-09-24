# Anime Stream

Built site snapshot published from the live Replit deployment:

https://anime-stream-hub-1--hmuch1954.replit.app

## Contents

This repository contains the production frontend bundle served by the site:

- `index.html`
- `assets/` (compiled JavaScript and CSS)
- `favicon.svg`

The frontend currently calls the Replit-hosted API routes for trending titles, search, anime info, episode metadata, and streaming (`/api/trending`, `/api/search`, `/api/info`, `/api/watch`, and `/api/stream`). Hosting these static files on GitHub Pages alone will not reproduce the full streaming runtime unless those API routes are also deployed and the frontend is configured to use them.
