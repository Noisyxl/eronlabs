# Eron Labs — The Forgotten Math Inside AI

Landing page for the Eron Labs course. Plain static site: one `index.html`, no build step.

## Deploy on Vercel
1. Vercel → **Add New → Project** → import this repo.
2. Framework preset: **Other**. Build command: none. Output directory: `./`.
3. **Deploy**, then **Settings → Domains** → add your domain and set the DNS records Vercel shows.

## Before launch
- Domain: https://www.eronlabs.org (eronlabs.org redirects to www). Link previews use https://www.eronlabs.org/og.png.
- Stripe Payment Links are wired (Full Stack, Pack 01–03). Promo code `ERON10` is prefilled from the code box. After payment, Stripe redirects to `/thanks` (`thanks.html`).
- Replace `[YOUR SUPPORT EMAIL]` in `index.html` (footer) and `thanks.html`.
- Replace the `[REAL STORY]` review cards and the `[ADD YOUR PAYOUT / STRIPE SCREENSHOT HERE]` box.
- Countdown deadline: `DEADLINE` near the top of the script (`2026-11-20T23:59:00+01:00`).
