# Elsai Mati Asefa — Professional Academic Website

A clean static academic website for GitHub Pages. The design is intentionally simple: no build system, no JavaScript dependency, and no external services required.

## What changed in this revision

- Rebuilt the visual identity around a calmer editorial design: warm background, dark scientific typography, deep-teal accent, and restrained card system.
- Updated the homepage hierarchy so the research identity appears immediately: contaminant fate, food systems, trade routing, dietary exposure, body burden, and risk.
- Added a reusable source-to-dose research framework diagram.
- Replaced the placeholder portrait with `assets/portrait.png`.
- Expanded ambiguous shorthand on the homepage, including “Sub-Saharan Africa” and full journal names for JHM/STOTEN.
- Added CV and Contact actions to the top navigation.
- Reorganized the publications page with selected publications before the full publication list.
- Kept the site fully static and GitHub Pages friendly.

## Files

```text
.
├── index.html
├── research.html
├── publications.html
├── teaching.html
├── styles.css
├── 404.html
├── assets/
│   ├── Elsai_Mati_Asefa_CV.pdf
│   ├── favicon.svg
│   ├── portrait.png
│   ├── portrait-placeholder.svg
│   └── site-card.svg
└── .nojekyll
```

## Publish on GitHub Pages

1. Upload all files in this folder to the repository root.
2. In GitHub, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/root` folder, then save.
5. Wait for GitHub Pages to finish deployment.

## Update the CV

Replace `assets/Elsai_Mati_Asefa_CV.pdf` with the newest PDF using the same filename. No HTML changes are needed if the filename stays the same.

## Update the portrait

Replace `assets/portrait.png` with a new transparent-background or clean portrait image using the same filename. A vertical crop works best in the current profile card.

## Maintenance notes

- Keep all page-level navigation labels identical across `index.html`, `research.html`, `publications.html`, `teaching.html`, and `404.html`.
- Keep publication metadata curated manually on `publications.html`; use Google Scholar for live bibliometrics.
- The stylesheet is centralized in `styles.css`.
