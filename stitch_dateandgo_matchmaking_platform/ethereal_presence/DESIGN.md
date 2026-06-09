---
name: Ethereal Presence
colors:
  surface: '#111317'
  surface-dim: '#111317'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e12'
  surface-container-low: '#1a1c1f'
  surface-container: '#1e2023'
  surface-container-high: '#282a2e'
  surface-container-highest: '#333539'
  on-surface: '#e2e2e7'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e2e2e7'
  inverse-on-surface: '#2e3034'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c8c6c7'
  on-secondary: '#303031'
  secondary-container: '#49494a'
  on-secondary-container: '#bab8b9'
  tertiary: '#d0cdd0'
  on-tertiary: '#303032'
  tertiary-container: '#b4b2b4'
  on-tertiary-container: '#454547'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e3'
  secondary-fixed-dim: '#c8c6c7'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474647'
  tertiary-fixed: '#e4e2e4'
  tertiary-fixed-dim: '#c8c6c8'
  on-tertiary-fixed: '#1b1b1d'
  on-tertiary-fixed-variant: '#474649'
  background: '#111317'
  on-background: '#e2e2e7'
  surface-variant: '#333539'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 20px
  unit-xs: 4px
  unit-sm: 8px
  unit-md: 16px
  unit-lg: 32px
  unit-xl: 64px
---

## Brand & Style

The design system is engineered for an elite, high-discretion dating environment. The personality is sophisticated, calm, and deeply intentional, moving away from the "gamified" nature of mass-market dating apps toward a curated, editorial experience. 

The aesthetic leverages **Minimalism** with a **Glassmorphic** layer to represent depth and privacy. Large amounts of whitespace communicate luxury, while subtle motion and soft transitions mirror the pace of a thoughtful conversation. The emotional response is one of safety, exclusivity, and profound quality.

## Colors

The palette is rooted in a deep, "Ink Black" dark mode to provide a sense of evening elegance and discretion. 

- **Primary:** A refined "Champagne Gold" (#D4AF37) used exclusively for high-priority calls to action and verification badges.
- **Secondary/Surface:** Deep charcoal tones that create a tiered background system, allowing content to recede or advance without harsh contrasts.
- **Neutral:** Off-whites and muted silvers used for typography to reduce eye strain and maintain a premium feel.
- **Accents:** Semantic colors (Success/Error) should be desaturated to fit the muted, prestigious environment.

## Typography

This design system employs a high-contrast typographic pairing. **Playfair Display** provides an authoritative, editorial voice for headings, suggesting a legacy of quality. **Manrope** is used for all functional and body text to ensure maximum readability and a modern, clean feel.

On desktop, display sizes are expansive to fill the horizontal space with "white-space-as-luxury." On mobile, the scale tightens significantly to maintain hierarchy without overwhelming the narrow viewport.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to preserve the integrity of the editorial compositions, centering a 1200px container. On smaller screens, it transitions to a fluid model.

- **Desktop (1200px+):** 12-column grid, 24px gutters. Use generous outer margins (80px) to frame the content like a luxury magazine.
- **Tablet (768px - 1199px):** 8-column grid, 20px gutters.
- **Mobile (Up to 767px):** 4-column grid, 16px gutters.

Spacing follows an 8px base unit. Vertical rhythm should be intentionally loose; use `unit-xl` between major sections to prevent the interface from feeling "crowded."

## Elevation & Depth

This design system uses **Tonal Layers** combined with **Glassmorphism** to create a sense of focused immersion.

1.  **Base (Level 0):** Pure #1A1A1B.
2.  **Surface (Level 1):** Subtle 5% lighter tint, used for card backgrounds.
3.  **Floating (Level 2):** Use a 20px backdrop blur with a 10% white border-stroke to simulate frosted glass. This is reserved for navigation bars and modal overlays.
4.  **Shadows:** Shadows are rarely used. When necessary, use extremely large, soft ambient blurs (40px+) with 30% opacity, tinted with the primary gold color to create a "glow" rather than a drop shadow.

## Shapes

The shape language is controlled and "Soft-Modern." 

Standard components utilize a **0.5rem (8px)** corner radius to feel approachable yet structured. Buttons and input fields should strictly adhere to this to maintain a professional architectural feel. 

Profile imagery and featured "Discovery Cards" may use **rounded-lg (16px)** to provide a slightly softer, more humanistic frame for photography. Avoid pill-shapes, as they appear too casual for this brand narrative.

## Components

- **Buttons:** Primary buttons use a solid Gold (#D4AF37) background with black text. Secondary buttons are "Ghost" style with a 1px border. Always use `label-caps` for button text to emphasize importance.
- **Cards:** Use the Glassmorphic treatment for profile cards. Photography should be the focus, with name and age overlaid on a subtle bottom-to-top dark gradient.
- **Input Fields:** Minimalist design with only a bottom border (1px) in the default state, transitioning to a full 1px Gold border on focus. Labels should float above the line.
- **Lists:** High-density lists are avoided. Ensure significant vertical padding (16px-24px) between list items to maintain the feeling of an unhurried experience.
- **Checkboxes/Radios:** Custom-styled to use Gold accents. The selection indicator should be a subtle diamond shape rather than a standard tick, reinforcing the "Premium" metaphor.
- **Concierge Badge:** A specific component for "Verified" users—a small, elegant Gold serif "V" inside a thin-line gold circle.