# West Hollywood Directory

Local business directory for West Hollywood, CA.

- **Live site:** https://westhollywooddirectory.com
- **Stack:** Hugo (static site generator) + Cloudflare Pages
- **Source of truth:** every business listing is a markdown file in `content/listings/`

## Local development

```bash
hugo server -D
```

Opens a live-reloading preview at http://localhost:1313.

## Deploy

Push to `main` — Cloudflare Pages rebuilds automatically.

## Adding a listing

Copy `content/listings/_template.md`, fill in the frontmatter, save with a URL-friendly filename (e.g. `gracias-madre.md`), then `git push`.
