# Seshank Bagavath — Personal Site

A single-page, single-file personal-marketing site. Plain semantic HTML + CSS + a little vanilla JS — no build step, no framework. Open `index.html` directly in a browser.

## Design
Clean / techy, light blue-and-white, one restrained accent (signal-blue). Space Grotesk (display) + JetBrains Mono (mono). Signature element: a live "still building" status indicator and count-up stat tiles that animate on scroll.

## Accessibility
- Visible keyboard focus + skip-to-content link
- `prefers-reduced-motion` respected (no scroll animations, counters jump to final value)
- Semantic landmarks, labelled sections, descriptive link text

## Links
GitHub, Podcast (Spotify), and SenseiSuite are wired up live, plus Instagram in the contact section.

## TODO before this is "high quality"

- [x] **Real URLs** — GitHub, Podcast, SenseiSuite, Instagram are all live.
- [ ] **Profile photo** — add a face to the hero.
- [ ] **1–2 visual artifacts** — SenseiSuite screenshot, podcast cover, CAD render, or robot photo.
- [ ] **Voice sample** — confirm the About copy sounds like Seshank.
- [ ] **Confirm the CTA** — currently "email me". Adjust if the single desired action changes.

## Run
Just open `index.html`. To serve locally: `python -m http.server` then visit the printed URL.
