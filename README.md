<<<<<<< HEAD
# Backstage Live — Marketing Site

Static marketing site for [Backstage Live](https://backstagelive.app), the iPad fulfillment app for live commerce sellers. Operated by SlowArcs LLC.

## What's here

| File | Purpose |
|---|---|
| `index.html` | Homepage — product overview, beta-access CTA |
| `support.html` | Support page — FAQ + contact |
| `privacy.html` | Privacy Policy (canonical source: `../docs/legal/privacy.md`) |
| `terms.html` | Terms of Service (canonical source: `../docs/legal/terms.md`) |
| `404.html` | Not-found page |
| `favicon.svg` | App icon, used as favicon |
| `robots.txt` | Allows all crawlers, points to sitemap |
| `sitemap.xml` | Lists the four canonical URLs |

## Deploy

Deployed via Cloudflare Pages, auto-publishes on push to `main`.

URL structure:

- `/` — homepage
- `/support` — support page
- `/privacy` — privacy policy
- `/terms` — terms of service

Cloudflare Pages serves `*.html` files at extension-less URLs automatically.

## Editing

The legal pages mirror canonical Markdown sources at `docs/legal/privacy.md` and `docs/legal/terms.md` (in the parent project). Update the Markdown first, then re-render the HTML to keep them in sync.
=======
# Backstage Live — Legal Pages

This repository hosts the public legal pages for the [Backstage Live](https://apps.apple.com/) app.

## Live URLs

- **Privacy Policy:** https://backstageliveapp.github.io/backstage-legal/privacy
- **Terms of Service:** https://backstageliveapp.github.io/backstage-legal/terms


## Editing

Each page is a Markdown file at the root:

- `privacy.md`
- `terms.md`

Push edits to `main` and GitHub Pages re-publishes within ~30 seconds.

## Hosting

Built with GitHub Pages + Jekyll's minimal theme. Configuration lives in `_config.yml`.
>>>>>>> d24185e5d9a126a1eab2aaeba02b6596bb613e1b
