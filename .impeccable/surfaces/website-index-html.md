---
version: 1
slug: "website-index-html"
primary_target: "website/index.html"
related_targets: []
---

# Surface: czepiel.dev homepage (website/index.html)

Mode: Persuade (the visitor decides whether to contact or interview Filip).

Audience and job: tech recruiters arriving from LinkedIn, often on phone, skimming in about 30 seconds. They need: who he is, that he wants a summer 2027 internship (Cloud / DevOps / AI Engineering / MLOps), the AWS SAA-C03 cert, proof of shipped work, and a working way to make contact.

Primary action: email (mailto:contact@czepiel.dev). Secondary: GitHub, LinkedIn. The CV is shown as a disabled "coming soon" control until the PDF exists.

Proof and content: Avida (Collabothon 2026, team lead, 48 h, live on stage, repo); czepiel.dev / Cloud Resume Challenge (Terraform, S3, CloudFront with OAC, ACM, GitHub Actions); two upcoming projects shown honestly as in progress or planned; experience and education; skills; languages.

Constraints: static HTML + Tailwind v4; PL default with an EN toggle; no framework; fonts and icons self-hosted, no third-party runtime scripts.

## Direction contract

THESIS: A Vercel/Linear-grade product page whose product is Filip and whose live demo is the page itself: the deploy that served it, and the architecture it runs on. It refuses the themed costume (terminal, stations, posters) and the generic student template (a centred name over equal cards).

OWN-WORLD: The standing exit, played straight: the dev-tool product canon at the craft level of Vercel and Linear (user's choice, 2026-11-23). A light, daylight surface of crisp neutrals with hairline borders and a dark mode that follows the system setting. One cobalt accent, used only for the action and for focus. A green status dot for live things. Geist for prose and display, and Geist Mono only for real data (commit SHA, regions, dates). Inline SVG icons drawn at one stroke weight.

STORY: The recruiter learns who Filip is and what he wants within one glance. They believe it because the page shows its own deploy and architecture, and Avida is proof of AI work. Then they email him.

FIRST VIEWPORT: On the left, a status line "Szukam stażu na lato 2027", then the name at display scale, a one-sentence positioning line, a meta row (SAA-C03 · PŁ · Łódź) and the actions (Email primary, GitHub, LinkedIn, CV disabled). On the right, a "this page" deploy panel showing the real commit SHA, branch, deploy time, region and status, above a compact S3 → CloudFront architecture diagram. On a phone the panel follows the actions.

FORM: canon (the standing exit, chosen in plain words after two re-rolls; references: Vercel, Linear); seed:5ba037e397066602
Signature interaction: the architecture diagram traces the request path (visitor → CloudFront/ACM → OAC → S3, plus GitHub Actions → S3 deploy). Each node can be focused or hovered to explain itself. Under reduced motion the trace is static.
Motion grammar: one orchestrated load (the content is visible by default, and the panel rows settle in sequence) with exponential ease-out. Nothing loops except the live status dot, and that stops under reduced motion.

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

## Open decisions (user-owned)

- CV PDF, the Credly link, Avida's feature and stack description, details of projects 3 and 4, and the dev.to post. Show these as clear placeholders and never invent them.
- An og:image raster does not exist yet.
