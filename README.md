# Seshank Bagavath — Personal Site

[![Deploy to GitHub Pages](https://github.com/seshankbagavath/personal-site/actions/workflows/pages.yml/badge.svg)](https://github.com/seshankbagavath/personal-site/actions/workflows/pages.yml)

A fast, single-page personal-marketing site for **Seshank Bagavath** — high-school student, creator, and developer. Built as one self-contained `index.html`: semantic HTML + CSS + a little vanilla JS. No build step, no framework, no dependencies.

🔗 **Live site:** https://seshankbagavath.github.io/personal-site/

---

## Highlights

- **Single file.** Everything (markup, styles, scripts) lives in `index.html`. Double-click to open, or host anywhere static.
- **Signature element.** A live "still building" status indicator and count-up stat tiles that animate on scroll — the numbers are the strongest argument, so they get the spotlight.
- **Accessible by default.** Keyboard focus rings, skip-to-content link, `prefers-reduced-motion` support, semantic landmarks, descriptive link text.
- **Responsive.** Mobile-first layout; nav, counters, and cards reflow cleanly down to phone widths.

## Design

Clean, light, and warm — **white-to-beige surfaces with a single forest-green accent** (`#3a7d5c`) used sparingly for CTAs, active state, and key emphasis. Generous whitespace, soft rounded cards, thin line icons. Display type in **Fraunces**, UI in **Inter**, mono details in **JetBrains Mono**. All tokens live in `:root` for easy re-tuning.

## Page structure

`Header (sticky)` → `Hero` → `Counters` → `About` → `Work` (3 cards) → `Track record` → `Contact` → `Footer`. One page, anchor-scroll navigation.

## Run locally

```bash
# simplest: just open the file
start index.html        # Windows
open index.html         # macOS

# or serve it
python -m http.server   # then visit http://localhost:8000
```

## Deploy

Hosted on **GitHub Pages** via the workflow in [`.github/workflows/pages.yml`](.github/workflows/pages.yml) — every push to `main` redeploys automatically. To enable it once: **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Still to add

- [ ] **Profile photo** — a face for the hero.
- [ ] **1–2 visual artifacts** — SenseiSuite dashboard screenshot, podcast cover, CAD render, or robot photo.
- [ ] **OG image** — a rich link-preview card for sharing.
- [ ] **Favicon.**

## License

© Seshank Bagavath. All rights reserved.
