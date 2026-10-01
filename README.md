# Milieu — Pricing page mock

A front-end mock of the Milieu pricing page, built to sit seamlessly alongside the
[mili.eu](https://mili.eu/) landing page.

**This is a mock-up.** Copy is temporary (from the "Pricing page, desktop" and
"MiResearch, the services arm" content docs) and every button/link is a placeholder.

## What's in it

A single self-contained file, `index.html` — plain HTML, CSS and JS, no build step,
no dependencies beyond the Archivo font from Google Fonts.

## Design

Uses the mili.eu landing page design system (taken from its `main.css` / `nav.css`):

- **Type:** Archivo, all weights
- **Dark sections** (hero → MiResearch): `#1A1A1A` page, `#242423` cards, `#48ADFF` / `#FFDFA7` accents
- **Light sections** ("Everything else we do" → closing CTA): `#F1F1F1` page, white cards, `#0067C2` accents
- **Dark → light fade on scroll**, same logic as the landing page: the background blends
  `#1A1A1A → #F1F1F1` as the light sections enter (starting at 85% of the viewport, over half a viewport height)
- **Nav** switches between its dark and light frosted states, as on the landing page
- **Buttons:** pill shape, `#0067C2` primary
- **Motion:** scroll reveal and button spring hover, as on the landing page
- Responsive: desktop, tablet and mobile

## Page structure

1. Hero — "You shouldn't have to ask what the software costs."
2. Priced on this page / Quoted, and here is why
3. Do it yourself (MiHQ) / Have us do it (MiResearch)
4. The bridge
5. MiHQ plans — Starter, Team, Professional (most chosen), Enterprise, Global
6. Reaching respondents
7. MiResearch — MiCustom, MiBus, MiRetail · A project is not a dead end · Back to plans
8. Everything else we do *(light from here)*
9. In every plan
10. Questions people actually ask
11. Tell us the study, not your budget
12. Footer

## Preview locally

Open `index.html` in a browser (an internet connection is needed for the font).

## Publish with GitHub Pages

Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
The page will be live at `https://<your-username>.github.io/<repo-name>/` after a minute or two.
