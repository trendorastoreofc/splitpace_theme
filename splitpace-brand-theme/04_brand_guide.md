# Splitpace Brand Guide

Applies to guides, docs, listings and marketing material. The app UI is not required to follow this yet.

## Logo

Mark: "Split Ring". A lap ring cut into two halves, the right half raised. One lap, two splits.
Wordmark: "split" in Inter ExtraBold + "pace" in Inter Medium, lowercase, letter-spacing -0.035em.

| File | Use on |
|---|---|
| `splitpace-logo-light-bg` | White or light backgrounds (default) |
| `splitpace-logo-dark-bg` | Ink backgrounds ("pace" in Volt) |
| `splitpace-icon-primary` | Favicon, avatar, app icon, small spaces |
| `splitpace-icon-inverse` | Icon on Ink backgrounds |
| `splitpace-wordmark-*` | Where the icon already appears nearby |

Asset pack: `splitpace-brand.zip` (outlined SVGs, no font needed, plus PNGs at 64–1200px).

Rules: keep clear space around the logo equal to half the icon height. Minimum icon size 24px. Don't recolour, stretch, add shadows, or put the light-bg logo on a busy photo.

## Colours

| Name | Hex | RGB | Role |
|---|---|---|---|
| Ink | `#0E1A2B` | 14, 26, 43 | Primary. All text, headings, dark backgrounds |
| Volt | `#C8F03C` | 200, 240, 60 | Accent. Fills, tags, highlights, CTAs on Ink |

Plus plain white `#FFFFFF` as the page background.

Contrast: Ink on white 17.5:1 (pass). Volt on Ink 13.3:1 (pass). Volt on white 1.3:1 (fail): never use Volt as text, thin lines or icons on white. On white pages, Volt only appears as a filled shape with Ink text on top (e.g. a tag pill).

Proportion: roughly 70% white, 25% Ink, 5% Volt. Volt is the highlight, not the base.

## Typography

Inter (Google Fonts, free). Headings ExtraBold 800 with -0.02em tracking; body Regular 400; labels/tags Bold 700, uppercase, +0.08em tracking.

## Guide header pattern

Volt pill tag with Ink text ("GUIDE 01") → Ink ExtraBold heading → grey body text. Cover pages: Ink background, dark-bg logo, white heading, Volt for one highlight word or rule.

## Icon SVG (for embedding)

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 48 48"><rect width="48" height="48" rx="12" fill="#0E1A2B"/><path d="M22 13 A13 13 0 0 0 22 39" fill="none" stroke="#FFFFFF" stroke-width="5.5" stroke-linecap="round"/><path d="M26 9 A13 13 0 0 1 26 35" fill="none" stroke="#C8F03C" stroke-width="5.5" stroke-linecap="round"/></svg>
```
