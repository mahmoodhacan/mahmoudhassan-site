# Mahmoud Hassan — Academic Minimalist Website

A static bilingual personal website designed for GitHub Pages, with editable content in Pages CMS.

## Preview
Open `index.html` locally. Built-in initial content appears even without a web server. On GitHub Pages the website loads its live content from `content/en.json`, `content/ar.json`, and `content/settings.json`.

## Publishing
1. Create a public GitHub repository and upload **all files including hidden `.pages.yml` and `.nojekyll`** to its root.
2. In Settings → Pages select **Deploy from a branch**, main, root.
3. In GitHub repository Settings → Pages set custom domain `mahmoudhassan.io`.
4. At your DNS registrar configure the apex A records according to GitHub's current official docs; do not change existing email MX/TXT records. Wait for verification and activate Enforce HTTPS.
5. Sign in to https://pagescms.org/ with GitHub and select this repository. Edit Homepage EN/AR and Links & images.

## Notes
- Portrait, authentic book cover, verified publication citations, and external profiles must be supplied; no invented scholarly references.
- The publication area is explicitly placeholder content pending verification.
- When changing Pages CMS content, GitHub Pages updates on the next deployment.
- Static fallback content embedded in the HTML is for offline preview only; the hosted site uses live JSON.
