# The Quilt Handbook

> A complete guide to the git.pp substrate: from "what is it" to "running it at the edge".

## What this is

A single-page HTML+CSS doc that covers the full Quilt stack:
- The concept (records, leaves, roots, fold, state)
- A worked example (one record → leaf → root → fold)
- Record anatomy
- The 7 fold ports
- Write your first record (5-minute tutorial)
- Install a fold port (per language)
- Run the fold at the edge (gitpp-fold-edge)
- Verify a checkpoint
- Deploy the hub
- Write a new fold port (the contract)
- Troubleshooting
- Quick reference

The handbook is one HTML file. No JS, no build, no install. Just open it in a browser.

## View

Open `index.html` in any browser, or deploy it to a static host:

```bash
# GitHub Pages
gh-pages branch → index.html

# Cloudflare Pages
wrangler pages deploy .

# Plain static server
python3 -m http.server 8000
```

## Edit

The doc is one file. Edit `index.html` directly. The CSS uses CSS custom
properties for theming, so you can re-skin it without touching the HTML.

## License

MIT. Re-use, re-skin, re-publish.
