# Sussegado — Project Handoff

A Goan-Bombay family food brand, based in Barcelona. This folder is everything
built so far, ready to continue working on inside Claude Code.

## Structure
- `index.html` — the landing page (bilingual EN/ES toggle, cover → story frames
  → "What Sussegado Means" → menu → WhatsApp CTA). Images are now linked from
  `/images/` instead of embedded, so this file is small and easy to edit.
- `/images/` — the six brand illustrations, all cropped to a consistent 4:3.
- `/booklets/` — the print-ready A5 booklet PDFs (EN + ES), same content as the
  landing page, laid out for a physical hand-out.
- `/stickers/` — square delivery-box stickers (EN/ES/CA), PNG for digital use
  and PDF sized to the real 4cm × 4cm print dimension.
- `/docs/sussegado-picture-stories.md` — the illustration prompts used to
  generate each image (for consistency if more are added later), plus the
  short-form story template used for the croqueta dish story.

## Brand system
- Colors: parchment `#E8DCC4` background, ink `#2B211B` text, maroon `#6B2737`,
  teal `#1F4C4C`, gold `#B8863B` accents
- Fonts: Playfair Display (headings/captions), Jost (UI/labels) — loaded from
  Google Fonts in `index.html`. Print PDFs use DejaVu Serif/Sans instead,
  since the PDF renderer can't fetch web fonts.
- Icon: a simplified Goan *balcão* (oyster-shell lattice window) — the
  brand's recurring visual motif, echoed throughout.

## Still open
- **WhatsApp number is a placeholder** (`wa.me/00000000000`) in two spots in
  `index.html` — the main CTA button and the mobile bottom-nav "Order" tab.
  Needs the real number before this goes live.
- **Per-dish story pages don't exist yet.** The plan (per earlier discussion)
  is that each menu item eventually links to its own illustrated page telling
  that dish's origin story — the croqueta story is written (see the docs
  file) but not yet built as its own page. Fried Rice + Bombay Chicken and
  Potato Chops don't have written stories yet.
- **Not hosted anywhere yet.** Recommended path discussed: Netlify, with a
  free account (not an anonymous drop) so it can be redeployed to the same
  URL as it keeps changing.
