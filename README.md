# Faza

Georgian-first electrical services website built with Astro. Content and contact numbers come from the supplied business text and banner; photography comes from the supplied project images.

## Run locally

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
npm run preview
```

The static site is generated in `dist/`. Before public launch, configure the real domain in `astro.config.mjs`, add a canonical URL, sitemap and absolute Open Graph image URL, and confirm the business copy and contact information. Noto Sans Georgian fonts are served locally; system fonts are the fallback.

Services and descriptions are visible without expanding controls. The blue-and-white layout uses the supplied logo, larger text, 14 gallery photos and two videos with native playback controls. Project photos open in a keyboard-accessible dialog. Contact links use the phone dialer and WhatsApp; there is no form backend.
