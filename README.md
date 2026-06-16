# Seshank Bagavath — Personal Site

A single-page, single-file personal-marketing site. Plain semantic HTML + CSS + a little vanilla JS — no build step, no framework. Open `index.html` directly in a browser.

## Design
Clean / techy, near-dark, one restrained accent (signal-green). Space Grotesk (display) + JetBrains Mono (mono). Signature element: a live "still building" status indicator and count-up stat tiles that animate on scroll.

## Accessibility
- Visible keyboard focus + skip-to-content link
- `prefers-reduced-motion` respected (no scroll animations, counters jump to final value)
- Semantic landmarks, labelled sections, descriptive link text

## TODO before this is "high quality"
Search the codebase for `TODO` — each marks a real gap:

- [ ] **Real URLs** — replace `[SENSEISUITE_URL]`, `[PODCAST_URL]`, `[GITHUB_URL]`. Each placeholder link has a `data-todo-url` attribute and an inline `href="#"`. Set the real `href` and delete the `.todo` note span.
- [ ] **Profile photo** — add a face to the hero.
- [ ] **1–2 visual artifacts** — SenseiSuite screenshot, podcast cover, CAD render, or robot photo.
- [ ] **Voice sample** — confirm the About copy sounds like Seshank.
- [ ] **Confirm the CTA** — currently "email me". Adjust if the single desired action changes.

## Run
Just open `index.html`. To serve locally: `python -m http.server` then visit the printed URL.
