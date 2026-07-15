---
name: Lumina Tech
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e4e2e1'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e4e2e1'
  inverse-on-surface: '#303030'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#f5f5f5'
  on-tertiary: '#2f3131'
  tertiary-container: '#d9d9d9'
  on-tertiary-container: '#5d5f5f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e4e2e1'
  surface-variant: '#353535'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  data-display:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is engineered to evoke a sense of precision, peak performance, and futuristic luxury. It targets tech-enthusiasts and health-conscious professionals who value data accuracy and sleek aesthetics. 

The visual style is a fusion of **Modern Corporate** and **Glassmorphism**. It utilizes deep, "true black" backgrounds to allow the hardware and health data visualizations to pop with cinematic intensity. The interface relies on light and depth rather than heavy ornamentation, using semi-transparent layers and vibrant blurs to simulate a high-end digital cockpit. The emotional response is one of confidence, clarity, and sophistication.

## Colors

The palette is optimized for OLED displays, utilizing a deep charcoal and black foundation to maximize contrast and energy efficiency.

- **Primary (Electric Cyan):** Used for critical health data, active states, and primary CTAs. It represents the "pulse" of the technology.
- **Secondary (Deep Charcoal):** The primary background color, providing a softer alternative to pure black for better legibility of depth.
- **Tertiary (Clean White):** Reserved for high-priority typography and icons to ensure maximum readability against dark backgrounds.
- **Surface Tints:** Use low-opacity variants of the primary cyan (5-10%) for glassmorphic backgrounds and glow effects.

## Typography

This design system uses **Inter** for its neutral, highly legible, and technical character. It provides a "Swiss-style" clarity that balances the vibrant color palette. **JetBrains Mono** is introduced as a secondary label font to emphasize the "tech" and "data-heavy" nature of the product, used for metadata and small technical specs.

Key emphasis is placed on **Headline-XL** for hero sections to create a premium, editorial feel. All typography should maintain high contrast—use white for primary text and 60% opacity white for secondary/supporting text.

## Layout & Spacing

The design system employs a **Fluid Grid** approach based on an 8px base unit. 

- **Desktop:** 12-column grid with 24px gutters. Use wide margins (64px+) to create a focused, premium "gallery" feel for the product.
- **Mobile:** 4-column grid with 16px gutters and 20px margins.
- **Section Spacing:** Use generous vertical padding (120px - 160px) between landing page sections to allow the hardware imagery to "breathe" and maintain a high-end luxury feel.
- **Alignment:** Content should be predominantly center-aligned for hero and feature highlights to emphasize symmetry and balance.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Ambient Glows**:

1.  **Level 0 (Base):** Pure #000000 or #121212.
2.  **Level 1 (Cards/Containers):** Semi-transparent surfaces (10% white opacity) with a 20px backdrop blur and a 1px inner border (15% white) to define edges.
3.  **Level 2 (Active Elements):** Elements "glow" rather than cast shadows. Use a soft, diffused outer glow of the Primary Cyan color (20% opacity, 40px blur) to indicate interactivity or health status.
4.  **Shadows:** Avoid traditional black shadows. Instead, use "negative glows" (darker blurs) only when an element overlaps a vibrant image background.

## Shapes

The shape language reflects the hardware itself: circular displays and softened rectangular modules. 

- **Containers:** Use `rounded-lg` (1rem/16px) for cards and content blocks. 
- **Interactive Elements:** Buttons and tags should use a more pronounced `rounded-xl` or full pill shape to provide a friendly, touch-optimized appearance.
- **Dividers:** Use extremely thin (1px) lines with 10% white opacity to maintain the minimalist tech aesthetic.

## Components

- **Buttons:** Primary buttons are solid Electric Cyan with black text for maximum punch. Secondary buttons are "ghost" style with a 1px cyan border and glassmorphic background.
- **Chips/Data Tags:** Use pill-shaped containers with a background blur. Icons within chips should be 1.5pt thin line icons.
- **Health Charts:** Use gradient strokes (Cyan to Transparent) for line charts. Data points should have a small "glow" at the tip of the line.
- **Input Fields:** Minimalist design with only a bottom border that turns Electric Cyan on focus.
- **Cards:** Feature cards should use the Level 1 elevation (glassmorphism). Any "active" health card should have a subtle Primary color tint in the background blur.
- **Icons:** Use "thin" or "light" weight (24px grid) stroke icons only. Avoid filled icons unless used as a status indicator.