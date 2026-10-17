---
name: PJC Glass & Showers
description: A fogged window you wipe clear with your own finger; logo red on a charcoal-blue ground, phone first.
colors:
  logo-red: "#e2231a"
  logo-red-deep: "#b5150e"
  slate: "#18222d"
  slate-2: "#1f2c39"
  slate-3: "#2a3a4a"
  window-glass: "#e8f0f3"
  ink: "#142029"
  ink-soft: "#3d5262"
  mist: "#c3d3dc"
  white: "#ffffff"
  sash-white: "#f3f6f7"
  water-blue: "#7fb6dc"
  water-pale: "#bfe0f0"
  focus-blue: "#2d8fd8"
  facebook-mark: "#8cc3ec"
  sky-warm: "#f6dcc0"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.45rem, 11.2vw, 5.4rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 8.6vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.3rem, 6vw, 1.75rem)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "0.01em"
  display-wide:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(3.4rem, 5.2vw, 4.8rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  subhead:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.7rem, 7vw, 2.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  title-lg:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.45rem, 6.4vw, 2rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.55
  body-sm:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.55
  micro:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 700
    lineHeight: 1.4
rounded:
  sm: "6px"
  pane: "8px"
  md: "10px"
  pill: "999px"
  circle: "50%"
spacing:
  gut-phone: "16px"
  gut-wide: "32px"
  stack: "10px"
  row: "18px"
  block: "22px"
  wide-gap: "56px"
components:
  button-primary:
    backgroundColor: "{colors.logo-red}"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "0 22px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.logo-red-deep}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "0 22px"
    height: "56px"
  button-line-on-glass:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    height: "56px"
  call-pill:
    backgroundColor: "{colors.slate-3}"
    textColor: "{colors.white}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: "44px"
  service-row-cue:
    backgroundColor: "{colors.white}"
    textColor: "{colors.logo-red}"
    rounded: "{rounded.circle}"
    size: "44px"
  service-row-cue-active:
    backgroundColor: "{colors.logo-red}"
    textColor: "{colors.white}"
  step-number:
    backgroundColor: "{colors.logo-red}"
    textColor: "{colors.white}"
    rounded: "{rounded.circle}"
    size: "48px"
---

# Design System: PJC Glass & Showers

## Overview

**Creative North Star: "The Fogged Window"**

The page is a pane of glass the visitor is standing behind. Charcoal-blue ground, pale window-glass sections, a white four-lite sash lifted from PJC's own logo icon, and logo red as the only loud colour. The material is condensation: fog that breathes and creeps back, beads that grow, merge and run, and seams between sections that move like water sheeting off glass. The signature is touch: drag a finger across a pane and it clears, the same thing PJC does to fogged insulated units for a living.

Density is phone-first and tradesperson-direct: big heavy italic uppercase headings, short plain paragraphs, full-width tap targets, and a call action never more than one thumb away. Desktop is an adaptation of the phone layout, not a separate design. Everything ships in one static file: system fonts, inline SVG icons, one inlined logo, canvas-drawn scenes; no photography.

**Key Characteristics:**
- Logo red (#e2231a family) is the only saturated colour; everything else is slate, glass or mist.
- Dark slate and pale glass sections alternate, joined by animated water-seam SVGs, never by hard edges.
- Headings are system sans at weight 900, italic, uppercase, tight (0.98 line-height), echoing the logo's heavy italic "PJC".
- The fogged-glass pane is the one signature component; it appears in the hero and the close.
- Call is always primary (solid red), text is always secondary (outline).
- Motion is ambient and material (fog, beads, water), paused off screen, and reduced to a still frame on request.

## Colors

Two grounds (dark slate, pale glass), one loud red, and a pair of water blues that only appear inside the material.

### Primary
- **Logo Red** (`logo-red`): the PJC logo red. Primary buttons, the red half of split headlines, step numbers, the service-row cue on press, text selection, caret, the call-pill phone icon, the "FULL SERVICE" words behind the hero fog.
- **Deep Logo Red** (`logo-red-deep`): hover and border state of the primary button only.

### Neutral
- **Slate** (`slate`): page ground, hero, footer, theme-color. Charcoal-blue, never black.
- **Slate 2** (`slate-2`): the "who it's for" and "how it works" band, one step lighter than the page.
- **Slate 3** (`slate-3`): raised fill on slate (the top-bar call pill) and the dark stroke in seams leaving a glass section.
- **Window Glass** (`window-glass`): ground of light sections (services, close).
- **Ink** (`ink`): text and outline-button stroke on glass; the 2px rule above the service list.
- **Ink Soft** (`ink-soft`): secondary text on glass.
- **Mist** (`mist`): secondary text on slate (pitch, row descriptions, footer).
- **White** (`white`): primary text on slate, the service-row cue disc, the bright middle line of light-bound seams.
- **Sash White** (`sash-white`): the window frame and four-lite sash bars around every pane. Slightly cool, so it reads as painted frame rather than paper.

### Water (material only)
- **Water Blue** (`water-blue`) and **Water Pale** (`water-pale`): seam stroke lines and the pane's pre-canvas sky fallback. **Sky Warm** (`sky-warm`) is the horizon at the bottom of the panes' sky, material-only like the water blues. They never colour text, buttons or section grounds.

### Named Rules
**The One Loud Colour Rule.** Logo red is the only saturated colour on the page. Water blues stay inside seams and panes; nothing else competes with red.

**The Never Black Rule.** The dark ground is slate (`slate`), never #000. Depth on slate comes from the slate-2 / slate-3 steps.

## Typography

**Display Font:** System sans stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** Same stack.

**Character:** One family, two voices. Headings at 900 italic uppercase carry the logo's heavy italic "PJC" into the page; body at 400 is plain and readable. The system stack is a deliberate house choice for this pitch-site family: zero font bytes on cellular in a Facebook in-app browser.

### Hierarchy
- **Display** (900 italic uppercase, clamp(2.45rem, 11.2vw, 5.4rem) on phone, clamp(3.4rem, 5.2vw, 4.8rem) at 1000px+, 0.98): the hero headline only, with its second clause in logo red.
- **Headline** (900 italic uppercase, clamp(2rem, 8.6vw, 3.6rem), 0.98): section headings. The close and "how it works" run slightly off this (9vw ceiling 3.6rem; 7vw ceiling 2.6rem) as the section's weight in the story demands.
- **Title** (900 italic uppercase, clamp(1.3rem, 6vw, 1.75rem), 1.02): service names, audience rows (up to 2rem), step titles (1.3rem).
- **Body** (400, 17px, 1.55): all paragraphs. Pitch scales to clamp(17px, 4.6vw, 20px) with max 34em; section intros max 36em. Descriptions under titles drop to 16px.
- **Label** (800, 17px, 1.1, +0.01em): button text and the call pill (15px). Phone numbers always use tabular numerals.

### Named Rules
**The Logo Voice Rule.** Every h1/h2/h3 is weight 900, italic, uppercase, -0.02em, balanced wrapping. Body copy is never italic or uppercase.

**The Split Headline Rule.** A headline may turn its final clause logo red to land the benefit ("Clear glass. *Working windows.*"); one red clause per heading, never a red word mid-sentence.

## Layout

Phone-first base, single column, with a 16px gutter inside a centred container (max 1180px).

- **Base (under 760px):** everything stacks. Hero is text then pane (16:10). Buttons are full-width, stacked 10px apart. Service list is one column of rows; audience rows and steps stack.
- **760px+:** gutter widens to 32px; Button pairs sit side by side at their natural widths, left-aligned. Service list becomes two columns (48px column gap); audience rows and steps become three columns (32px gap). The Text button swaps "a photo" for the full number.
- **1000px+:** hero becomes a two-column grid (1.15fr text / 1fr pane, 56px gap, vertically centred) and the pane goes 5:4. The close becomes pane-left / copy-right (1.1fr / 1fr, 56px gap). Section padding grows to 64px top / 72px bottom.

Rhythm: 10px between paired actions, 18px row padding, 20 to 22px between a heading block and its content, 34 to 44px section padding on phones.

**The Thumb Reach Rule.** The phone number sits in the header's top-right corner as a 44px tap-to-call pill, once per screen. Under the headline there is one 56px full-width Text button; no Call button there and nothing fixed to the bottom of the screen.

## Elevation & Depth

Depth comes from tonal steps (slate, slate-2, slate-3) and from the glass itself, with soft dark-slate shadows used only under objects that physically sit forward: the pane, buttons, discs. All shadows are tinted slate (rgba(4,12,20) or rgba(20,32,41)), with negative spread so they pool below the object rather than glow around it.

### Shadow Vocabulary
- **Pane drop** (`0 22px 44px -22px rgba(4,12,20,.8), 0 2px 0 rgba(0,0,0,.15)`): the window sitting in the wall; the 2px line is the sill edge.
- **Sash bar** (`0 3px 8px rgba(4,12,20,.25)`): the muntins casting onto the glass.
- **Button lift** (`0 8px 18px -10px rgba(4,12,20,.55)`): primary red button only.
- **Disc lift** (`0 6px 14px -8px rgba(20,32,41,.5)` / `0 8px 16px -10px rgba(4,12,20,.6)`): service cue disc and step numbers.

**The Forward Objects Only Rule.** Only things that sit in front of the wall (pane, buttons, discs) get a shadow. Sections, rows and text never do.

## Shapes

Soft, small radii from a window maker's world: 10px on buttons, 8px on the pane frame, 6px on the logo and focus ring; full pills for floating labels (call pill, wipe hint); perfect circles for cues and step numbers. The pane frame is a 9px sash-white border with an 8px cross of sash bars, a literal four-lite window. Lists are ruled, not boxed: a 2px ink rule above, 1px 18% ink hairlines between rows. There are no cards.

**The Ruled Not Boxed Rule.** Repeating content (services, audiences) is separated by horizontal rules, never wrapped in cards or tinted tiles.

## Components

### Buttons
Big, blunt, thumb-sized.
- **Shape:** gently rounded (10px), 56px minimum height, 2px border, icon + label with a 10px gap, never wraps.
- **Primary (Call):** logo-red fill, white text, button-lift shadow. Hover deepens to logo-red-deep (fill and border).
- **Line (Text):** transparent with an 85% white 2px border on slate; on glass sections the border and text become ink. Hover adds an 8% white (or 6% ink) wash.
- **States:** colour transitions .2s ease-out; press scales to .98 (.15s). Hover and focus share one 3px focus-blue outline at 3px offset on buttons and links (blue so it stands apart from the red buttons). Service rows get no hover outline: only their arrow disc turns red (Ellie, 2026-10-17); keyboard focus still shows the blue ring.
- **Pairing:** always Call (primary) then Text (line). Every SMS link opens with a pre-filled message naming the service; one flag in the script turns every text link into a call link if the number is a landline.

### Top Bar
Logo left (56px tall phone, 58px wide, 6px radius), call pill right: slate-3 pill, 44px tall, red phone icon, number in 800 at 15px with tabular numerals.

### Service Row List
The services menu as a ruled list where every row is a link that opens a pre-filled text.
- **Row:** two-column grid (content / 44px cue), 18px vertical padding, title in the Title style, description in ink-soft 16px.
- **Cue:** a 44px white disc holding a red right-arrow line icon (20px). On hover/press the disc fills red, the arrow turns white, and it nudges 3px right (.2s ease-out). The tap highlight is a 12% red wash.
- Ends with a single plain-language note in ink-soft 15px.

### Numbered Steps
Three steps, each a 48px red disc with the counter in 900 italic 22px white, beside a Title and mist body.

### Icons
Inline line SVGs on a 24 grid at 22px, 2.2 stroke, round caps and joins, `currentColor`. Phone, message bubble, pointing hand, right arrow. No icon fonts, no filled glyphs.

### Fogged Glass Pane (signature)
A window you wipe. A `.pane` element (16:10 phone hero, 5:4 hero at 1000px+, 16:9 close) framed in a 9px sash-white border with a four-lite sash cross, holding one canvas. `data-scene` picks what is behind the glass (`sky`: a sky gradient with a sun and "FULL SERVICE / HOMES · BUSINESSES · COMPLEXES" lettered in the display voice; `logo`: the PJC logo hung outside under a sky). `data-fog` sets maximum fog opacity (0.94 hero, 0.72 close, default 0.9). Before the canvas draws, a CSS gradient shows still fog over sky so the first paint is never empty.

Layers, drawn per frame:
- **Scene:** painted once per size; a blurred copy is made by downscaling to 1/4 and then 1/10 size.
- **Fog:** the blurred scene + a milky tint (rgba(228,238,243,.62)) + a drifting **steam swirl** (26 soft white blobs on a tiled 1/3-scale texture, slid by layered sines), cut by a quarter-resolution **fog mask** that regrows toward full at 10% per second.
- **Beads:** water drops that grow, and past a run radius break loose and slide down with stick-slip lurches and a slight wander, swallowing beads in their path, clearing a trail in the fog and shedding small trailing beads. Each bead is a tiny inverted lens of the scene with a dark refracted rim and a soft low highlight; no hairline glints.
- **Pointer:** finger or mouse wipes the fog with a soft round brush (24px radius phone, 32px desktop) interpolated along the stroke, and pushes nearby beads, which spring back with a wobble; a fast swipe knocks a bead loose to run. Touch listeners are passive. The hero pane is `touch-action: none` so a finger wipes up, down and sideways (and `html` has `overscroll-behavior-y: none` so it never pulls to refresh); the close pane keeps `pan-y`.
- **Ghost wipe:** after 9 idle seconds (and once on load, and again on the logo pane's first reveal), an S-shaped swipe clears a band across the glass to show it is wipeable.
- **Hint:** a slate 78% pill at the bottom of the hero pane ("pointing hand" + short label) that fades out (.6s) on first touch.

Tunables live at the top of the pane IIFE and are the only place to adjust feel: `FOG_SCALE` 4, `REGROW` 0.10, `WIPE_R` 24/32, `BEAD_DENSITY` 1/1900 phone, 1/1500 desktop, `BEAD_MAX` 60/150, `RUN_R` 4.6, `PUSH_R` 52, `PUSH` 1500, `SPRING` 38, `DAMP` 6.5, `BREAK_SPEED` 900, `GHOST_IDLE` 9, `SWIRL_SPEED` 1.6. Device pixel ratio is capped at 2.

### Water Seams
A 28px full-width SVG between every slate/glass change, in place of a hard edge. Three stroked lines (2.2px non-scaling) ride one shared slow swell plus their own ripple; a fill path follows the middle line so the colour boundary itself moves. Line colours run water-blue, white/water-pale and slate-3 depending on direction; the fill is the next section's ground and the SVG background is the previous one.

### Motion
- **One loop per engine:** every pane shares one requestAnimationFrame loop and every seam shares another; never a loop per element.
- **Pause off screen:** IntersectionObserver turns each pane or seam on and off (panes with a 60px margin); a loop with nothing visible stops.
- **Reduced motion:** panes draw one still frame with no ghost wipe or drift, but wiping by hand still works; seams draw once and stay still; smooth scrolling and button/cue/bar transitions are removed.
- UI transitions are short ease-out (.15 to .35s); the only long durations are material (fog regrowth, ghost wipe 2.4s, hint fade .6s).

## Do's and Don'ts

### Do:
- **Do** keep logo red as the only saturated colour; use it for the primary action and one headline clause.
- **Do** set every heading in the system stack at 900 italic uppercase, -0.02em, 0.98 line-height.
- **Do** keep the phone number in the header's top-right corner, once per screen; the hero and close each carry one red Text button, 56px tall; no Call button under the headline, no sticky bar.
- **Do** put the Facebook button (ink, white label, blue mark) where people look for proof of the work, and again in the footer.
- **Do** join slate and glass sections with a water seam, never a straight edge.
- **Do** frame any new glass surface as a pane: sash-white 9px frame, four-lite sash cross, canvas engine with a still CSS fog fallback.
- **Do** run all ambient motion through the shared loops, pause it off screen, and give it a still reduced-motion frame.
- **Do** keep shadows slate-tinted with negative spread, and only under forward objects.

### Don't:
- **Don't** use black (#000) as a ground; the dark is slate.
- **Don't** introduce a second accent hue or let the water blues leave seams and panes.
- **Don't** box repeating content in cards; rule it.
- **Don't** add photography, stock imagery or webfonts; the scenes are canvas-drawn and the type is the system stack.
- **Don't** block vertical scroll on a pane or start a per-element animation loop.
- **Don't** use icon fonts or filled glyph icons; icons are 2.2-stroke inline line SVGs.
