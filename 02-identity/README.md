# 02 — Visual Identity

All visual assets and specifications for the Neptura Science brand.

## Structure

```
02-identity/
├── logos/
│   ├── neptura-icon-base.svg          # Master icon mark (N)
│   ├── neptura-wordmark-base.svg      # Master wordmark (NEPTURA)
│   └── variants/                      # Production-ready color variants
│       ├── neptura-icon-white.svg
│       ├── neptura-icon-black.svg
│       ├── neptura-icon-neptura-blue.svg
│       ├── neptura-icon-signal-green.svg
│       ├── neptura-icon-alert-orange.svg
│       ├── neptura-icon-negative.svg
│       ├── neptura-wordmark-white.svg
│       ├── neptura-wordmark-black.svg
│       ├── neptura-wordmark-neptura-blue.svg
│       ├── neptura-wordmark-signal-green.svg
│       ├── neptura-wordmark-alert-orange.svg
│       ├── neptura-wordmark-negative.svg
│       ├── neptura-icon-black.pdf
│       ├── neptura-icon-negative.pdf
│       ├── neptura-wordmark-black.pdf
│       └── neptura-wordmark-negative.pdf
├── colors/
│   ├── neptura-colors.json            # Color tokens for design tools & APIs
│   └── neptura-colors.css             # CSS custom properties for web
├── typography/
│   └── neptura-typography.json        # Typography scale specification
├── LOGO_SPECIFICATIONS.md             # Full logo usage guide
├── visual-territories.md              # Color, type & photo direction
├── style-directions.md                # Visual direction options (Satellite Precision selected)
├── logo-routes.md                     # Logo variant rationale & use cases
└── visual-system-components.md        # Atomic UI components & data viz rules
```

## Aesthetic Direction: Satellite Precision

Dark mode dominant. Neon data on deep charcoal backgrounds. Cinematic science.

**References:** Linear (structure), Raycast (glow effects), Mapbox Dark (geospatial data viz).

## Color Quick Reference

| Token | Hex | Role |
|---|---|---|
| Dark BG | `#0B0E14` | Primary background |
| Neptura Blue | `#3B82F6` | Primary accent, data, links |
| Signal Green | `#10B981` | Success states, CTAs, positive data |
| Alert Orange | `#F59E0B` | Warnings, opportunity alerts |
| White | `#FFFFFF` | Text on dark backgrounds |
| Gray 400 | `#9CA3AF` | Secondary text |

## Typography Quick Reference

| Level | Font | Size | Use |
|---|---|---|---|
| Display Large | Inter Black | 64px | Hero, page titles |
| Heading 1 | Inter Bold | 36px | Main headings |
| Body Regular | Inter Regular | 16px | Main body text |
| Caption | Inter Medium | 12px | Labels, tags |
| Monospace | JetBrains Mono | 12px | Code, IDs, coordinates, financial values |
