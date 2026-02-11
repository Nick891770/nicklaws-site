# nicklaws-site

Personal website for Nick Laws — built with [Astro](https://astro.build/), deployed to GitHub Pages.

## Development

```bash
npm install
npm run dev
```

## Deployment

Pushes to `main` automatically build and deploy via GitHub Actions.

Live at: [nick891770.github.io/nicklaws-site](https://nick891770.github.io/nicklaws-site/)

## Custom Domain (later)

1. Register a domain (e.g. `nicklaws.com.au`)
2. Add a `CNAME` file to `public/` with the domain name
3. Point DNS A records to GitHub Pages IPs
4. Update `site` in `astro.config.mjs`
