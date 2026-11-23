---
name: czepiel.dev
description: A dev-tool product page whose product is Filip Czepiel and whose live demo is the page's own deploy.
colors:
  cobalt: "#2747e0"
  cobalt-pressed: "#1d39c2"
  cobalt-wash: "#eef1fe"
  on-cobalt: "#ffffff"
  live-green: "#16a34a"
  live-green-text: "#13773a"
  building-amber-text: "#8a5a00"
  daylight-canvas: "#fafafa"
  paper-surface: "#ffffff"
  raised-mist: "#f4f4f5"
  graphite-ink: "#0b0d12"
  slate-muted: "#565c68"
  hairline: "#e4e5e8"
  hairline-strong: "#cfd2d8"
  cobalt-dark: "#3d5df2"
  cobalt-pressed-dark: "#2f4fd9"
  cobalt-wash-dark: "#161d3a"
  live-green-dark: "#22c55e"
  live-green-text-dark: "#4ade80"
  building-amber-text-dark: "#f0b44c"
  night-canvas: "#0a0b0d"
  night-surface: "#111318"
  night-raised: "#181b21"
  night-ink: "#ececef"
  night-muted: "#9ca2ad"
  night-hairline: "#23262d"
  night-hairline-strong: "#333741"
typography:
  display:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(3rem, 8.5vw, 5.75rem)"
    fontWeight: 600
    lineHeight: 0.95
    letterSpacing: "-0.04em"
    fontFeature: "\"ss01\" on"
  display-closing:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(2.25rem, 5.5vw, 4rem)"
    fontWeight: 600
    lineHeight: 1.02
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(1.75rem, 3.2vw, 2.5rem)"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.03em"
  title:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 600
    lineHeight: 1.33
    letterSpacing: "-0.02em"
  title-sm:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 600
    lineHeight: 1.55
  positioning:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 400
    lineHeight: 1.375
  lede:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
  body:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.625
  body-sm:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Geist, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 500
    lineHeight: 1.4
  data:
    fontFamily: "Geist Mono, ui-monospace, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: "0.8125rem"
    fontWeight: 400
    lineHeight: 1.4
    fontFeature: "\"tnum\" on"
rounded:
  focus: "6px"
  sm: "8px"
  control: "10px"
  panel: "16px"
  pill: "999px"
spacing:
  hair: "4px"
  xs: "8px"
  sm: "12px"
  md: "20px"
  lg: "24px"
  xl: "40px"
  gutter: "20px"
  gutter-wide: "32px"
  section: "80px"
  section-wide: "112px"
  container: "72rem"
components:
  button-primary:
    backgroundColor: "{colors.cobalt}"
    textColor: "{colors.on-cobalt}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.control}"
    padding: "0 18px"
    height: "44px"
  button-primary-hover:
    backgroundColor: "{colors.cobalt-pressed}"
    textColor: "{colors.on-cobalt}"
  button-secondary:
    backgroundColor: "{colors.paper-surface}"
    textColor: "{colors.graphite-ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.control}"
    padding: "0 18px"
    height: "44px"
  button-secondary-hover:
    backgroundColor: "{colors.raised-mist}"
  button-large:
    rounded: "{rounded.control}"
    padding: "0 20px"
    height: "48px"
  button-pending:
    backgroundColor: "transparent"
    textColor: "{colors.slate-muted}"
    rounded: "{rounded.control}"
    height: "44px"
  nav-link:
    textColor: "{colors.slate-muted}"
    rounded: "{rounded.sm}"
    padding: "0 12px"
    height: "44px"
  nav-link-current:
    textColor: "{colors.graphite-ink}"
  chip:
    backgroundColor: "{colors.paper-surface}"
    textColor: "{colors.graphite-ink}"
    rounded: "{rounded.pill}"
    padding: "0 10px"
    height: "28px"
  status-pill:
    backgroundColor: "{colors.paper-surface}"
    textColor: "{colors.live-green-text}"
    rounded: "{rounded.pill}"
    padding: "6px 14px 6px 12px"
  status-dot:
    backgroundColor: "{colors.live-green}"
    rounded: "{rounded.pill}"
    size: "8px"
  panel:
    backgroundColor: "{colors.paper-surface}"
    rounded: "{rounded.panel}"
  panel-row:
    typography: "{typography.data}"
    padding: "11px 20px"
  node:
    backgroundColor: "{colors.daylight-canvas}"
    textColor: "{colors.graphite-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "8px 10px"
    height: "52px"
  node-pressed:
    backgroundColor: "{colors.cobalt-wash}"
  caption-well:
    backgroundColor: "{colors.raised-mist}"
    textColor: "{colors.slate-muted}"
    rounded: "{rounded.sm}"
    padding: "10px 12px"
