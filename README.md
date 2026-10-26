# Program Page Prototype

A working prototype of the IU Online degree program page (Informatics, B.S.) and the program comparison drawer, built from the Figma file "Degrees Program Page Start" (Design 0.11).

Live: https://manselldesign.github.io/program-page-prototype/
Open straight to the comparison drawer: https://manselldesign.github.io/program-page-prototype/#compare

## What works

- Header nav dropdowns, plus a mobile menu below 1100px
- "On this page" links jump to each section
- Request-info form: required-field checks, email check, and a thank-you state (nothing is sent)
- HLC disclosure opens and closes
- Advisor "Hours" toggles and "Schedule a consultation" (shows a prototype message)
- Program comparison drawer: opens from the sidebar card, closes with ✕, the dark backdrop, or Esc. You can remove programs, add up to 3 from a list, and the "Most affordable" and "Shortest duration" cards plus the Lowest/Highest tags recalculate.
- The Practical skills and Experiential learning sentences are built from short lists, the same way the CMS spec describes

## Files

- `index.html` is the whole prototype (HTML, CSS, and JS in one file). Icons and stickers are the official Rivet icons and stickers, inlined.
- `rivet-tokens.css` holds every color, spacing, shadow, and type value, generated from the Rivet 3 Components Figma library (Foundation, Theme, and Shadows variables, plus one `.t-*` class per library text style). The page's own CSS only references these tokens.
- `assets/` holds the photos exported from Figma: `feature.jpg`, `ranking-badge.png`, `advisor-1.jpg`, `advisor-2.jpg`. Stickers are exported straight from the design file.

Content is sample content for review, not the live IU website.
