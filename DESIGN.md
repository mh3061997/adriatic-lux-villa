---
name: Adriatic Azure & Stone
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#43474d'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#74777e'
  outline-variant: '#c3c6ce'
  surface-tint: '#48607c'
  primary: '#001529'
  on-primary: '#ffffff'
  primary-container: '#0f2a43'
  on-primary-container: '#7992b0'
  inverse-primary: '#b0c9e9'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#141513'
  on-tertiary: '#ffffff'
  tertiary-container: '#292927'
  on-tertiary-container: '#91908c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e4ff'
  primary-fixed-dim: '#b0c9e9'
  on-primary-fixed: '#001d35'
  on-primary-fixed-variant: '#304963'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e5e2de'
  tertiary-fixed-dim: '#c8c6c2'
  on-tertiary-fixed: '#1c1c19'
  on-tertiary-fixed-variant: '#474744'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap: 120px
---

## Brand & Style

The brand personality is rooted in "Quiet Luxury"—an understated, sophisticated elegance that mirrors the stillness of the Adriatic at dawn. It targets high-net-worth individuals seeking a sanctuary that blends modern architectural precision with the raw beauty of the Mediterranean landscape.

The design style is **Minimalist / Corporate Modern**, leaning heavily into high-end editorial aesthetics. It utilizes expansive whitespace to create "visual breathing room," suggesting that time and space are the ultimate luxuries. The UI should feel airy and light, avoiding cluttered layouts in favor of curated, large-scale imagery and precise typographic alignment.

## Colors

The palette is inspired by the natural materials and environment of the Croatian coastline.

- **Primary (Deep Sea Blue):** #0F2A43. A commanding, dark navy used for primary headings and navigational anchors, providing a stable foundation.
- **Secondary (Aegean Gold):** #C5A059. Drawn directly from the logo, used sparingly for accents, active states, and call-to-action highlights to denote prestige.
- **Tertiary (Istrian Stone):** #F4F1ED. A warm, off-white sand tone used for section backgrounds to soften the interface and avoid the clinical feel of pure white.
- **Neutral (Carbon):** #2D2926. A soft black used for body text to ensure high readability without the harshness of #000.

## Typography

The typography pairing reflects the duality of the brand: historical prestige and modern efficiency.

- **Headlines:** `Libre Caslon Text` provides a literary, established feel. Large display sizes should use slight negative letter-spacing to appear tighter and more intentional.
- **Body & UI:** `Manrope` offers a clean, contemporary contrast. Its geometric yet approachable structure ensures clarity in property details and booking flows.
- **Labels:** Use uppercase `Manrope` with increased letter-spacing for sub-headings and utility labels to create a sense of architectural structure.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop, centered within a 1440px container to maintain control over line lengths and image crops. 

- **Grid:** A 12-column system with generous 24px gutters. 
- **Whitespace:** Emphasize vertical rhythm with large section gaps (120px+) to separate different narratives (e.g., Amenities vs. Location).
- **Responsive Behavior:** On mobile, margins reduce to 24px and the grid collapses to a single column. Imagery should retain its aspect ratio, often bleeding to the edges of the screen to maximize the sense of immersion.

## Elevation & Depth

This system avoids heavy shadows, opting instead for **Tonal Layers** and **Low-Contrast Outlines**.

- **Surfaces:** Depth is created by placing white containers over the `Istrian Stone` (#F4F1ED) background.
- **Outlines:** Use very thin (1px) borders in a slightly darker version of the stone color (#E0DDD7) to define cards and inputs.
- **Interactive Depth:** When a card is hovered, a very soft, highly diffused ambient shadow (Opacity 5%, Blur 30px) may be applied to suggest a gentle lift, mimicking the soft Mediterranean sun.

## Shapes

To reflect the sharp, modern lines of the villa's architecture (as seen in the reference image), the design system utilizes **Sharp (0)** corners. 

Right angles convey precision, luxury, and a "bespoke" feel. Avoid all rounding on buttons, input fields, and image containers. This creates a rigorous, grid-aligned aesthetic that feels high-end and architectural.

## Components

- **Buttons:** Primary buttons are solid `Deep Sea Blue` with white text, sharp corners, and `label-caps` typography. Secondary buttons use a 1px border of the same blue.
- **Inputs:** Minimalist bottom-border-only fields or fully outlined boxes with no fill. Focus states should transition the border color to `Aegean Gold`.
- **Cards:** For villa highlights, use "Floating Image" cards where the image has no border, and the text is positioned below with generous padding.
- **Chips:** Used for "Amenities" (e.g., Private Pool, Sea View). These should be `Istrian Stone` backgrounds with `Deep Sea Blue` text, no border.
- **Navigation:** A transparent header that transitions to a solid `Istrian Stone` background on scroll. Links are in `label-caps`.
- **Imagery:** All images should feature a slight "warm" color grade to align with the Mediterranean theme. Use "Full-Bleed" components for hero sections to emphasize the scale of the property.