---

# Design System: czepiel.dev

## Overview

**Creative North Star: "The Live Deploy Page"**

czepiel.dev is built in the dev-tool product canon at the craft level of Vercel and Linear, played straight: a daylight surface of crisp neutrals, hairline structure, one cobalt accent and one green signal for live things. The product being sold is a person, and the proof is the page itself: a framed deploy panel with real commit, origin and pipeline data, and a small architecture diagram the visitor can interrogate. Everything else is set as calm, ruled editorial lists so the panel is the one object that reads as "product".

Density is moderate and recruiter-paced: large display type for the name, generous section spacing (80px, 112px from 768px), and content held to readable measures (around 40rem for prose). Dark mode is not a separate design; it is the same token set re-valued under `prefers-color-scheme: dark`, with no manual toggle. Motion is one orchestrated settle on load plus a one-shot path trace; nothing loops except the live status dot.

The system replaces an earlier terminal costume (monospace everywhere, `// HEADINGS`, hashtag badges, typewriter cursor), which the user retired. It also refuses the generic student template: a centred name over a grid of equal cards.

**Key Characteristics:**
- Light-first neutrals with a system-following dark mode; every color is a CSS custom property re-valued per scheme.
- One accent (cobalt) reserved for the action, focus, text selection and the pressed diagram node.
- Green means live; amber means in progress; dashed means not yet.
- Geist for all words, Geist Mono only for real data.
- Structure from 1px hairlines and ruled lists; exactly one lifted object (the deploy panel).
- Exponential ease-out on everything; full reduced-motion fallbacks.

## Colors

Cool, near-colorless neutrals carry the page; two saturated signals (cobalt, green) and one muted amber each have a single job.

### Primary
- **Signal Cobalt** (`cobalt`; `cobalt-dark` at night): the primary button fill, the 2px focus ring, the text-selection highlight, the pressed architecture node's border, and the skip link. Hover/pressed state is **Pressed Cobalt** (`cobalt-pressed`). **Cobalt Wash** (`cobalt-wash`) is the pressed node's fill and nothing else. Text on cobalt is white (`on-cobalt`).

### Secondary
- **Live Green** (`live-green`; `live-green-dark`): the status dot and its pulse ring. Never a fill for buttons or surfaces.
- **Live Green Text** (`live-green-text`; `live-green-text-dark`): the words beside a live dot ("Online", the availability line). Darker than the dot so it holds contrast as text.

### Tertiary
- **Building Amber** (`building-amber-text`; `building-amber-text-dark`): text-only colour for an "in progress" state, paired with a hollow ring marker. It has no fill or background use.

### Neutral
- **Daylight Canvas** (`daylight-canvas`; `night-canvas`): page background, header backdrop (at 90% with blur), and the inset fill of diagram nodes.
- **Paper Surface** (`paper-surface`; `night-surface`): the panel, secondary buttons, chips and the status pill. One step brighter than the canvas in light, one step lifted in dark.
- **Raised Mist** (`raised-mist`; `night-raised`): secondary-button hover, the diagram caption well, and the node-hit halo during the trace.
- **Graphite Ink** (`graphite-ink`; `night-ink`): all primary text, link text, the strong 1px rule above skill columns, and the trace's wire fill.
- **Slate Muted** (`slate-muted`; `night-muted`): secondary text, ledes, metadata, nav links at rest, icon strokes in meta rows.
- **Hairline** (`hairline`; `night-hairline`): every structural 1px border: section tops, list rules, panel edge and rows, chips, nodes at rest.
- **Hairline Strong** (`hairline-strong`; `night-hairline-strong`): button borders, wires and arrowheads, node hover, list markers, link underlines at rest, scrollbar thumb.

