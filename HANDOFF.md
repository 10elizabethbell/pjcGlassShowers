# PJC Glass & Showers — handoff at ~60%

**Live file:** index.html · **Repo:** https://github.com/10elizabethbell/pjcGlassShowers · **Built:** 2026-10-08 from Muse brief (run 2026-10-08, FB group flyer post)

## What's built
- **World:** fogged window glass. Charcoal-blue ground (`#18222d`, not black), PJC logo red `#e2231a` as the only loud colour, pale glass `#e8f0f3` for light sections, white four-lite sash lifted from the window icon in their logo.
- **Signature element:** the hero is a fogged window. Fog breathes (drifting steam) and creeps back after it's cleared; water beads grow, merge, and run down in stick-slip lurches, clearing trails. Finger or mouse wipes the fog and shoves the beads (spring back with a wobble); shove hard and a bead breaks loose and runs. Behind the fog: "FULL SERVICE" (their flyer's words) and "HOMES · BUSINESSES · COMPLEXES". A ghost wipe runs on load and after 9s idle so people see it's wipeable.
- **Carried through:** the close has a second fogged window with their logo outside it; section seams are the same animated water lines as Blessed's.
- **Sections:** top bar (logo + call pill) → hero (headline, service pitch, Call / Text a photo) → What PJC fixes (6 flyer services, each row opens a pre-filled text naming the service) → One house or the whole complex (Homes / Businesses / Entire complexes) → How it works (3 steps) → close (logo window, name, Call / Text) → footer with "Demo one-pager — free sample."
- **Contact:** call is primary everywhere (`tel:+17325797813`); text is secondary. Sticky Call/Text bar on phones once the hero buttons scroll away.
- **Logo:** Muse couldn't get it; I pulled the Facebook profile image via og:image (their banner logo, cropped, ~14 KB WebP embedded once). Whole file ~62 KB.

## Assumptions I made
- **New Jersey** as the area: from the 732 area code and the NJ contractor group they post in. No towns named anywhere.
- **Service descriptions** are mine, explaining the trade problem (e.g. fogged unit = failed seal), not claims about PJC's methods or prices.
- **How-it-works copy** ("Tell PJC what's wrong and get a price") and the Homes / Businesses / Entire complexes rows are mine, built from the flyer's "Residential + Commercial" and "Service Entire Complex".
- **Shower enclosures** described as "glass shower doors and enclosures"; their flyer says only "Shower Enclosure".
- **Commercial doors** described as storefront/commercial; flyer says "Commercial Door Repair".
- **Texts:** unknown if 732-579-7813 takes texts; text links are secondary but present on every service row. If it's a landline, set `TEXTS_OK = false` at the top of the contact script: every text link becomes a call link and the services intro changes. (The buttons still say "Text"; relabel or hide them then.)
- **Font:** system stack per house style (Impeccable's craft floor would want a sourced display face; your rule wins).
- **Headline** "Clear glass. Working windows." is mine.

## Placeholders and gaps
- **Link preview:** `og:image` points at `assets/og.jpg` on raw.githubusercontent.com (logo on slate, 1200×630). Swap to the final host's URL once the site is deployed, and add `og:url`.
- No work photos, no before/afters, no reviews: the page shows none and says nothing about them. Photos wanted.
- No hours, owner name, email, address, towns served, years in business.
- Name: Facebook page says "PJC Glass & Showers", logo says "GLASS AND SHOWERS". Used "&" in text.

## Questions for the owner
- Does 732-579-7813 take texts?
- Which towns / counties do you cover?
- Hours, and do you do emergency board-ups / same-day?
- Photos of jobs (fogged units before/after would be perfect for a slider), shower enclosures you've installed.
- Free estimates? Any warranty on sealed units?
- Owner's first name for the close ("Ask for ___").
- Which service brings in the most work (to lead with it)?

## Ideas not built (yours to pick)
- **Runner-up world:** rain on a window at night with streetlight bokeh behind (same bead engine, darker scene). Others considered: shower steam on tile, squeegee streaks, light caustics through shower glass, sash-balance springs.
- Before/after slider for fogged insulated units once photos exist (desktop beside the list, phone under the row).
- Booking form page (`book.html`) for property managers: complex name, units, issue per unit.
- Each service row could get its own tiny fogged pane icon.
- Close pane could reveal a "Call 732-579-7813" decal on the glass instead of the logo.
- Tune: `REGROW` (fog return speed), `WIPE_R`, `BEAD_DENSITY`, `GHOST_IDLE` — all named at the top of the panes IIFE.

## Not verified
- Real-device touch (verified only with simulated touch/mouse sweeps in headless Chrome).
- Real SMS handoff on iOS/Android and inside Facebook's in-app browser.
- Frame rate on older phones (canvas redraws the full pane each frame; ~60 beads on phones, 150 on desktop).
- Impeccable detector ran in degraded regex mode (its parser modules aren't installed): it returned no findings, which is an undercount.
