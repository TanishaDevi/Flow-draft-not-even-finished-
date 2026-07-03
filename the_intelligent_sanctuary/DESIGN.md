---
name: The Intelligent Sanctuary
colors:
  surface: '#fbf8ff'
  surface-dim: '#d9d9e6'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f2ff'
  surface-container: '#ededfa'
  surface-container-high: '#e7e7f4'
  surface-container-highest: '#e2e1ef'
  on-surface: '#191b24'
  on-surface-variant: '#434656'
  inverse-surface: '#2e303a'
  inverse-on-surface: '#f0effd'
  outline: '#747688'
  outline-variant: '#c4c5d9'
  surface-tint: '#124af0'
  primary: '#0040e0'
  on-primary: '#ffffff'
  primary-container: '#2e5bff'
  on-primary-container: '#efefff'
  inverse-primary: '#b8c3ff'
  secondary: '#566500'
  on-secondary: '#ffffff'
  secondary-container: '#d3f049'
  on-secondary-container: '#5b6b00'
  tertiary: '#993100'
  on-tertiary: '#ffffff'
  tertiary-container: '#c24100'
  on-tertiary-container: '#ffece6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c3ff'
  on-primary-fixed: '#001356'
  on-primary-fixed-variant: '#0035be'
  secondary-fixed: '#d3f049'
  secondary-fixed-dim: '#b7d32c'
  on-secondary-fixed: '#181e00'
  on-secondary-fixed-variant: '#404c00'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59b'
  on-tertiary-fixed: '#380d00'
  on-tertiary-fixed-variant: '#812800'
  background: '#fbf8ff'
  on-background: '#191b24'
  surface-variant: '#e2e1ef'
  oatmeal: '#F2EFE9'
  linen: '#FAF9F6'
  obsidian: '#1A1B1E'
  cobalt-electric: '#2E5BFF'
  bio-lime: '#D6F34C'
  warm-glow: '#FFD2A0'
typography:
  display-lg:
    fontFamily: notoSerif
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: notoSerif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: notoSerif
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: notoSerif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: hankenGrotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: hankenGrotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  data-lg:
    fontFamily: jetbrainsMono
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  data-sm:
    fontFamily: jetbrainsMono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.4'
  label-caps:
    fontFamily: hankenGrotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  margin-page: 48px
  gutter: 24px
  container-padding: 32px
  section-gap: 64px
---

## Brand & Style

The design system embodies **The Intelligent Sanctuary**, a hybrid aesthetic designed for an operational control system that balances high-stakes data management with psychological safety. It merges the warmth of a "Digital Hearth" with the precision of a high-tech "Flow" state.

The style is a sophisticated blend of **Tactile Neumorphism** and **Glassmorphism**. It utilizes soft, organic textures like oatmeal and linen to ground the user, while layering sharp, translucent glass surfaces for operational data. The visual narrative moves away from sterile corporate minimalism toward **Hyper-Humanism**—where the interface feels like a living, breathing environment that responds to the user's circadian rhythm and system health.

Key characteristics include:
- **Atmospheric Depth:** Layers that feel physical and spatial.
- **Organic Precision:** A tension between soft-touch surfaces and high-visibility technical signals.
- **Circadian Awareness:** Visual transitions that mimic natural solar cycles.

## Colors

The palette is anchored by **Oatmeal**, which serves as the primary surface color to provide a calming, organic foundation. **Electric Cobalt** is the engine of the system, used for interactive elements and critical data streams, while **Bio-Lime** acts as a high-visibility diagnostic signal for system health and "active" states.

- **Primary Surface:** Use `oatmeal` for main application backgrounds. Use `linen` for elevated tactile cards.
- **Operational Accents:** `cobalt-electric` is reserved for primary actions, progress indicators, and data peaks. `bio-lime` is used sparingly for status ok, health indicators, and highlights.
- **Contrast & Depth:** `obsidian` is used for text and deep structural elements to ensure legibility against the warm neutrals.
- **Environmental Lighting:** Implement subtle radial gradients using `warm-glow` at low opacities (5-10%) to simulate ambient sun-leakage in the corners of the interface, shifting toward cooler tones during evening hours.

