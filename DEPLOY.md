# diskc landing page

This folder is a static, dependency-free landing page for:
https://github.com/diskc-cli/diskc

## Before production deployment

1. Set the real production domain in `index.html`:
   - add `<link rel="canonical" href="https://YOUR-DOMAIN/">`
   - add `<meta property="og:url" content="https://YOUR-DOMAIN/">`
   - make `og:image` and `twitter:image` absolute URLs
2. Add a `LICENSE` file to the GitHub repository before broadly marketing the project as open source.
   The repository was public and its README contained only `# diskc` when this page was generated.
3. Update the Homebrew status only after the formula is actually published.
4. If desired, add a sitemap after a production domain exists.
5. The website disclaimer is general wording, not legal advice. Have counsel review it if legal enforceability matters.

## Deploy

Upload this directory to any static host (Cloudflare Pages, GitHub Pages, Netlify, S3, etc.).

## Smoke test

After deploy, verify the canonical URL and social preview image in the page source, test the source-install command copy button over HTTPS, and check the layout at mobile and desktop widths.
