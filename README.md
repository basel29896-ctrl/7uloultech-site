# 7uloul tech — حلول

Premium digital-solutions studio website (Amman, Jordan). Single-file, dependency-free
front-end: web/app development, branding, UX, and POS systems.

**Live:** enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) → served from `index.html`.

## Contents
- `index.html` — the full site (HTML/CSS/JS in one file, no build step)
- `assets/logo-primary.svg` — horizontal logo lockup (7T monogram)
- `assets/logo-board.svg` — full logo system / brand sheet
- `assets/appicon.svg` — square app icon / favicon source

## Features
- Dark-luxury navy / royal-blue / gold palette (#1A1A2E · #16213e · #0f3460 · #efc07b)
- Dimensional depth-on-scroll, intro ring loader, 3D rotating 7T cube
- Sliding text-swap nav, odometer counters, infinite marquee
- Rule-based chat widget with email + WhatsApp quick actions
- Fully responsive, `prefers-reduced-motion` aware

## Contact routing
Edit the two lines in the `CONTACT ROUTING` block near the bottom of `index.html`:
```js
const CONTACT_EMAIL='basel29896@gmail.com';
const WHATSAPP_NUMBER='962795032137';
```
These feed the email + WhatsApp buttons, footer links, and chat actions.

## License
© 2026 7uloul tech. All rights reserved.
