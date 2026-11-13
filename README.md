# tdb-landing

Landing page for **The Data-Bridge**, served at https://tdb.asvanlabs.com
via GitHub Pages. Static HTML (no build step).

- `index.html` — the page
- `CNAME` — custom domain binding for GitHub Pages
- `.nojekyll` — serve files as-is (skip Jekyll)
- `404.html`, `robots.txt`, `sitemap.xml` — error page and crawler files (update `sitemap.xml`'s `lastmod` when the page changes)
- `.well-known/security.txt` — security contact (RFC 9116), points to `security@tdb.asvanlabs.com` and the docs' Security & updates page; **renew `Expires` before 2027-11-13**
- `og.png` — the social card; `media/` — the 60-second tour video (`tour.webm`, `tour.mp4`), recorded on the community 0.13.0 image

Edit `index.html` and push to `main`; GitHub Pages redeploys automatically.
