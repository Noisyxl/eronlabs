# Eron Labs — The Forgotten Math Inside AI

Landing page for the Eron Labs course. Plain static site: one `index.html`, no build step.

## Deploy on Vercel
1. Vercel → **Add New → Project** → import this repo.
2. Framework preset: **Other**. Build command: none. Output directory: `./`.
3. **Deploy**, then **Settings → Domains** → add your domain and set the DNS records Vercel shows.

## Before launch
- In `index.html`, replace `/og.png` in the `og:image` and `twitter:image` tags with the full URL (`https://YOURDOMAIN/og.png`) so link previews work on X.
- Replace the checkout links: `#checkout-full`, `#checkout-p1`, `#checkout-p2`, `#checkout-p3`.
- Replace `[YOUR SUPPORT EMAIL]` in the footer.
- Replace the `[REAL STORY]` review cards and the `[ADD YOUR PAYOUT / STRIPE SCREENSHOT HERE]` box.
- Countdown deadline: `DEADLINE` near the top of the script (`2026-11-20T23:59:00+01:00`).
