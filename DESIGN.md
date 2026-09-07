---
name: Bio-Synthetic Studio
colors:
  surface: '#101419'
  surface-dim: '#101419'
  surface-bright: '#36393f'
  surface-container-lowest: '#0a0e13'
  surface-container-low: '#181c21'
  surface-container: '#1c2025'
  surface-container-high: '#262a30'
  surface-container-highest: '#31353b'
  on-surface: '#e0e2ea'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#e0e2ea'
  inverse-on-surface: '#2d3136'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#ffb783'
  on-secondary: '#4f2500'
  secondary-container: '#d97722'
  on-secondary-container: '#451f00'
  tertiary: '#45dfa4'
  on-tertiary: '#003825'
  tertiary-container: '#00b982'
  on-tertiary-container: '#00422c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#ffdcc5'
  secondary-fixed-dim: '#ffb783'
  on-secondary-fixed: '#301400'
  on-secondary-fixed-variant: '#713700'
  tertiary-fixed: '#68fcbf'
  tertiary-fixed-dim: '#45dfa4'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#101419'
  on-background: '#e0e2ea'
  surface-variant: '#31353b'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
  label-micro:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  space-3xs: 0.125rem
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
  space-4xl: 6rem
  gutter-mobile: 1rem
  gutter-desktop: 2rem
  container-max: 84rem
---

## Brand & Style

This design system establishes a high-tier digital environment for an elite boutique software engineering consultancy. The visual language unites organic cellular vitality with structural software rigor—a symbiotic fusion of deep natural ecology and advanced computing.

The aesthetic philosophy balances **tactile bio-minimalism** with **deep cybernetic glassmorphism**. Visual compositions feel ambient, alive, and breathing rather than static or clinical. The emotional response is one of quiet authority, unhurried precision, and deep technological mastery. Surfaces are soft-edged, translucent, and reactive, simulating real-world physics through luminescence, subtle refraction, and responsive surface tension.

## Colors

The foundation relies on an impenetrable obsidian slate matrix rather than flat blacks, giving the interface optical depth:

- **Base Matrix (`#0B0F14`):** Canvas bedrock, grounding the interface in an infinite, light-absorbent field.
- **Surface Elevation 1 (`#121820`):** Base container tier, tinted with faint cyan-slate undertones.
- **Surface Elevation 2 (`#1A222D`):** Elevated tactile cards and floating interactive elements.
- **Primary Cyber Emerald (`#10B981`) & Mint Glow (`#34D399`):** Bioluminescent signals conveying active state, successful execution, and architectural vitality.
- **Secondary Solar Coral (`#FB923C`) & Crimson Ember (`#F43F5E`):** Warm organic counters used for critical highlights, latency warnings, and human-centric touchpoints.
- **Text & Contrast:** Primary text is set to high-legibility bleached ice (`#F1F5F9`), secondary text in desaturated slate (`#94A3B8`), and muted metadata in subdued iron (`#475569`).

All glowing interactive states must utilize dual-stop atmospheric gradients tinted with low-alpha luminescence rather than harsh saturated fills.

## Typography

Typography orchestrates an editorial dialogue between human-centric warmth and engineering precision:

- **Headlines (Plus Jakarta Sans):** Carries natural geometry, curved terminals, and open counters that evoke organic forms without losing structural firmness. Used with tight tracking (`-0.02em` to `-0.03em`) to present concise, high-impact statements.
- **Body & Prose (Inter):** Serves as the functional, invisible workhorse ensuring pristine legibility in complex technical specifications, case study breakdowns, and consulting proposals.
- **Technical & Data Accents (JetBrains Mono):** Deployed for metadata, real-time performance indicators, engineering metrics, architecture diagrams, and inline code snippets. All caps variants use positive tracking (`0.06em`) for badge classifications.

## Layout & Spacing

This design system uses a flexible 12-column dynamic fluid grid encased inside a clamped central shell maxing out at `84rem` (1344px). The layout responds through three primary tiers:

- **Mobile (< 768px):** 4 fluid columns, `1rem` outer gutters, compressed vertical rhythm focusing on single-stack reading order.
- **Tablet (768px - 1024px):** 8 fluid columns, `1.5rem` gutters, contextual two-column reflows for engineering metrics and deliverable matrices.
- **Desktop (> 1024px):** 12 fluid columns, `2rem` gutters, asymmetric balance allowing technical data cards to anchor alongside narrative case study sections.

