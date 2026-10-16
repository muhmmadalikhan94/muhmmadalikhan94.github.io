# Muhammad Ali Khan · Portfolio

Personal portfolio site: experience, projects, skills and education.

**Live:** https://muhmmadalikhan94.github.io

## What's inside

The whole site is designed as an HL7 v2 message about its author: the nav is an `MSH` header and each section is a segment (`PID`, `ZEM`, `ZPR`, `ZSK`, `ZED`, `ACK`).

- Hero name drawn on canvas from HL7 delimiter characters, with a scanning lens that follows the cursor and data packets running across it
- About section shown as a real `PID` segment plus custom Z-segments, with a hover-linked decoder
- Experience with a live HL7 → JSON parser animation that maps each field
- Project index with variable-font hover, cursor-following previews and expandable details
- Skills-by-project matrix showing where each technology was used
- Purple dark theme by default with a light toggle; respects `prefers-reduced-motion`
- Single `index.html`, no build step, no dependencies apart from Google Fonts

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

The site is served by GitHub Pages from the `main` branch. Push to `main` and it updates.
