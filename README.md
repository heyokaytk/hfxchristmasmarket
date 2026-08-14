# Halifax Christmas Market

Website for Halifax Christmas Market — an indoor holiday market at Pavilion 22 on the Halifax Waterfront, December 4–6, 2026. 140 curated Nova Scotia vendors, timed entry from $12, kids always free.

Live at [hfxchristmasmarket.ca](https://hfxchristmasmarket.ca).

## Stack

Static single-file HTML (`index.html`), no build step. Deployed via GitHub Pages, fronted by Cloudflare DNS (proxied) — same pattern as [okaytk.com](https://okaytk.com), [bumpandgrindhfx.com](https://bumpandgrindhfx.com), and [goldenservice.ca](https://goldenservice.ca).

## SEO

- `robots.txt` / `sitemap.xml` at root
- `CNAME` sets the custom domain for GitHub Pages
- JSON-LD structured data: `Organization`, `Event` (Dec 4–6, 2026), `FAQPage`
- Open Graph / Twitter Card meta tags, canonical URL

## Structure

| File | Purpose |
|------|---------|
| `index.html` | The site |
| `IMAGES/` | Logo and social share assets |
| `favicon-16.png`, `favicon-32.png`, `apple-touch-icon.png` | Favicons |
| `robots.txt`, `sitemap.xml`, `CNAME` | SEO / hosting config |

## Deploying

Push to `main` — GitHub Pages rebuilds automatically. If a change doesn't appear live, purge the Cloudflare cache in addition to the push.
