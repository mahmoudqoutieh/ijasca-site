# IJASCA Publications — ijasca.net

Static website for IJASCA Publications (home, about, publish, privacy, terms, refund), hosted on GitHub Pages.

## Structure
- `index.html` — the whole site (pages switch via `#home`, `#about`, `#publish`, `#privacy`, `#terms`, `#refund`)
- `assets/` — logo and favicon
- `CNAME` — custom domain (ijasca.net)
- `404.html`, `robots.txt`, `sitemap.xml`

## Deploy
1. Push these files to the root of a GitHub repository (branch `main`).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
3. Custom domain: `ijasca.net`, then tick **Enforce HTTPS** once the certificate is issued.
