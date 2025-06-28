# Artist Portfolio + Shop

A static site for an artist portfolio and web shop, built with [Eleventy](https://www.11ty.dev/), [Tailwind CSS](https://tailwindcss.com/), and [Snipcart](https://snipcart.com/) for e-commerce. Deployed via [Netlify](https://netlify.com/).

## 🚀 Features

- Static site generation via Eleventy
- Utility-first styling with Tailwind CSS
- Markdown-based content (`src/`)
- Nunjucks templating system
- Reusable product cards with Snipcart integration
- CI/CD via GitHub → Netlify

## 🛠 Development

```
# Install dependencies
npm install

# Start local dev server
npm run dev

# Build for production
npm run build
```

## Structure

```
src/
  index.md           # Homepage
  shop.md            # Shop page (Snipcart products)
  styles/            # Tailwind CSS source
  _includes/         # Layout and component templates
_site/               # Output folder (generated)
```

## Deployment (Netlify)

```
Build command: npm run build

Publish directory: _site
```

## Licence

MIT
