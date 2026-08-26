# Mini Orange Bento, Astro

## Run
```bash
npm install
npm run dev
```

## Components
- Navbar
- Hero
- LogoTicker
- Benefits
- ProductStory
- Metrics
- UseCases
- PurchaseCta
- Footer

The selected Webflow page was split only at its original top-level boundaries.
All 22 `data-w-id` animation hooks, all 8 inline transform states, all 319 class
assignments, the original Webflow CSS, script chunks, root page/site IDs, and
script order are preserved.

## Latest changes
- Logo ticker reduced to one centered ORANGE logo.
- First and second use-case cards swapped.
- Added `HowToUse.astro` directly below the hero with the supplied video in a phone frame.
- Benefit accordions now use measured JS height transitions for smooth opening and closing.
- Device and benefit emojis were replaced with one consistent SVG icon system.
