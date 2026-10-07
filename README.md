# Digital Shepherds Limited: website

Static marketing site for Digital Shepherds Limited (company number 16374308), published with GitHub Pages at
https://naveen2407.github.io/digital-shepherds/

## Structure
- `index.html`: single-page site (hero, about, services, why us, contact, footer)
- `404.html`: self-contained not-found page
- `assets/styles.css`, `assets/main.js`: styles and the mobile menu script
- `assets/favicon.svg`, `assets/og-image.png`: icon and social share image
- `sitemap.xml`, `robots.txt`, `.nojekyll`

No build step. All internal links are relative, so the site works under the `/digital-shepherds/` project path.

## Publish
Push these files to the root of the `digital-shepherds` repository, then go to Settings → Pages → Deploy from a branch → `main` / root.

## Preview locally
    python3 -m http.server 8000
then open http://localhost:8000/