### Named Rules
**The Cobalt Is a Verb Rule.** Cobalt appears only where the visitor acts or where the system marks focus or selection: the primary button, the focus ring, `::selection`, the pressed node, the skip link. Headings, links, icons, chips and decoration never take it. Text links are ink with a hairline-strong underline.

**The Green Means Live Rule.** Green is spent only on things that are actually live right now (the site is online, the availability is open). Amber marks work in progress; a dashed muted ring marks planned work. These three states never borrow each other's colour.

**The One Variable Rule.** Every colour is a `--c-*` custom property defined once for light and once for dark, exposed to Tailwind through `@theme`. Never hard-code a hex in markup; inline SVG uses `var(--c-*)` too.

## Typography

**Display Font:** Geist (self-hosted variable, with ui-sans-serif / system-ui fallback)
**Body Font:** Geist
**Label/Mono Font:** Geist Mono (self-hosted variable, with ui-monospace fallback)

**Character:** One grotesque family does all the talking, tightened hard at display sizes (-0.04em) and left neutral at reading sizes; its mono sibling appears only as the voice of machine data. Stylistic set `ss01` is on globally.

### Hierarchy
- **Display** (600, clamp(3rem, 8.5vw, 5.75rem), 0.95, -0.04em): the name in the hero. One per page.
- **Display Closing** (600, clamp(2.25rem, 5.5vw, 4rem), 1.02, -0.04em): the closing contact question, max 48rem.
- **Headline** (600, clamp(1.75rem, 3.2vw, 2.5rem), 1.1, -0.03em): section titles.
- **Title** (600, 1.5rem, -0.02em): project names in the ruled project list. A muted, 1.25rem variant is used for a planned, empty slot.
- **Title Small** (600, 1.125rem): entries in the experience list; panel and column heads use 600 at 0.9375rem / 1rem.
- **Positioning** (400, 1.25rem rising to 1.5rem at 768px, snug): the one-sentence positioning line under the name, muted, max 34rem.
- **Lede** (400, 1.0625rem, 1.6): section ledes and project descriptions, muted, max 40rem.
- **Body** (400, 1rem, 1.625): entry descriptions and bullet lists, max 40rem.
- **Body Small** (400–500, 0.9375rem): buttons, meta rows, organisation lines, list metadata.
- **Label** (500, 0.8125rem): chips, panel subtitles, the diagram heading, node names. Lane labels sit at 0.75rem.
- **Data** (Geist Mono 400, 0.8125rem, tabular numerals): commit SHA, region, origin, dates in list gutters.

### Named Rules
**The Mono Is Data Rule.** Geist Mono is reserved for values a machine would print: hashes, regions, protocols, dates. Words inside a mono slot switch back to sans (e.g. "w produkcji" inside a date line, the pipeline row). Never set headings, labels or prose in mono.

**The Sentence Case Rule.** Every heading and label is sentence case at normal tracking. No uppercase tracked labels above headings.

## Layout

A single centred container (max 72rem) with 20px side gutters, widening to 32px from 640px. Desktop uses a 12-column grid: the hero splits 7/5 (copy left, deploy panel right); project rows split 4/8 (metadata gutter left, content right, metadata drops below the content on phones); the experience section splits 4/8 with a sticky heading column (top 6rem) beside a ruled list whose rows use a 9rem date gutter from 640px. Skills are four ruled columns (1 / 2 at 640px / 4 at 1024px).

