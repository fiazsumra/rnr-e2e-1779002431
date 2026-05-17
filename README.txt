RnR site export -- RnR Smoke rnr-e2e-1779002431
================================
Generated: 2026-05-17T07:24:39.746061Z
Domain: rnr-e2e-1779002431
Pages: 9
Canonical-back to: https://rnr-e2e-1779002431.example.com

Deployment options
------------------
1. Cloudflare Pages: drag this whole zip into Cloudflare Pages
   (https://dash.cloudflare.com/?to=/:account/pages) or use wrangler
   pages deploy. Phase 36 of SBG will automate this.
2. Netlify: drop the unzipped folder onto https://app.netlify.com/drop
3. Vercel: vercel deploy --prod from the unzipped folder
4. GitHub Pages: push contents to a gh-pages branch
5. Any other static host: upload the unzipped contents to web root.

Notes
-----
- Each page is a self-contained HTML file with inline CSS -- no external
  asset dependencies. Works on any static CDN.
- Canonical tags rewritten to point to https://rnr-e2e-1779002431.example.com so this static drop supports the WP money domain (Approach A+).
- Place a real branded favicon at /favicon.ico to replace the placeholder.
- robots.txt allows all crawlers and points to /sitemap.xml.
