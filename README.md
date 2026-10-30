# Tix Android download page

A lightweight static landing page for downloading the supplied Tix Android APK.

## Run locally

Open `index.html` in a browser, or serve this folder with any static file server. No build step, framework, backend, or external service is required for the download.

## Publish

The GitHub Actions workflow in `.github/workflows/pages.yml` deploys the site to GitHub Pages whenever changes are pushed to `main`. Enable **Settings → Pages → Build and deployment → Source: GitHub Actions** in the repository if Pages has not been configured yet.

## Files

- `index.html` — accessible landing page and installation guidance
- `styles.css` — responsive presentation
- `assets/tix-logo.png` — supplied Tix logo
- `assets/tix_KE.apk` — supplied Android package linked by the download button
