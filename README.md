# Hosted Lore Microsite

A single static page (`index.html`) hosted on GitHub Pages.

## Edit

Open `index.html` in a browser to preview. There's no build step.

## Deploy

GitHub Pages serves the `main` branch root:

1. In the repo, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*. Then pick branch `main` and folder `/ (root)`.
3. Push to `main`. The site is published at
   https://anchorpoint-software.github.io/hosted-lore-microsite/

`.nojekyll` turns off Jekyll processing, so the file is served exactly as written.
