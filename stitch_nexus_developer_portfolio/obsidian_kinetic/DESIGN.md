---
name: Obsidian Kinetic
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#c4c7c9'
  on-tertiary: '#2d3133'
  tertiary-container: '#8e9193'
  on-tertiary-container: '#272a2c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 120px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
---

## Brand & Style

The design system is engineered for high-end developer portfolios, balancing technical precision with personal authenticity. The brand personality is "The Architect of the Future"—authoritative, sophisticated, and innovative. 

The aesthetic leverages **Modern Minimalism** fused with **Glassmorphism**. It utilizes deep, obsidian-like surfaces to create an infinite canvas, allowing vibrant electric accents to guide the user's eye. The emotional response should be one of trust in technical mastery and excitement for cutting-edge digital craftsmanship. Generous whitespace is used not just for breathing room, but as a deliberate structural element to emphasize high-value content and code.

## Colors

The palette is centered on a "Dark Mode First" philosophy. The primary background is a deep **Obsidian** (#020617), providing a high-contrast base for the **Electric Indigo** (#6366F1) primary accent. 

**Secondary Cyan** (#06B6D4) is used exclusively for interactive highlights and gradient terminal points, creating a sense of energy and motion. 

**Neutral** tones are pulled from the slate palette to maintain a cool, technical temperature. In Light Mode transitions, the Obsidian background flips to a crisp **Slate-50**, while the Glassmorphism effects shift from dark-translucent to light-translucent with increased blur intensity to maintain legibility.

## Typography

Typography is used to reinforce the "High-Tech" narrative. **Geist** serves as the display face, offering a mechanical yet refined personality for headlines. **Inter** handles long-form body text to ensure maximum readability across all devices. 

**JetBrains Mono** is utilized for metadata, tags, and code snippets, acting as a visual cue for the user's developer identity. Large display type should use tight letter spacing to feel "locked-in" and intentional. Mobile headings must scale aggressively to maintain a single-column impact without awkward word breaks.

## Layout & Spacing

This design system employs a **Fixed Grid** on desktop (12 columns) and a **Fluid Grid** on mobile (4 columns). The layout philosophy is "Vertical Momentum"—using large section gaps (120px+) to separate distinct projects or narrative beats.

The 8px base unit governs all padding and margins. Use wide gutters (24px) to emphasize the minimalist, airy feel. Content should be centered within a 1280px container, but decorative elements (like background blur orbs) should bleed to the edge of the viewport to enhance the futuristic, "infinite" aesthetic.

## Elevation & Depth

Depth is communicated through **Glassmorphism** and **Tonal Layering** rather than traditional heavy shadows. 

1.  **The Base:** Deep Obsidian (#020617).
2.  **The Surface:** Semi-transparent slate layers with a 12px-20px backdrop-filter blur. 
3.  **The Highlight:** A 1px subtle inner-border (stroke) on glass cards using a low-opacity white (10-15%) to catch the "light" and define edges.
4.  **The Glow:** Use "Ambient Orbs"—large, low-opacity radial gradients of Electric Indigo placed behind glass layers to create a sense of three-dimensional space and luminescence.

## Shapes

The shape language is "Soft-Tech." Elements use a consistent **0.5rem (8px)** to **1rem (16px)** corner radius. 

- **Standard Buttons & Inputs:** 8px radius for a precise, tool-like feel.
- **Content Cards & Glass Containers:** 16px radius to feel approachable and modern.
- **Interactive Tags:** Pill-shaped (fully rounded) to contrast against the structured grid of the cards.
- **Border Weight:** Keep all borders to a crisp 1px to maintain the high-resolution, technical look.

## Components

### Buttons
Primary buttons use the Indigo-to-Cyan gradient with white text. Hover states should trigger a slight "glow" effect (external box-shadow with primary color at 30% opacity). Secondary buttons are "Ghost" style with a 1px slate border and glass background.

### Cards
Portfolio cards are the centerpiece. Use a 1px border with `backdrop-filter: blur(12px)`. On hover, the border color should transition from slate to the primary Indigo, and the background opacity should increase slightly.

### Input Fields
Inputs should be dark and recessed. Use a subtle 1px bottom border as the default state, transitioning to a full 1px Indigo border focus state. Use JetBrains Mono for placeholder text.

### Code Snippets/Chips
Chips use a mono font and a low-opacity Indigo background (`rgba(99, 102, 241, 0.1)`). For code blocks, use a dedicated glass container with a "Copy" icon that appears only on hover.

### Micro-interactions
Transitions should be swift but smooth (200ms - 300ms) using `cubic-bezier(0.4, 0, 0.2, 1)`. Implement a subtle "parallax" effect on background blur orbs when the user scrolls to enhance the futuristic depth.