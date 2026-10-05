# DyeMill — Free Color Palette Generator

Forge color palettes: harmonies, spacebar workflow, image-to-palette
extraction, WCAG contrast checker, Tailwind/CSS export.
**100% client-side. No account. No uploads. Free forever.**

## Features

- 7 harmonies from any base color (or dice-random)
- Lock colors, re-roll the rest with Space
- Click-to-copy HEX/RGB/HSL
- Export: CSS variables, Tailwind config, HEX/RGB lists, SVG + PNG strips
- WCAG contrast checker with live preview
- Extract dominant palette from any photo (in-browser)
- Dark/light mode, installable PWA, works offline

## Privacy

Everything runs in your browser. Photos and palettes never leave the device
(localStorage only).

The page loads a small cookieless analytics script (Umami) on the production
hostname only, to count visits. It sets no cookies, builds no profile, and never
sees your photos or palettes, because all extraction happens locally. Load the
page once and use it offline and nothing is sent at all.

## Run it

Open `index.html` in a browser — or host anywhere static
(Vercel, Netlify, GitHub Pages, Cloudflare Pages).

## License

MIT
