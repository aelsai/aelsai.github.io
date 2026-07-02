# Elsai Mati Asefa — personal academic website

A static, professional personal site. Plain HTML + CSS — no build step, no
Jekyll, no dependencies. Every page works by opening the file directly in a
browser or serving the folder.

## Structure

```
professional-site/
├── index.html          Home (about, current research, methods, selected pubs)
├── research.html       Research themes, ongoing/past projects, methods
├── publications.html   Peer-reviewed papers by year, talks, grants & awards
├── teaching.html       Teaching appointments, mentoring, community work
├── 404.html            Not-found page
├── styles.css          Single shared stylesheet
├── .nojekyll           Tells GitHub Pages to serve files as-is
└── assets/
    ├── portrait_new.jpg
    ├── Elsai_Mati_Asefa_CV.pdf
    ├── favicon.svg
    └── figure-*.jpg / .png   Research figures
```

## Preview locally

Just open `index.html` in a browser. To test relative links exactly as they’ll
behave when deployed, serve the folder instead:

```bash
# from inside professional-site/
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy to GitHub Pages

1. Copy the contents of this folder to the root of your `aelsai.github.io` repo
   (or point Pages at this subfolder).
2. Commit and push to the `main` branch.
3. In the repo settings under **Pages**, set the source to the `main` branch.

The site is live at `https://aelsai.github.io/` a minute or two later.

## Editing content

- Text lives directly in the `.html` files — edit the paragraphs in place.
- To add a publication, copy an existing `<li>` inside the relevant year list in
  `publications.html`.
- Colours, fonts, and spacing are all defined as CSS variables at the top of
  `styles.css` (`:root { ... }`) — change them in one place to restyle the site.
- Replace `assets/portrait_new.jpg` to update the portrait; keep the same
  filename or update the `<img src>` in `index.html`.
