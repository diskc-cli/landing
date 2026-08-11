# diskc landing page

A dependency-free, static landing page for [diskc](https://github.com/debugc-clis/diskc), the Linux CLI for investigating disk pressure.

## Local preview

Run a static server from this directory:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Before deployment

See [DEPLOY.md](DEPLOY.md). In particular, set the production canonical URL, `og:url`, and absolute social image URLs in `index.html` before publishing.