## Typography

The typographic strategy pairs **Noto Serif** (representing the elegant, human "Sanctuary") with **Hanken Grotesk** and **JetBrains Mono** (representing the "Flow" and technical precision).

- **Headlines:** Use Noto Serif for section titles and branding to evoke emotional softness and authority.
- **Operational Data:** Use JetBrains Mono for all numeric values, timestamps, and technical logs. The monospaced nature ensures data doesn't "jump" during real-time updates.
- **Interface UI:** Use Hanken Grotesk for body copy and general navigation. It provides a clean, neutral balance to the serif headings.
- **Visual Weight:** Keep data labels small and uppercase to maintain a "dashboard" aesthetic without cluttering the "Sanctuary" environment.

## Layout & Spacing

The layout is a **Fluid Grid** system that prioritizes "Digital Breathing Room." It avoids the cramped density of traditional dashboards in favor of wide margins and generous internal padding.

- **Grid Model:** A 12-column system with 24px gutters. Content should typically be contained within cards that span 4, 6, or 8 columns.
- **The Sanctuary Margin:** A minimum page margin of 48px on desktop creates a sense of detachment from the screen edges, mimicking the visual calm of a framed window.
- **Rhythm:** Use an 8px base unit. Component internal padding should lean toward 24px or 32px to reinforce the "soft" feel.
- **Mobile Reflow:** On mobile, margins reduce to 16px, and the 12-column grid collapses into a single vertical stack. Serifs should scale down slightly to maintain elegance without overwhelming the viewport.

## Elevation & Depth

This system uses a dual-depth model to differentiate between "Static Comfort" and "Active Data."

1.  **Tactile Neumorphism (The Base):** Primary buttons and card containers use "Neumorphism 3.0." This involves two shadows: a light shadow (white, -5px -5px) and a soft dark shadow (muted oatmeal-grey, 5px 5px). This gives the impression that the UI is molded from a physical substance like clay or fine linen.
2.  **Glassmorphism (The Flow):** Operational overlays, tooltips, and floating diagnostic panels use backdrop filters. Apply a `blur(12px)` and a semi-transparent white fill (opacity 40-60%). This allows the "Sanctuary" background to bleed through, reducing cognitive load by keeping the user aware of the global context.
3.  **Tonal Layers:** Deep obsidian is reserved for high-contrast "Command Layers"—black glass panels that appear only during critical system alerts.

## Shapes

The shape language is consistently **Rounded**, avoiding sharp corners to maintain the "Sanctuary" theme.

- **Containers:** Standard cards use `rounded-lg` (1rem) to feel approachable.
- **Interactive Elements:** Buttons and input fields use `rounded` (0.5rem) for a precise but soft touch.
- **Operational Accents:** Use "Cyber-Organic" forms—incorporate subtle squiggles or pill-shaped "Ribbon" motifs for connectivity lines between data points to mimic fluid motion.

## Components

- **Buttons:**
    - **Primary:** Tactile neumorphic style with a subtle `cobalt-electric` glow on hover.
    - **Ghost:** Transparent with a thin `linen` border and `bio-lime` text for secondary technical actions.
- **Cards:** The "Digital Hearth" component. High-radius corners, oatmeal background, and soft tactile shadows. Inside these cards, data is presented on "Glass" sub-layers.
- **Input Fields:** Recessed neumorphic wells. When active, the border glows with a soft `cobalt-electric` pulse.
- **Chips & Status:** Pill-shaped (`rounded-xl`). Status "Ok" uses `bio-lime` with a soft "breath" animation (opacity oscillation).
- **Data Visualizations:** Use "Liquid Motion." Line graphs should be smoothed splines rather than jagged points, colored in `cobalt-electric` with a gradient fill that mimics flowing water.
- **The Ribbon:** A specialized component for showing connectivity. It is a thick, translucent path that pulses when data is moving between nodes.