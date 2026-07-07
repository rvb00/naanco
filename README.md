# Naan & Co — Website

Marketing site for Naan & Co, a concept by Chef Vineet Bhatia MBE and Ronit Bhatia
in partnership with Emirates Flight Catering, located at Emirates Group Headquarters, Level 2.

## Running it

This is a fully static site — no build step.

- Open `index.html` directly in a browser, or
- Serve the folder with any static server, e.g. `npx serve .`

## What's here

- `index.html` — the whole site, including the opening film + logo-draw intro sequence
- `styles.css` — all styling (Instrument Serif via Google Fonts, red `#E30313` on cream `#FDFDF3`)
- `assets/` — optimised images (dish cutouts with transparent backgrounds), the intro and
  Naancy films, posters, and the menu PDF served by the menu buttons

## Notes

- The intro respects `prefers-reduced-motion` (skipped entirely) and has a Skip button plus
  an autoplay-failure fallback, so nobody gets stuck.
- The rotating dish cutout above the menu swaps every 0.75 s.
- Contact email `hello@naanco.ae` should be confirmed before launch.