Sections are separated by a hairline top border and 80px of vertical padding (112px from 768px). Inside sections the rhythm is: title, 12px to lede, 48px to content; list rows 40px (projects) or 24px (experience) of vertical padding; chips and buttons gap 8–12px. The header is sticky, 64px tall, canvas at 90% with a light backdrop blur and a hairline bottom. Anchor scrolling offsets by 5rem for the header.

Breakpoints in use: 420px (diagram compaction), 640px, 768px, 1024px. On phones the deploy panel follows the action row; primary nav links collapse to just "Kontakt" plus the language toggle.

## Elevation & Depth

The system is flat and line-built. Depth comes from tonal steps (canvas, surface, raised) and 1px hairlines. Exactly one object is lifted: the deploy panel.

### Shadow Vocabulary
- **Panel lift** (light `0 1px 2px rgb(11 13 18 / 0.04), 0 12px 32px -12px rgb(11 13 18 / 0.12)`; dark `0 1px 2px rgb(0 0 0 / 0.4), 0 16px 40px -16px rgb(0 0 0 / 0.7)`): the deploy panel only.
- **Trace halo** (`0 0 0 3px` in Raised Mist): a transient ring on a diagram node while the path trace passes through it, gone at rest.

### Named Rules
**The One Lifted Object Rule.** Only the live "this page" panel casts a shadow, because it is the product demo. Lists, chips, buttons and nodes stay flat; if another surface wants elevation, it is probably a second card that should be a ruled row.

## Shapes

