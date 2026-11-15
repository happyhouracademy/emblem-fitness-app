# Emblem design system: start here

This folder is the source of truth for how Emblem looks and behaves. Build every screen against it.

## Decisions already made

1. Type: Direction B. Fraunces for headings and the wordmark, Manrope for numbers and body.
2. Mascot: Ro, a pixel prize rosette, 44 x 44. She lives on client screens only.
3. Colour: Cherry Cola #7C0116, Hibiscus Tonic #E0A4B0, Maraschino #DD1A2A, Oat Milk #FBF3EC. Full list in tokens.json.
4. Logging forgives: every field pre-filled, one 64px "Done as written" tap per set.
5. Celebration scales with the win: tick for a set, Ro's cheer for a session, full screen for a personal best.

## What is in this folder

- README.md: the full brand and screen guide. Read this first.
- tokens.json: colour, type, spacing, radius and shadow tokens.
- components/bundle.css: shared styles, including the .dir-b type block and the wordmark.
- components/<Screen>/README.md: one note per screen, 21 screens.
- design-system.json: the design system's own index file.

## What still lives only in the online design system

- components/<Screen>/preview.html: the 21 working screen previews.
- components/bundle.js: shared preview code and Ro's sprite grids (Emblem.sprites), outfits included.

Source: https://claude.ai/artifact/8KuyvLzV2RLkJ4eeSQp5j9
Design system version copied: 1794716562-9e3e (15 Nov 2026)
