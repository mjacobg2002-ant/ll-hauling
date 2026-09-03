# LL Hauling — Homepage Redesign (Demo)

A modern, high-converting homepage concept for **LL Hauling** — fast, reliable & affordable junk removal in Northern Virginia.

**Live demo:** _(Vercel URL after deploy)_
**Current site:** https://llhauling.com

## What's inside
- Single-file, dependency-free `index.html` — loads instantly, works on any host.
- Fully responsive with a sticky mobile call/quote bar.
- Sections: hero, trust strip, services, "how it works", price-comparison vs. big providers, results gallery, reviews, service area map, quote form, footer.
- Real brand cues preserved: red brand color, "Junk Removal Made Simple." tagline, phone `571-373-7921`, email `LLHaulingServices@gmail.com`, and the three core services.
- Accessible, SEO-ready (title, meta description, Open Graph), fast (no framework).

## Before going live — quick handoff notes
1. **Photos** — the gallery/hero use tasteful stock placeholders that gracefully hide if they don't load. Swap the `src` values for real LL Hauling job photos (before/after shots convert best).
2. **Quote form** — currently shows a success message client-side (demo). Point it at Formspree, a Google Form, or the client's CRM by editing the `form` submit handler / adding a `<form action>` near the bottom of `index.html`.
3. **Service area** — cities listed (Fairfax, Arlington, etc.) are inferred from the 571 area code; confirm the exact coverage with the client.
4. **Hours** — footer shows "Open 7 days · 7am–7pm" as a placeholder; update to real hours.

## Deploy
Static site — deploys as-is on Vercel (no build step). Just import the repo and ship.
