# Rishabh Prajapati: Portfolio

Interactive 3D portfolio. Plain HTML, CSS and JavaScript. No build step.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The page shell, SEO tags and a no-JavaScript fallback |
| `style.css` | All styles |
| `script.js` | All site code (routing, 3D scenes, animations, content) |
| `three.min.js`, `lenis.min.js` | Libraries (3D and smooth scrolling) |
| `about.html`, `projects.html`, `contact.html` | Redirect old links to the new pages |
| `404.html` | Sends clean URLs to the right page |
| `favicon.svg`, `og-image.png`, `apple-touch-icon.png` | Icons and social preview |

## Open it

Double-click `index.html`, or run `python3 -m http.server 8000` and visit http://localhost:8000.

## Edit your content

Open `script.js` and search for `SITE`, `PROJECTS`, `SKILLS`, `ARCHIVE` or `FEATURED`. They sit together near the top, and changing them updates every page.

## Deploy

Upload every file in this folder to the root of your GitHub repo and commit. GitHub Pages serves it.
