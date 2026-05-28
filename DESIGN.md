---
name: Obsidian & Ether
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#0a0a0a'
  on-primary-container: '#7b7979'
  inverse-primary: '#5f5e5e'
  secondary: '#c8c8b0'
  on-secondary: '#303221'
  secondary-container: '#494a38'
  on-secondary-container: '#b9baa3'
  tertiary: '#e1c299'
  on-tertiary: '#402d10'
  tertiary-container: '#120800'
  on-tertiary-container: '#8f7552'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e4e4cc'
  secondary-fixed-dim: '#c8c8b0'
  on-secondary-fixed: '#1b1d0e'
  on-secondary-fixed-variant: '#474836'
  tertiary-fixed: '#feddb3'
  tertiary-fixed-dim: '#e1c299'
  on-tertiary-fixed: '#281801'
  on-tertiary-fixed-variant: '#584324'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-xl:
    fontFamily: Bodoni Moda
    fontSize: 80px
    fontWeight: '700'
    lineHeight: 96px
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 28px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 32px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 24px
  max-width: 1440px
---

## Brand & Style

This design system is anchored in the concept of "Cinematic Architecture." It targets an ultra-high-net-worth audience seeking exclusivity, tranquility, and precision. The brand personality is authoritative yet understated, prioritizing the visual weight of architectural photography over dense information.

The visual style blends **Apple-inspired Minimalism** with **Editorial Glassmorphism**. It utilizes expansive whitespace to create a "gallery" feel, where every UI element feels like a curated artifact. High-contrast typography and fine-line borders provide a sense of technical rigor, while frosted glass surfaces and soft light-leaks evoke a tactile, premium atmosphere. The emotional response is one of calm, quiet luxury and absolute confidence.

## Colors

The palette is driven by **Deep Obsidian**, providing a cinematic, "infinite" backdrop that allows property photography to glow. **Champagne Beige** and **Warm Sand** are used for interactive elements and subtle accents, providing a human, organic warmth to the digital environment. **Crisp White** is reserved for primary typography and hairline dividers to ensure surgical legibility.

Color is applied through a "layered depth" strategy:
- **Surface (Base):** Deep Obsidian (#0A0A0A).
- **Surface (Container):** Semi-transparent Obsidian or frosted Champagne Glass.
- **Accents:** Warm Sand (#D2B48C) for high-intent actions.
- **Overlays:** 10-15% opacity Champagne Beige for glassmorphic blurs.

## Typography

The typographic system relies on a dramatic contrast between the classical elegance of **Bodoni Moda** and the industrial precision of **Inter**. 

Headlines use Bodoni Moda with tight tracking to mimic high-end fashion mastheads. For large display sizes, a slight negative letter-spacing is applied to enhance the "locked-in" architectural feel. Body text is set in Inter with generous line-height to ensure an airy, breathable reading experience. Labels and metadata should always use uppercase Inter with increased letter-spacing to denote a sense of technical specifications or luxury branding.

## Layout & Spacing

The design system utilizes a **Fixed Grid** model for desktop to maintain editorial control over whitespace. A 12-column grid is centered within a 1440px container, utilizing oversized 32px gutters to prevent content density. 

The spacing rhythm is aggressive; use large increments of the 8px base unit (e.g., 80px or 120px) between major sections to emphasize the "luxury of space." On mobile, the layout reflows to a single column with significant vertical padding, ensuring that property images always retain a cinematic aspect ratio (16:9 or 21:9).

## Elevation & Depth

Depth is articulated through **Glassmorphism** and **Ambient Shadows** rather than traditional elevation levels. 

1.  **Base Layer:** The Obsidian background acts as the canvas.
2.  **Glass Layer:** Floating panels use a background blur (20px-40px) and a semi-transparent Champagne Beige fill (10% opacity). A 1px "inner glow" border in high-opacity White (20%) is applied to the top and left edges to simulate light hitting a glass edge.
3.  **Shadows:** Elements use "Architectural Shadows"—extremely soft, large-radius blurs (60px-100px) with very low opacity (5-8%). These shadows should feel like ambient occlusion rather than a direct light source.

## Shapes

The shape language is "Soft-Precision." We avoid the playfulness of heavy rounds in favor of subtle, 4px corners (`roundedness: 1`). This mimics the precise machining of luxury materials like stone, metal, and glass. 

- **Containers & Cards:** 4px radius.
- **Buttons:** 4px radius or occasionally sharp (0px) for high-editorial sections.
- **Media:** Photography should remain sharp (0px) to feel like edge-to-edge architectural renders, while interactive glass overlays on top of media should use the 4px radius.

## Components

### Buttons
Primary buttons feature a solid **Warm Sand** fill with **Deep Obsidian** text for maximum impact. Secondary buttons are "Ghost Glass"—a frosted blur background with a fine 1px White border. All buttons use uppercase label styles with increased letter-spacing.

### Cards (Property Listings)
Cards are designed as immersive windows. They feature edge-to-edge photography with a glassmorphic footer overlay containing the property details. Hover states should trigger a subtle "ken burns" zoom effect on the image rather than a lift in elevation.

### Input Fields
Inputs are minimalist, consisting of a single 1px White bottom border. The label sits above in uppercase Inter. Focus states transition the border color to Warm Sand and introduce a subtle backdrop glow.

### Elegant Carousels
Property galleries use "infinite" carousels with no visible scrollbars. Navigation is handled by oversized, thin-stroke arrows or custom cursor interactions.

### Lists
Lists are separated by "Fine Lines"—0.5px opacity-reduced White dividers. They should have generous vertical padding (24px+) to maintain the system's airy feel.