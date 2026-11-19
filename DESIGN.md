---
name: "Fig & Filter"
description: "Warm, tactile, characterful design system for neighbourhood micro-roastery and bakery Fig & Filter."
---

## Overview

Fig & Filter is an independent neighbourhood café, roastery, and scratch bakery open two years in an old picture-framing shop. The visual identity pairs warmth and craftsmanship with quiet, plainspoken confidence. The design evokes the tactile sensory experience of fresh espresso, warm pastry dough, and well-worn timber, serving two primary visitors: a passerby on mobile deciding to step in right now, and an office coordinator reviewing corporate catering packages.

The aesthetic blends warm minimalism with artisanal character: generous breathable margins, rich organic tones, tactile card framing, and refined typographic contrast.

## Colors

The brand color system is rooted in the cafe's namesake fig and amber roasted notes. Deep fig purple conveys depth and craft, complemented by warm amber highlights (strictly reserved for accents, badges, and small decorative borders, never for long body text). Clean, high-contrast near-black on warm off-white creates comfortable long-term legibility.

- **Primary (Deep Fig Purple #4A2C4D):** Anchors identity, headers, prominent containers, and primary call-to-action buttons.
- **Accent (Warm Amber #D9A441):** Reserved for focal accents, badges, tags, and subtle borders. Never used for body text.
- **Surface (Warm Off-White #FAF6F0):** Evokes unbleached linen and warm café ceramics.
- **On-Surface (Near-Black #221E1F):** Grounded, deeply legible neutral text.

```yaml
colors:
  fig-purple: "#4A2C4D"
  warm-amber: "#D9A441"
  warm-offwhite: "#FAF6F0"
  near-black: "#221E1F"
  accent: "#D9A441"
  on-accent: "#221E1F"
  light:
    primary: "#4A2C4D"
    on-primary: "#FAF6F0"
    primary-container: "#5C3760"
    on-primary-container: "#FAF6F0"
    surface: "#FAF6F0"
    on-surface: "#221E1F"
    surface-container: "#F2ECE2"
    on-surface-container: "#221E1F"
    surface-container-high: "#E8E0D2"
    on-surface-container-high: "#221E1F"
    outline: "#6E6359"
    outline-variant: "#D6CBBF"
```

## Typography

A dual-font system balancing historical charm with effortless clarity. Cormorant Garamond provides a literary, sculpted serif for all headings and brand statements. Lato delivers a clean, friendly, open-countered sans-serif that remains crisp across small mobile displays.

```yaml
typography:
  display-lg:
    fontFamily: "Cormorant Garamond"
    fontSize: 40px
    fontWeight: 700
    lineHeight: 48px
    letterSpacing: -0.5px
  display-lg-mobile:
    fontFamily: "Cormorant Garamond"
    fontSize: 30px
    fontWeight: 700
    lineHeight: 36px
    letterSpacing: -0.25px
  headline-lg:
    fontFamily: "Cormorant Garamond"
    fontSize: 32px
    fontWeight: 700
    lineHeight: 40px
    letterSpacing: -0.25px
  headline-lg-mobile:
    fontFamily: "Cormorant Garamond"
    fontSize: 24px
    fontWeight: 700
    lineHeight: 32px
    letterSpacing: -0.2px
  headline-md:
    fontFamily: "Cormorant Garamond"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 28px
    letterSpacing: 0px
  title-lg:
    fontFamily: "Cormorant Garamond"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 24px
    letterSpacing: 0px
  body-lg:
    fontFamily: "Lato"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0px
  body-md:
    fontFamily: "Lato"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0px
  label-lg:
    fontFamily: "Lato"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 20px
    letterSpacing: 0.25px
  label-sm:
    fontFamily: "Lato"
    fontSize: 11px
    fontWeight: 600
    lineHeight: 16px
    letterSpacing: 0.5px
```

## Layout & Spacing

Mobile-first fluid architecture strictly formatted in a single narrow column on phones, extending comfortably to a structured grid on wider viewports without ever breaking readability. A regular 8px scale creates steady visual rhythm across sections and cards.

```yaml
spacing:
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 16px
  gutter-lg: 24px
  gutter-xl: 32px
  section: 48px
  page-margin: 20px
```

## Elevation & Depth

Tactile physical warmth through layered tonal surfaces (`surface-container` #F2ECE2 and `surface-container-high` #E8E0D2) paired with subtle 1px hairline borders in muted parchment tones (`outline-variant` #D6CBBF). No heavy drop shadows; cards feel like physical menu stock and bakery boards resting gently on a cafe counter.

## Shapes

Organic, slightly softened rectangles. Corners use subtle radii that echo stoneware plates and timber counters rather than sharp high-tech edges or overly bubbly pills.

```yaml
rounded:
  sm: 4px
  DEFAULT: 8px
  md: 12px
  lg: 16px
  xl: 20px
  full: 9999px
```

## Motion & Micro-interaction

Understated, crisp micro-interactions that communicate tactile responsiveness. Hover and focus states softly shift color and surface tone within 150ms. Navigation transitions stay swift and natural.

```yaml
motion:
  state-change:
    duration: 150ms
    delay: 0ms
    timingFunction: ease-out
  surface-enter:
    duration: 250ms
    delay: 0ms
    timingFunction: cubic-bezier(0.2, 0, 0, 1)
```

## Voice & Content Strategy

Warm, plainspoken, a little dry-humoured. Direct and informative without marketing jargon or empty superlatives. Headings use sentence case or brief evocative phrases. Action labels use clear, decisive verbs ("Find us", "Order catering", "Call café").