Soft, controlled corners scaled to object size: 6px on the focus ring, 8px on nav links and the caption well, 10px on buttons and diagram nodes, 16px on the panel, full pills on chips, status pills and dots. The logo mark is a 32-unit square at radius 8 holding a flat raccoon face (Filip's mascot): rounded ears, a dark eye mask and a nose, drawn in two tones (ink and canvas) so it inverts with the colour scheme. The same drawing is the favicon. Borders are always 1px solid, with one exception: a dashed border means "not available yet" (the pending CV button, the planned-project ring). Wires in the diagram are 1px lines with small CSS-triangle arrowheads.

## Components

### Buttons
Quiet, compact, product-UI buttons with an icon leading the label.
- **Shape:** gently rounded (10px), 44px tall, 18px side padding, 500 weight at 0.9375rem, 8px icon gap, icons 17px.
- **Primary:** Signal Cobalt fill and border, white text. One per action row (email).
- **Secondary:** Paper Surface with a Hairline Strong border and ink text (GitHub, LinkedIn).
- **Hover / Focus:** primary darkens to Pressed Cobalt; secondary gains Raised Mist fill and a muted border. 160ms exponential ease-out. Active nudges down 1px. Focus is the global 2px cobalt ring, 3px offset.
- **Large:** the closing contact row uses 48px height, 20px padding, 1rem text.
- **Pending:** an unavailable action (`aria-disabled`) is transparent with a dashed Hairline Strong border, muted text, `not-allowed` cursor, no hover or press response, and a title explaining why.

### Chips
- **Style:** 28px pill, Paper Surface, Hairline border, ink text at 0.8125rem, 10px padding. Static tags for stack and role; not interactive.

### Status Pill and Dot
- **Dot:** 8px Live Green circle with a pulse ring (scale to 2.8x, fading, 2.4s loop) that is removed entirely under reduced motion.
- **Pill:** the dot plus Live Green Text in a Paper Surface pill with a Hairline border. Used for availability in the hero and "Online" in the panel header.
- **State markers:** in-progress work uses an 8px hollow 2px ring in Building Amber beside amber text; planned work uses the same ring dashed, in muted.

### Cards / Containers (the Deploy Panel)
- **Corner Style:** 16px.
- **Background:** Paper Surface; overflow clipped.
- **Shadow Strategy:** Panel lift (see Elevation); the only shadowed object.
- **Border:** 1px Hairline.
- **Internal Padding:** 20px sides; header 16px vertical.
- **Rows:** a definition list, each row a two-column grid (7.5rem label column, 16px gap), 11px by 20px padding, hairline top. Labels in muted sans 0.875rem; values in Geist Mono 0.8125rem, wrapping anywhere.
- **Motion:** header, rows and diagram settle in sequence on load.

### Navigation
- **Style:** text links at 0.875rem, muted at rest, ink on hover and for the current section (`aria-current`, driven by scroll position). 44px tall hit areas, 12px padding, 8px radius, colour-only transition.
- **Language toggle:** the same nav link with a Hairline border and ink 500 text; it names the language it switches to.
- **Mobile:** section links hide below 768px; "Kontakt" and the toggle remain.

### Architecture Flow (signature)
A compact, interactive diagram of how the page is served and deployed.
- **Lanes:** two labelled rows (request, deploy), each a five-column grid: node, wire, node, wire, node. Nodes in a lane stretch to equal height; wires centre between them.
- **Node:** a button with a 10px radius, Hairline border, Daylight Canvas fill, a 0.8125rem 500 name and a short, non-wrapping Geist Mono sub-label in muted. Hover strengthens the border; pressed (`aria-pressed`) takes a cobalt border and Cobalt Wash fill. Hover or focus previews a caption; click pins it.
- **Wire:** 20px 1px Hairline Strong line with an arrowhead; 12px wide below 420px, where nodes also tighten.
- **Caption well:** Raised Mist, 8px radius, muted 0.8125rem relaxed text, `aria-live="polite"`, minimum height reserved so the panel never jumps.
- **Trace:** a one-shot pass along a lane: each node's border flashes to ink with a 3px Raised Mist halo (900ms) while each wire fills left to right in ink (380ms), staggered 0 / 220 / 480 / 700 / 960ms. The request lane plays once 900ms after load; the deploy lane replays on pointer or keyboard entry. Never runs under reduced motion.

### Ruled Lists
Repeating content (projects, experience, skills) is never carded. Rows are separated by 1px Hairline rules with a closing rule at the end. Projects place a mono date and plain-text context in a left gutter; experience places a mono date in a 9rem gutter; skill columns sit under a 1px ink rule with a muted item list. Bullet markers are Hairline Strong.

### Text Links
Ink text with a 1px Hairline Strong underline at 0.2em offset; the underline turns ink on hover. External repo links pair a leading icon with a trailing muted up-right arrow icon.

## Do's and Don'ts

### Do:
- **Do** keep cobalt to the primary button, focus ring, selection and the pressed node (The Cobalt Is a Verb Rule).
- **Do** define every colour as a `--c-*` variable with both a light and a dark value; let dark mode follow `prefers-color-scheme`.
- **Do** set real data (SHA, region, dates, protocols) in Geist Mono with tabular numerals, and everything else in Geist.
- **Do** build repeating content as ruled rows with a metadata gutter, so the projects list can grow from two to four entries without a redesign.
- **Do** show unfinished things honestly: a dashed pending control, a hollow amber ring for in-progress, a dashed muted ring for planned.
- **Do** use inline SVG icons from one sprite, 24-unit viewBox, 2px round strokes, in `currentColor`.
- **Do** keep content visible by default and animate only transform (settle from 6px below over 800ms, staggered 70ms), with `cubic-bezier(0.16, 1, 0.3, 1)` and 160ms for state changes.
- **Do** give every button, nav control and diagram node at least 44px of height; inline text links are the exception.

### Don't:
- **Don't** bring back the terminal costume: monospace for prose, `// HEADINGS`, hashtag badges, typewriter text or blinking cursors.
- **Don't** set the hero as a centred name over a grid of equal cards.
- **Don't** add a second shadowed surface; the deploy panel is the one lifted object.
- **Don't** use green for anything that is not live, or cobalt for decoration, headings or links.
- **Don't** loop any animation other than the live status dot, and don't run settle, trace, pulse or smooth scrolling under `prefers-reduced-motion: reduce`.
- **Don't** add uppercase tracked labels above headings.
- **Don't** load fonts, icons or scripts from third-party runtimes; Geist and Geist Mono are self-hosted.
