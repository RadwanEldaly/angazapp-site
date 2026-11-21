# إنجاز / Enjaz — Riyadh sewage services website

Static Arabic (RTL) website for Enjaz sewage suction & drain-unclogging services in Riyadh.
Live: https://www.angazapp.online/

## Stack
- Plain HTML pages, Tailwind CSS via CDN (`cdn.tailwindcss.com`), vanilla JS inline
- Google Fonts: Alexandria, Cairo, IBM Plex Sans Arabic, Material Symbols
- Google tag `G-S0ZVFWWG5M`
- Hosted on Vercel (static, no build step)

## Structure
```
index.html              Home
services.html           Services guide
drain-unclogging.html   Drain unclogging
suction-truck.html      Suction truck
coverage.html           Service area
how-it-works.html       How ordering works
about.html              About
contact.html            Contact
media/                  Images + operation videos
robots.txt, sitemap.xml SEO
```

## Run locally
```bash
npx serve .
```

## Deploy
Import the repo in Vercel (Framework Preset: **Other**, no build command, output = root).
