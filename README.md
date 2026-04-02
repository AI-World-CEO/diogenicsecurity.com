# Diogenesis Security Website

Marketing website for [diogenicsecurity.com](https://diogenicsecurity.com) — the behavioral immune system for AI applications.

## Deployment

### GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` / `root`
4. The `CNAME` file is already configured for `diogenicsecurity.com`
5. In your DNS provider, add:
   - `A` record: `185.199.108.153` (and `.109`, `.110`, `.111`)
   - `CNAME` record: `www` → `<username>.github.io`

### Netlify

1. Connect your GitHub repository
2. Build command: *(leave empty)*
3. Publish directory: `/`
4. Add custom domain `diogenicsecurity.com` in Domain settings

### Any Static Host

Upload the contents of this directory. The site is a single `index.html` with no build step.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Complete single-page website (HTML + CSS + JS) |
| `CNAME` | GitHub Pages custom domain |
| `.nojekyll` | Disables Jekyll processing on GitHub Pages |
| `robots.txt` | Search engine crawler rules |
| `sitemap.xml` | XML sitemap for search engines |

## Tech Stack

- Pure HTML, CSS, JavaScript
- No frameworks, no build tools, no npm
- Google Fonts (Space Grotesk, Inter, JetBrains Mono)
- Canvas API for hero animation
- Intersection Observer for scroll animations

## Product Links

- **PyPI:** https://pypi.org/project/diogenesis-sdk/
- **GitHub:** https://github.com/AI-World-CEO/Prometheus_Prime
- **Install:** `pip install diogenesis-sdk`