Spacing relies on an 8pt base grid with a 4pt micro-subdivision. Sectional padding is intentionally generous (`4.5rem` to `6rem`) to create an airy, unhurried aesthetic that reflects consulting caliber and clarity of thought.

## Elevation & Depth

Visual hierarchy uses **frosted glassmorphic stratification** and **bioluminescent back-glows** rather than standard muddy drop shadows:

- **Layer 0 (Canvas):** Flat `#0B0F14` textured with a 2% procedural grain overlay to prevent sterile digital flatness.
- **Layer 1 (Card & Module Foundation):** `#121820` rendered at 70% opacity with `16px` backdrop-filter blur and a 1px border stroke (`rgba(255, 255, 255, 0.07)`).
- **Layer 2 (Floating Modals & Interactive Nodes):** `#1A222D` rendered at 85% opacity with `24px` backdrop-filter blur, enclosed by a top-lit border gradient (`rgba(255, 255, 255, 0.15)` fading to `rgba(255, 255, 255, 0.02)`).
- **Atmospheric Glows:** Floating active items cast an extra-diffused radial halo (`blur: 32px` to `48px`, spread: `-8px`) using primary emerald (`rgba(16, 185, 129, 0.18)`) or coral (`rgba(251, 146, 60, 0.14)`), giving components the illusion of levitating over a light source.

## Shapes

The shape architecture is defined by full pill forms (`rounded-full`) for high-touch interactive affordances paired with generous organic curves (`1.5rem` to `2rem`) for outer container modules. 

Key structural rules:
- **Interactive Triggers (Buttons, Badges, Search Bars):** Fully rounded pill geometry (`9999px`), reinforcing physical touch and handheld pebble-like tactile qualities.
- **Structural Cards & Panels:** Generously curved surfaces (`2rem` / `32px` radius on desktop, `1.25rem` / `20px` on mobile), producing an approachable, human contour.
- **Nested Radii Coherence:** Inner elements strictly calculate curvature using concentric offsets (`Radius_outer - Padding = Radius_inner`) to prevent visual friction between card frames and inner nested chips.

## Components

### Interactive Buttons
- **Primary Pill:** Background is a subtle gradient from `#10B981` to `#059669`. Inner top stroke in `rgba(255, 255, 255, 0.35)` to create a tactile chamfered highlight. On hover: scale transform (`1.02`), box shadow bloom with `rgba(16, 185, 129, 0.35)`.
- **Secondary Glass Pill:** Semi-transparent base (`rgba(255, 255, 255, 0.04)`), `1px` subtle white border stroke, text rendered in `#F1F5F9`. On hover: surface brightness increases (`rgba(255, 255, 255, 0.09)`) with faint mint border illumination.

### Chips & Status Badges
- Encased in full-pill containers with `0.25rem` vertical and `0.75rem` horizontal padding.
- Text rendered in `JetBrains Mono` label-micro.
- Active state displays a living pulse: a 6px circular dot featuring an animated radial ping (`#10B981`).

### Form Fields & Inputs
- Enclosed with pill borders or soft-cornered fields (`1rem`), deep `#0D131A` background, and `1px` low-contrast outline (`rgba(255, 255, 255, 0.1)`).
- On focus: outline smoothly shifts to `#34D399` alongside an inner diffuse spread (`0 0 0 3px rgba(52, 211, 153, 0.15)`). Monospaced inline placeholder hints assist technical data entry.

### Cards & Solution Panels
- Built with Layer 1 translucent glass foundations. Cards feature a simulated light sheen: a dynamic radial gradient tracking mouse position on desktop hover.
- Outlines are dynamic: passive state is faint gray slate; active state highlights the edge nearest to the cursor with subtle emerald luminescence.

### Checkboxes & Toggle Controls
- Custom organic rounded switches (`rounded-full`). Unchecked state sits in recessed charcoal (`#1A222D`); checked state slides a bioluminescent pill across an emerald track with quick, elastic spring physics.
- Checkboxes feature rounded squares (`6px` radius) with custom SVG organic check draws on selection.

### Code Display & Telemetry Blocks
- Enclosed in obsidian slate containers with glass header bars displaying file provenance, branch metadata, and latency metrics in `JetBrains Mono`.
- Syntax highlighting uses an organic palette: mint for functions, soft coral for strings, muted lavender for keywords, and iron slate for structural tokens.