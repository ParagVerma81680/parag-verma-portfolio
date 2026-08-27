---
name: Cloud Drift
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#454653'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#767684'
  outline-variant: '#c6c5d5'
  surface-tint: '#4953bc'
  primary: '#4953bc'
  on-primary: '#ffffff'
  primary-container: '#818cf8'
  on-primary-container: '#101b8a'
  inverse-primary: '#bdc2ff'
  secondary: '#396477'
  on-secondary: '#ffffff'
  secondary-container: '#bae6fd'
  on-secondary-container: '#3d687c'
  tertiary: '#575e72'
  on-tertiary: '#ffffff'
  tertiary-container: '#8e95ab'
  on-tertiary-container: '#262e40'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bdc2ff'
  on-primary-fixed: '#000767'
  on-primary-fixed-variant: '#2f3aa3'
  secondary-fixed: '#bee9ff'
  secondary-fixed-dim: '#a1cde3'
  on-secondary-fixed: '#001f2a'
  on-secondary-fixed-variant: '#1e4c5f'
  tertiary-fixed: '#dbe2fa'
  tertiary-fixed-dim: '#bfc6dd'
  on-tertiary-fixed: '#141b2c'
  on-tertiary-fixed-variant: '#3f4759'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '450'
    lineHeight: 24px
  body-sm:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '450'
    lineHeight: 20px
  label-md:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

This design system is built on a foundation of **Modern Minimalism** infused with **Soft Tonalism**. The objective is to transition from a dense dark-themed environment to a "Cloud Drift" state—an atmosphere that is airy, professional, and calm.

The brand personality is welcoming and precise. It leverages heavy whitespace to reduce cognitive load and uses subtle pastel gradients to suggest movement and depth without clutter. The target audience values a clean, high-performance workspace that feels like a premium, quiet retreat rather than a chaotic digital tool. 

Key visual principles:
- **Luminosity:** Prioritizing light-reflective surfaces over light-absorbing ones.
- **Breathability:** Generous internal padding and external margins.
- **Soft Precision:** High geometric accuracy softened by significant corner radii.

## Colors

The palette is anchored by a soft white and off-white base to create a high-key, bright environment. Color is used purposefully as a navigational guide rather than a background filler.

- **Primary Indigo (#818CF8):** Reserved for high-priority actions, focus states, and active indications. 
- **Pastel Accents:** Lavender, Sky Blue, Mint, and Peach are used for categorization, chip backgrounds, and subtle decorative gradients to differentiate data types.
- **Neutrality:** The background hierarchy utilizes `#F8FAFC` for the global canvas and `#FFFFFF` for elevated cards and containers to create a subtle "pop" effect.
- **Borders:** A consistent, very thin `#F1F5F9` stroke provides structure without introducing visual noise.

## Typography

This design system utilizes **Geist** for its technical precision and clean legibility. To ensure optimal performance on light backgrounds, font weights have been slightly increased (e.g., using weight 450 instead of 400 for standard body text) to compensate for the "thinning" effect of dark text on light surfaces.

- **Headlines:** Feature tight letter spacing and heavier weights to create a strong visual anchor.
- **Body Text:** Maintains a comfortable line height (1.5x) to support the "Cloud" feel of the interface.
- **Labels:** Used for metadata and overlines, these are rendered in uppercase with slightly increased tracking to ensure clarity at small scales.

## Layout & Spacing

The layout philosophy is a **Fixed-Fluid Hybrid**. Content is contained within a 1280px max-width container on desktop, centered with generous 64px outer margins. 

- **Grid:** A 12-column grid system is used with a 24px gutter. 
- **Rhythm:** An 8px linear scale (referenced as 2 units) governs all spatial relationships. 
- **Reflow:** On tablet, margins reduce to 32px. On mobile, the grid collapses to a single column with 16px margins, and vertical spacing is reduced by one step (e.g., `xl` spacing becomes `lg`).
- **Whitespace:** When in doubt, increase the `padding-bottom` on sections to maintain the airy, uncrowded atmosphere.

## Elevation & Depth

Elevation in this design system is achieved through **Soft Tonal Layering** and **Ambient Shadows** rather than stark borders or heavy overlaps.

- **Levels:**
  - **Level 0 (Canvas):** `#F8FAFC`.
  - **Level 1 (Cards/Containers):** `#FFFFFF` with a `shadow-sm` (0 1px 3px rgba(0,0,0,0.05)).
  - **Level 2 (Dropdowns/Modals):** `#FFFFFF` with a `shadow-md` (0 10px 25px rgba(0,0,0,0.03)) and a 1px border of `#F1F5F9`.
- **Shadow Quality:** Shadows should be extremely diffused, using low-opacity cool-grey tints to avoid a "dirty" look on the soft white backgrounds.
- **Interactions:** On hover, Level 1 elements should transition to Level 2 via a subtle Y-axis lift (-2px) and an expanded shadow spread.

## Shapes

The shape language is defined by high-radius curves to evoke friendliness and modern sophistication.

- **Base Radius:** 1rem (16px) for standard UI components like cards and input fields.
- **Large Radius:** 2rem (32px) for decorative containers or feature sections.
- **Pill Shape:** Fully rounded corners (999px) for buttons, chips, and tags.
- **Consistency:** Avoid mixing sharp and rounded corners within the same component hierarchy.

## Components

- **Buttons:** Primary buttons use the Soft Indigo background with white text. Secondary buttons use a transparent background with a 1px `#F1F5F9` border. Both use pill-shaped (rounded-full) geometry.
- **Input Fields:** Use a `#FFFFFF` background with a 1px `#F1F5F9` border. Focus states transition the border to the Primary Indigo and apply a soft glow.
- **Chips:** Utilize the pastel palette for backgrounds (e.g., Soft Mint background with a darker green-tinted text) with a `rounded-full` radius.
- **Cards:** White surfaces with a 16px corner radius and a `shadow-sm`. Padding inside cards should be at least `24px` (`lg`) to maintain the system's breathability.
- **Lists:** Clean rows with a thin bottom border of `#F1F5F9`. Use subtle hover states that change the background to the Primary Indigo at 5% opacity.
- **Progress Indicators:** Use subtle gradients between the Primary Indigo and Sky Blue to show motion and fluidity.