# Bohdan Kopijka — Portfolio

Single-page portfolio for **Bohdan Kopijka** (web designer & developer).

Cinematic, space-themed landing page with a liquid-glass design system, looping
video backgrounds (custom rAF crossfade), and Framer Motion entrance animations.

## Tech
Fully static, CDN-only — no build step:
- React 18 (UMD) + Babel Standalone
- Framer Motion 11
- Tailwind CSS (CDN)
- Fonts: Instrument Serif + Barlow

Everything lives in a single [`index.html`](index.html).

## Sections
Hero → Services → Contact.

## Local preview
Open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 5601
# → http://localhost:5601
```

## Deploy
Hosted on **Cloudflare Pages**. Every push to `main` triggers a redeploy.

## Contact
Telegram: [@BohdanKopijka](https://t.me/BohdanKopijka)
