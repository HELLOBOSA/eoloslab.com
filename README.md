# EOLOS Design Lab

Static launch site for `eoloslab.com`.

The site is built as a self-contained HTML launch page for GitHub Pages with:

- `index.html` for the full page experience
- `CNAME` for `eoloslab.com`
- `robots.txt` and `sitemap.xml` for search indexing
- `.github/workflows/mirror-assets.yml` to mirror project images into this repo under `assets/projects/triptychs`

The public page uses local asset paths so the `.com` site is not dependent on the `.gr` domain once the mirror workflow has run.
