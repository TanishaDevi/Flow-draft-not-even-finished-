---
name: Digital Hearth
colors:
  surface: '#faf9f8'
  surface-dim: '#dadad9'
  surface-bright: '#faf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f2'
  surface-container: '#eeeeed'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e3e2e1'
  on-surface: '#1a1c1c'
  on-surface-variant: '#484555'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f0f0'
  outline: '#797587'
  outline-variant: '#c9c4d8'
  surface-tint: '#603ce2'
  primary: '#5e39e0'
  on-primary: '#ffffff'
  primary-container: '#7757fa'
  on-primary-container: '#fffbff'
  inverse-primary: '#cabeff'
  secondary: '#74593f'
  on-secondary: '#ffffff'
  secondary-container: '#fed9b8'
  on-secondary-container: '#795d43'
  tertiary: '#4f5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#677877'
  on-tertiary-container: '#f3fffe'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6deff'
  primary-fixed-dim: '#cabeff'
  on-primary-fixed: '#1c0062'
  on-primary-fixed-variant: '#4816cb'
  secondary-fixed: '#ffdcbe'
  secondary-fixed-dim: '#e3c0a0'
  on-secondary-fixed: '#2a1704'
  on-secondary-fixed-variant: '#5a422a'
  tertiary-fixed: '#d4e6e5'
  tertiary-fixed-dim: '#b8cac9'
  on-tertiary-fixed: '#0e1e1e'
  on-tertiary-fixed-variant: '#3a4a49'
  background: '#faf9f8'
  on-background: '#1a1c1c'
  surface-variant: '#e3e2e1'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Work Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is centered on the "Welcome Home" aesthetic, evoking feelings of sanctuary, warmth, and nostalgic comfort. It targets an audience seeking a digital refuge that feels more like a lived-in space than a sterile tool. 

The design style is a sophisticated blend of **Minimalism** and **Soft Glassmorphism**. It utilizes heavy whitespace to provide breathing room, layered with semi-translucent surfaces that catch the light. The emotional response is one of safety and tranquility, achieved through a "digital hearth" effect where soft, multi-colored background glows simulate the flicker of a fireplace, grounding the user in a calm, inviting environment.

## Colors
The palette is built on a foundation of "Home Tones"—a collection of soft, muted pastels that create a nurturing atmosphere. 
- **Primary (Peach):** Used for main interactive areas and inviting warmth.
- **Secondary (Mint):** Applied to success states and refreshing background washes.
- **Tertiary (Lavender & Lemon):** Used for organizational accents and subtle categorization.
- **Electric Cobalt:** Reserved strictly for precision accents, high-priority notifications, and primary calls-to-action to provide a sharp, modern contrast to the soft surroundings.
- **Backgrounds:** Use a creamy off-white (`#FDFCFB`) instead of pure white to maintain the organic, paper-like feel. 
- **Digital Hearth Effect:** Implement large, low-opacity radial gradients in the corners of the viewport using the lavender and peach tones to create a sense of ambient depth.

## Typography
This design system utilizes **Noto Serif** for all editorial and display moments to reinforce the literary, traditional feel of a home library. It is paired with **Work Sans** for body text and labels to ensure modern legibility and a grounded, professional structure. 

Headlines should use high-contrast weights to stand out against the soft pastel backgrounds. Body text remains dark charcoal rather than pure black to maintain the gentle visual hierarchy. Labels are set in Work Sans with slightly increased letter spacing for clarity in navigation and small-scale UI elements.

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous margins to emphasize the "Minimalist" influence. 
- **Desktop:** A 12-column grid with 64px outer margins to create a focused center-stage for content.
- **Mobile:** A 4-column grid with 16px margins.
- **Rhythm:** All spacing (padding, margins, gaps) must be multiples of the 8px base unit. 

The philosophy is "Content as Furniture"—elements should be placed with intentionality and wide "walking paths" (whitespace) between them to avoid a cluttered or anxious user experience.

## Elevation & Depth
Depth is communicated through **Tonal Layers** and **Soft Glassmorphism** rather than traditional drop shadows.
- **Surfaces:** Use high-diffusion backdrop blurs (20px - 40px) on containers to suggest they are floating within the "Digital Hearth" atmosphere.
- **Shadows:** When necessary, use extremely subtle, long-range shadows with a tint of the Primary Peach color (`rgba(255, 218, 185, 0.2)`) to simulate natural, warm light sources.
- **Interaction:** Upon hover, elements should slightly increase their translucency or "glow" from within, rather than lifting higher off the page.

## Shapes
The shape language is consistently **Rounded**. There are no sharp corners in the design system, as sharp angles conflict with the "Welcome Home" narrative. 
- Standard components (buttons, inputs) use a 0.5rem (8px) radius.
- Large containers and cards use a 1.5rem (24px) radius to emphasize the soft, pillowy nature of the interface.
- Buttons may occasionally use a fully rounded "pill" shape (rounded-xl) for secondary actions to differentiate them from primary rectangular-rounded forms.

## Components
- **Buttons:** Primary buttons use a solid Peach or Mint fill with dark text. The "Electric Cobalt" is used for the "High Alert" or "Final Action" button state. All buttons feature a subtle 1px inner border to give them a tactile, "pressed" quality.
- **Cards:** Cards are semi-transparent with a 40px backdrop blur. They do not have borders; instead, they use a subtle gradient edge to separate them from the background hearth glows.
- **Input Fields:** Use a soft-grey fill with a 2px bottom border that transitions to Electric Cobalt when focused.
- **Chips/Badges:** Small, pill-shaped elements using the Lavender and Lemon tones. These should be low-contrast to avoid distracting from the main narrative.
- **Lists:** Items are separated by generous padding and soft horizontal rules in a muted Lavender tint.
- **The Hearth Component:** A unique background wrapper that hosts the animated radial gradients. It sits at the lowest z-index and provides the color context for the entire application.