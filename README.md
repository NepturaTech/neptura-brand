# Neptura Brand OS

> **The Climate Certainty Engine** — Precision for Impact.

This repository is the single source of truth for Neptura Science's brand system: strategy, visual identity, guidelines, and application specs.

---

## Repository Structure

```
neptura-brand/
├── 01-strategy/          # Brand positioning, messaging & research
├── 02-identity/          # Visual assets: logos, colors, typography
├── 03-guidelines/        # Usage rules & brand guidelines
├── 04-applications/      # Touchpoint specs (packaging, product)
├── 05-go-to-market/      # GTM strategy
└── 06-execution/         # Design agent instructions
```

---

## Quick Navigation

| Section | What's inside |
|---|---|
| [01-strategy](./01-strategy/) | Brand foundations, decision framework, messaging matrix, market research |
| [02-identity](./02-identity/) | Logo SVGs/PDFs, color tokens (JSON + CSS), typography specs |
| [03-guidelines](./03-guidelines/) | Logo usage rules, voice & tone, brand guidelines MVP |
| [04-applications](./04-applications/) | Smart tag, certificate asset, dashboard spec |
| [05-go-to-market](./05-go-to-market/) | "Operation Andes" — phased GTM plan |
| [06-execution](./06-execution/) | Prompt & instructions for design agents |

---

## Brand in One Sentence

Neptura Science transforms 12 weeks of environmental consulting into 2 weeks of certified, investable data — built for municipalities, coffee exporters, and carbon market operators.

## Core Identity

- **Positioning:** "The Climate Certainty Engine" — we calculate, certify, and monetize environmental regeneration.
- **Archetype:** The Visionary Architect (Magician + Ruler)
- **Aesthetic:** Satellite Precision — dark mode, neon data, cinematic science.
- **Tagline:** *Certeza Climática.* / *Precision for Impact.*

## Color Tokens (Quick Reference)

| Token | Hex | Use |
|---|---|---|
| Neptura Blue | `#3B82F6` | Primary, data, links |
| Signal Green | `#10B981` | Success, CTAs, positive data |
| Alert Orange | `#F59E0B` | Warnings, opportunity alerts |
| Dark BG | `#0B0E14` | Primary background |
| White | `#FFFFFF` | Text on dark, accents |
| Gray 400 | `#9CA3AF` | Secondary text |

## Logo Files (Quick Reference)

All logos live in [`02-identity/logos/`](./02-identity/logos/).

| File | Use |
|---|---|
| `neptura-icon-base.svg` | Source icon mark — use this in Figma |
| `neptura-wordmark-base.svg` | Source wordmark — use this in Figma |
| `variants/neptura-icon-white.svg` | Icon on dark backgrounds |
| `variants/neptura-wordmark-black.svg` | Wordmark on light backgrounds |
| `variants/neptura-wordmark-negative.svg` | Wordmark on dark backgrounds |

---

## How to Use This Repo

### For Web Projects
```css
/* 1. Import color tokens */
@import '02-identity/colors/neptura-colors.css';

/* 2. Use variables */
background: var(--neptura-dark-bg);
color: var(--neptura-blue);
```

### For Design Tools (Figma / Sketch)
1. Import `02-identity/colors/neptura-colors.json` as color styles.
2. Import `02-identity/typography/neptura-typography.json` for text styles.
3. Use base SVGs from `02-identity/logos/` as master components.

### For Presentations
- Use `variants/neptura-wordmark-negative.svg` on dark slides.
- Follow the Satellite Precision aesthetic: dark backgrounds, neon data accents.

---

## Contact

Brand questions: hello@neptura.science

---

*Neptura Science — From doubt to investment in 15 days.*
