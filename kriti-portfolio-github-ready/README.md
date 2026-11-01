# Kriti Arora Portfolio

Personal portfolio website for Kriti Arora.

## Project structure

- `index.html` — complete portfolio website (HTML, CSS, and JavaScript)
- `Kriti_Arora_Resume.pdf` — image-based PDF résumé linked from the site (no selectable text layer)
- `headshot.jpg` — optional; add this file next to `index.html` to replace the built-in `KA` fallback avatar

## Run locally

No build step is required. Open `index.html` in a browser, or serve the folder using any simple local web server.

## Deploy on Netlify

This is a static site. Connect this GitHub repository to Netlify and use:

- Build command: leave blank
- Publish directory: `kriti-portfolio-github-ready`

Netlify will redeploy automatically whenever changes are pushed to the production branch.

## Git workflow

```bash
git pull
git add .
git commit -m "Describe your change"
git push
```

GitHub is the source of truth and version history; Netlify publishes the latest pushed production version.

## Résumé and content copying

The résumé is offered only as an image-based PDF. The published folder contains no Word document. Page text selection and routine copy actions are discouraged, while text inputs remain usable. These are deterrents: public pages and PDFs can still be copied with screenshots, OCR, or browser tools. The PDF has no searchable text layer, which limits screen-reader access and automated résumé parsing.
