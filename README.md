# AIH SaaS Landing Page

Modern, conversion-focused landing page for AIH backup service.

## Features

- 🎨 Modern dark theme design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast and lightweight
- 🎯 Conversion-optimized CTAs
- 💳 Pricing section ready for Stripe integration
- 📊 Dashboard preview section

## Quick Start

### Local Development

```bash
cd aih-saas-landing
python3 -m http.server 8000
# Open http://localhost:8000
```

### Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Initial landing page"
gh repo create aih-saas-landing --public --source=. --push
# Go to GitHub → Settings → Pages → Deploy from main branch
```

### Deploy to Railway

1. Push to GitHub
2. Connect repo to Railway
3. Deploy as static site (or use `npx serve`)

## Tech Stack

- Pure HTML/CSS (no frameworks)
- No JavaScript dependencies
- Fast loading (22KB)
- SEO-friendly structure

## Customization

### Colors

Edit `:root` variables in `<style>`:

```css
:root {
    --primary: #22c55e;      /* Main green */
    --primary-dark: #16a34a;  /* Darker green */
    --dark: #0f172a;          /* Background */
    --darker: #020617;        /* Darker bg */
    --light: #f8fafc;         /* Text color */
    --gray: #64748b;          /* Secondary text */
}
```

### Content

Edit the HTML directly - all content is in plain HTML.

## Production Build

No build step required. Just upload `index.html` to any static host:

- GitHub Pages ✅
- Railway ✅  
- Netlify ✅
- Vercel ✅
- Cloudflare Pages ✅

## License

MIT - Free for commercial use.
