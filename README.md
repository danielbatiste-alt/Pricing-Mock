# Milieu — Pricing page mock

A front-end mock of the Milieu pricing page, built to sit seamlessly alongside the
[mili.eu](https://mili.eu/) landing page.

**This is a mock-up.** Copy is from the "MiHQ pricing page boards" doc (2026-10-04) plus agreed edits and every button/link is a placeholder.

## What's in it

A single self-contained file, `index.html` — plain HTML, CSS and JS, no build step,
no dependencies beyond the Archivo font from Google Fonts.

## Design

Uses the mili.eu landing page design system (taken from its `main.css` / `nav.css`):

- **Type:** Archivo, all weights
- **Dark sections** (hero → MiResearch): `#1A1A1A` page, `#242423` cards, `#48ADFF` / `#FFDFA7` accents
- **Light sections** ("In every plan" → closing CTA): `#F1F1F1` page, white cards, `#0067C2` accents
- **Dark → light fade on scroll**, same logic as the landing page: the background blends
  `#1A1A1A → #F1F1F1` as the light sections enter (starting at 85% of the viewport, over half a viewport height)
- **Nav** switches between its dark and light frosted states, as on the landing page
- **Buttons:** pill shape, `#0067C2` primary
- **Motion:** scroll reveal and button spring hover, as on the landing page
- Responsive: desktop, tablet and mobile

## Page structure

1. Hero, "Every price, up front. Find the right MiHQ plan for you"
2. MiHQ plans: Starter, Team, Professional (most chosen), Enterprise, plus MiHQ Global and the pricing small print
3. MiResearch: MiCustom, MiBus, MiRetail; A project is not a dead end; Back to plans
4. What we quote, and why; Only need one study?
5. In every plan *(light from here)*
6. Tell us the study, not your budget
7. Footer

Copy source: "MiHQ pricing page boards" (2026-10-04), with final edits agreed on 2026-10-06
(new hero title and sub-headline, revised small print, no full stops at the end of headlines and
sub-headlines; "Everything else we charge for", "Everything else we offer" and the FAQ removed).

## Preview locally

Open `index.html` in a browser (an internet connection is needed for the font).

## Publish with GitHub Pages

Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
The page will be live at `https://<your-username>.github.io/<repo-name>/` after a minute or two.
