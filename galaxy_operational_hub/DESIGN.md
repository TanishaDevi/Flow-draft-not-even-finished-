---
name: Galaxy Operational Hub
colors:
  surface: '#0e141a'
  surface-dim: '#0e141a'
  surface-bright: '#333a40'
  surface-container-lowest: '#080f14'
  surface-container-low: '#161c22'
  surface-container: '#1a2026'
  surface-container-high: '#242b31'
  surface-container-highest: '#2f353c'
  on-surface: '#dde3eb'
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#dde3eb'
  inverse-on-surface: '#2b3137'
  outline: '#958ea0'
  outline-variant: '#494454'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3c0091'
  primary-container: '#a078ff'
  on-primary-container: '#340080'
  inverse-primary: '#6d3bd7'
  secondary: '#44e2cd'
  on-secondary: '#003731'
  secondary-container: '#03c6b2'
  on-secondary-container: '#004d44'
  tertiary: '#eec200'
  on-tertiary: '#3c2f00'
  tertiary-container: '#cea700'
  on-tertiary-container: '#4e3e00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#62fae3'
  secondary-fixed-dim: '#3cddc7'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005047'
  tertiary-fixed: '#ffe083'
  tertiary-fixed-dim: '#eec200'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#574500'
  background: '#0e141a'
  on-background: '#dde3eb'
  surface-variant: '#2f353c'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.6'
  data-lg:
    fontFamily: JetBrains Mono
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  orbital-inner: 1.5rem
  orbital-outer: 4rem
  node-gap: 2rem
  panel-padding: 1.25rem
---

## Brand & Style
The design system embodies the "Galaxy Operational Hub"—a high-fidelity, futuristic interface designed for interstellar coordination and deep-space data management. The brand personality is authoritative yet ethereal, blending the precision of an advanced command center with the vast, awe-inspiring beauty of the cosmos. It targets power users who require high information density without sacrificing visual sophistication.

The aesthetic leverages **Glassmorphism** and **Futurism**. The interface should feel like a holographic projection floating in a void, characterized by high-transparency panels, vibrant ambient blurs (nebulas), and razor-sharp data points. The emotional response is one of calm control amidst infinite complexity.

## Colors
The palette is rooted in the deep void. The foundation uses **Deep Obsidian** for the furthest backdrops and **Midnight Navy** for primary UI containers. 

Action and status colors are derived from cosmic phenomena:
- **Electric Violet (Primary):** Used for primary actions, active states, and high-energy nodes.
- **Cosmic Teal (Secondary):** Used for data streams, successful system checks, and navigation accents.
- **Solar Gold (Tertiary):** Reserved for critical alerts, solar-synced data, and premium status indicators.
- **Starlight Silver (Neutral):** The primary color for typography and iconography, ensuring maximum legibility against the dark void.

Gradients should be used sparingly as "nebula" background blurs to provide depth behind glass panels.

## Typography
This design system utilizes a high-contrast typographic pairing to signal both elegance and technical precision. 

**Noto Serif** is used for headlines and display text, treated as "Starlight Elegance." It should appear with generous tracking in display settings to evoke a sense of vastness.

**JetBrains Mono** serves as the functional workhorse. It is used for all body copy, data visualizations, and interface labels. The monospaced nature reinforces the "operational hub" aesthetic, suggesting programmatic accuracy and real-time data processing. All labels should be set in uppercase with increased letter spacing to enhance the technical feel.

## Layout & Spacing
The layout departs from traditional linear grids in favor of an **Orbital Arrangement**. Content is organized into "Systems" and "Nodes." 

- **Orbital Centers:** Primary information sits at the center of the viewport or container.
- **Node Networks:** Related data points are connected via thin, 1px lines (0.2 opacity), creating a web-like structure.
- **Interconnectedness:** Use dynamic padding that scales based on the distance from the "Command Core" (center). 

On mobile, the orbital layout collapses into a vertical "System Stack," where each node becomes a glass card, but maintains the connecting vertical lines to signify a continuous data stream.

## Elevation & Depth
Depth is achieved through **Glassmorphism** and atmospheric lighting rather than traditional shadows.

- **Surface Layers:** All containers use a high-transparency background (`rgba(10, 10, 31, 0.6)`) with a high-intensity `backdrop-filter: blur(20px)`.
- **Borders:** Panels feature a 1px solid border using a gradient of Starlight Silver at 0.3 opacity, with "light-leaks" at the corners using the Primary or Secondary color.
- **Atmospheric Glow:** "Active" nodes emit an outer glow (box-shadow) using their functional color (e.g., Electric Violet) with a large spread (20-40px) and low opacity (0.15) to simulate a nebula's radiance.
- **Sparkle Layer:** A subtle, tiled noise texture at 5% opacity is applied to glass surfaces to mimic starlight dust.

## Shapes
Shapes in the design system are "Soft" to maintain a sophisticated, non-aggressive futurism. 

- **Primary Containers:** Use a 0.25rem radius for a sharp, precision-engineered look.
- **Nodes/Circular Elements:** Interactive nodes and status indicators are perfectly circular to reinforce the orbital theme.
- **Call-to-Action:** Buttons use the same 0.25rem radius, ensuring they feel like integrated modules of the hub's dashboard.

## Components
### Buttons
Buttons are high-transparency glass elements. The "Primary Action" button features a subtle pulse animation on its border using the Electric Violet color. Text is always Monospace Bold.

### Nodes (Chips)
Small, circular or pill-shaped indicators. When "Active," they glow with a 10px blur. They are used for status monitoring and filtering data streams.

### Orbital Cards
Glass panels that house data groups. They do not have shadows; instead, they have a "rim light" effect—a top and left border that is slightly brighter than the bottom and right.

### Data Links
The lines connecting nodes. These are 1px strokes. When a user hovers over a node, the connecting links should "animate" a pulse of light traveling from the origin to the destination.

### Input Fields
Minimalist underlines or "bracketed" corners. The focus state illuminates the brackets with Cosmic Teal.

### System HUD (Navigation)
A fixed, peripheral navigation bar that follows the curvature of the screen (on desktop) or sits as a floating glass dock (on mobile).