# Prateek Chatterjee — Portfolio (rebuilt homepage)

Drop-in replacement for your `index.html`. Senior-level redesign with a new
design system, collapsing pill nav, animated hero, emphasized metrics, and
WCAG-AA colors + focus styles.

## How to deploy (copy-paste)

1. **Replace your `index.html`** with the one in this folder.
2. **Keep your existing `images/` folder.** The six case-study images load from
   it by their original names:
   - `images/peri.png` (Periscope)
   - `images/bspd.png` (Brightspeed)
   - `images/assist.png` (Inova Assist)
   - `images/2.png` (ACO-MS)
   - `images/clinical_analytics_hero.png` (Clinical Analytics)
   - `images/4.png` (VR)
3. **Keep `images/res.pdf`** for the résumé button.

That's it. Push and it's live.

## What's already embedded (no files needed)

These three images you provided are encoded directly into `index.html`, so they
show everywhere with zero setup:

- Your **headshot** → the round avatar in the nav
- Your **portrait** → the About section
- The **Inova logo** (background removed) → the hero footer

For convenience, processed copies are also included in `images/` in case you
ever want them as files:
- `images/avatar.jpg`
- `images/about.jpg`
- `images/inova-logo.png`

## Notes

- Self-contained: fonts load from Google Fonts, icons are inline SVG.
- If you open `index.html` locally without your `images/` folder, the six case
  cards fall back to clean colored blocks (no broken-image icons) — they appear
  as soon as the folder is present.
- Accessibility: AA contrast throughout, visible keyboard focus, reduced-motion
  fallback, semantic landmarks, 48px touch targets.
