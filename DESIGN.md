---
name: Gilded Minimalist
colors:
  surface: '#fbf9f3'
  surface-dim: '#dbdad4'
  surface-bright: '#fbf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4ed'
  surface-container: '#efeee8'
  surface-container-high: '#eae8e2'
  surface-container-highest: '#e4e2dc'
  on-surface: '#1b1c18'
  on-surface-variant: '#4d4635'
  inverse-surface: '#30312d'
  inverse-on-surface: '#f2f1ea'
  outline: '#7f7663'
  outline-variant: '#d0c5af'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#e9c349'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#415ba4'
  on-tertiary: '#ffffff'
  tertiary-container: '#97b0ff'
  on-tertiary-container: '#254188'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#27438a'
  background: '#fbf9f3'
  on-background: '#1b1c18'
  surface-variant: '#e4e2dc'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 24px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style
The brand personality is one of quiet luxury, architectural precision, and timeless elegance. Targeted at high-end editorial, luxury real estate, or boutique lifestyle brands, the UI evokes a sense of calm, curated space. 

The design style is **Minimalism** infused with **Architectural Detail**. It prioritizes vast white (cream) space, high-quality serif typography, and a "less but better" approach. The aesthetic is inspired by premium gallery spaces and high-fashion editorial layouts where every line and margin is intentional. The transition to a warm, cream-based palette moves away from technical coldness toward a welcoming, sophisticated atmosphere.

## Colors
The palette is centered around a warm, architectural base. 

- **Primary (Elegant Gold):** Used sparingly for high-impact highlights, hairline borders, and subtle interactive states. It represents the "gilt" in the design.
- **Secondary (Deep Charcoal):** Reserved for primary headings and high-contrast UI elements. It provides the structural weight.
- **Background (Light Cream):** The "canvas" of the design system. It is a soft, non-reflective off-white that reduces eye strain while maintaining a premium feel.
- **Neutral (Subtle Grey):** Used for body text and secondary labels to create a clear visual hierarchy against the charcoal headings.

## Typography
The typographic system relies on the contrast between the expressive, high-contrast serifs of **Playfair Display** and the functional, clean lines of **Source Sans 3**. 

Headlines should be treated as architectural elements; large-scale headings use tighter letter spacing and bold weights to command attention. Body text is set in a neutral sans-serif to ensure legibility and a contemporary edge. Labels and small navigation elements use uppercase styling with increased letter spacing to evoke the feeling of engraved architectural signage.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to maintain a sense of a "contained page" or "curated frame," centered within the browser. 

A 12-column grid is used for desktop with generous 64px outer margins to create an "airy" editorial feel. Vertical spacing is intentional and dramatic; use `stack-lg` to separate major content sections, allowing the cream background to act as a visual breather. On mobile, margins compress to 24px, and the grid shifts to a 4-column system, prioritizing vertical stacking and full-width imagery.

## Elevation & Depth
This design system avoids heavy drop shadows, opting instead for **Tonal Layering** and **Thin Outlines**.

Depth is communicated through "Hairline Borders" (0.5pt to 1pt) in Elegant Gold or a slightly darker cream tint. Surfaces that need to appear "elevated" do so by changing their background to pure white (#FFFFFF) against the Light Cream (#F5F5F0) base, rather than using shadows. When shadows are absolutely necessary for high-stack components like modals, use a very large blur (32px+) with extremely low opacity (3-5%) tinted with the primary gold color to maintain a warm, ambient glow.

## Shapes
The shape language is strictly **Sharp**. 0px roundedness reinforces the architectural, structural aesthetic. This applies to buttons, input fields, cards, and image containers. The precision of right angles conveys a sense of formality, high-end construction, and editorial rigor.

## Components
- **Buttons:** Use a "Ghost" or "Solid" style. Primary buttons are Deep Charcoal with White text. Secondary buttons use a 1px Elegant Gold border with Charcoal text. All buttons have 0px border radius and generous horizontal padding.
- **Inputs:** Simple bottom-border only (1px Deep Charcoal). When focused, the border transitions to Elegant Gold. Labels sit above the line in the uppercase `label-md` style.
- **Cards:** Cards do not use shadows. They are defined by a 1px hairline border in a muted gold or a slightly darker cream. Imagery within cards should always be full-bleed to the top and sides.
- **Chips/Tags:** Small, rectangular boxes with a 1px border. Use the `label-md` typography for the internal text.
- **Dividers:** Use horizontal lines in Elegant Gold (#D4AF37) at 0.5px thickness to separate major editorial sections.
- **Navigation:** Use a minimalist top bar. Navigation links are in `label-md`. The active state is indicated by a thin gold underline.