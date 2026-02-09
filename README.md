# Omni Landing Page

Modern, mobile-first landing page for the Omni iOS app. Built as a static site for GitHub Pages.

## What's Included
- `index.html` for content and layout
- `styles.css` for styling and responsive design
- `app.js` for scroll reveal animations

## Run Locally
Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy on GitHub Pages
Enable GitHub Pages for this repo:

1. Go to the repo on GitHub → Settings → Pages.
2. Under “Build and deployment,” select “Deploy from a branch.”
3. Choose `main` and the `/ (root)` folder.

Then push to the `main` branch of `omnistudy-one.github.io`. GitHub Pages will publish the site at:

`https://omnistudy-one.github.io`

## Customize
- Replace the App Store link (`href="#"`) with your real App Store URL.
- Swap the demo placeholder with an embedded video.
- Update footer links and support email as needed.
