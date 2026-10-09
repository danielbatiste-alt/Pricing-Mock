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

1. Hero: pill "MiHQ Powered by MiCortex", title "Every price, up front / Find the right MiHQ plan for you"
2. MiHQ plans: Starter, Team, Professional (most chosen), Enterprise ("MiHQ" in brand blue in the plan names)
3. MiHQ Global and MiAudience cards, then "Everything else we charge for" as a dropdown (table; stacks into a list on mobile), then the pricing small print
4. MiResearch: MiCustom, MiBus, MiRetail; A project is not a dead end (3 steps + "Talk to Us About a Study")
5. What we quote, and why
6. In every plan *(light from here)*
7. Questions people ask (collapsed accordion, one answer open at a time)
8. Tell us the study, not your budget
9. Footer

The full-width cards (MiHQ Global, MiAudience and the charges dropdown) share one style: 20px title,
15px text, button on the right, 28/32px padding, outline buttons. Solid blue buttons are kept for the
main actions only.

Pills, buttons, nav buttons and call-to-action links use Title Case (short joining words such as a,
the, to and by stay lowercase). The "MOST CHOSEN" / "COMING SOON" pills and the table headings display
in capitals; the "MiResearch" and "Where the Two Meet" labels display as written. The mock's nav and
footer use the new product names (MiHQ, MiAudience, MiTemplates, MiBus); the live nav is configured
separately.

Copy source: "MiHQ pricing page boards" (2026-10-04), with edits agreed up to 2026-10-09
(hero pill, title and sub-headline; revised small print; MiAudience card; the one-study message shown
once; no full stops at the end of headlines and sub-headlines; "Everything else we offer" removed).

The FAQ accordion follows the Milieu inner pages (canvas-v2 / MiAudience).

## Preview locally

Open `index.html` in a browser (an internet connection is needed for the font).

## Publish with GitHub Pages

Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
The page will be live at `https://<your-username>.github.io/<repo-name>/` after a minute or two.
