---
name: High-Fidelity Command
colors:
  surface: '#0a141d'
  surface-dim: '#0a141d'
  surface-bright: '#313a44'
  surface-container-lowest: '#060f17'
  surface-container-low: '#131d25'
  surface-container: '#172129'
  surface-container-high: '#212b34'
  surface-container-highest: '#2c363f'
  on-surface: '#dae3f0'
  on-surface-variant: '#c5c8b4'
  inverse-surface: '#dae3f0'
  inverse-on-surface: '#28313b'
  outline: '#8f9380'
  outline-variant: '#454839'
  surface-tint: '#b3d266'
  primary: '#ffffff'
  on-primary: '#273500'
  primary-container: '#ceef7f'
  on-primary-container: '#536d05'
  inverse-primary: '#4e6700'
  secondary: '#b9c7e4'
  on-secondary: '#233148'
  secondary-container: '#3c4962'
  on-secondary-container: '#abb9d6'
  tertiary: '#ffffff'
  on-tertiary: '#322f3c'
  tertiary-container: '#e6e0f1'
  on-tertiary-container: '#666271'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ceef7f'
  primary-fixed-dim: '#b3d266'
  on-primary-fixed: '#151f00'
  on-primary-fixed-variant: '#3a4d00'
  secondary-fixed: '#d6e3ff'
  secondary-fixed-dim: '#b9c7e4'
  on-secondary-fixed: '#0d1c32'
  on-secondary-fixed-variant: '#39475f'
  tertiary-fixed: '#e6e0f1'
  tertiary-fixed-dim: '#cac4d5'
  on-tertiary-fixed: '#1d1a26'
  on-tertiary-fixed-variant: '#484553'
  background: '#0a141d'
  on-background: '#dae3f0'
  surface-variant: '#2c363f'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
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
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  data-tabular:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The design system is engineered for mission-critical public safety environments where precision, authority, and rapid data synthesis are paramount. The aesthetic merges **Corporate Modernism** with **High-Contrast Technical** influences, creating a "Management Consulting" layer over deep tech infrastructure.

The target audience consists of high-level decision-makers and field commanders who require a UI that feels reliable, expensive, and indestructible. The emotional response is one of absolute control and clarity. 

Key stylistic pillars:
- **High Contrast:** Pure black and deep navy backgrounds provide a void-like canvas for vibrant lime accents.
- **Architectural Precision:** Every element is aligned to a rigid grid, emphasizing order over organic flow.
- **Technical Luxury:** Use of hairline borders and monospaced accents to denote "pro-grade" equipment.
- **Visual Silence:** Generous whitespace is used not for "breathability," but to reduce cognitive load during high-stress operations.

## Colors
The palette is restricted to maximize the impact of data visualizations and status indicators.

- **Primary (Vibrant Lime):** Reserved exclusively for active states, primary actions, and critical data highlights. It must pop against the dark backgrounds.
- **Secondary (Deep Navy):** Used for surface containers, sidebars, and navigation elements to provide subtle depth against the pure black base.
- **Neutral (Slate Gray):** The primary text color, chosen to reduce eye strain compared to pure white while maintaining high legibility.
- **Base (Pure Black):** The canvas for the entire application, grounding the UI in a "night-mode" professional environment.

## Typography
Typography is treated as a structural element. **Inter** provides a clean, neutral foundation for all interface text, ensuring legibility at small sizes. **JetBrains Mono** (or any high-quality monospace) is introduced for labels, metadata, and data tables to evoke a technical, "deep tech" feel.

- **Headlines:** Use tight letter-spacing and bold weights to project authority.
- **Data Display:** Numerical values should always use monospaced fonts to ensure vertical alignment in tables.
- **Labels:** Small-caps mono text should be used for section headers and overlines to distinguish navigation from content.

## Layout & Spacing
The layout follows a **Rigid 12-Column Grid** system. In this design system, whitespace is "dead space" used to isolate clusters of information, preventing visual clutter during critical incidents.

- **Desktop:** 12-column grid, 24px gutters, 48px outer margins. Elements should snap to the grid without exception.
- **Tablet:** 8-column grid, 16px gutters, 32px outer margins.
- **Mobile:** 4-column grid, 16px gutters, 16px outer margins.
- **Hierarchy:** Use larger gaps (40px+) to separate distinct modules or functional areas, while keeping related inputs tightly grouped (8-16px).

## Elevation & Depth
Depth is created through **Tonal Layering** and **Hairline Outlines** rather than traditional shadows. This maintains the "Management Consulting" professional rigor.

- **Layer 0 (Base):** #000000 for the main background.
- **Layer 1 (Containers):** #0a192f for cards and modules, appearing to sit slightly above the black base.
- **Outlines:** All containers must feature a 1px solid border (#1e293b). For active or focused states, this border transitions to the Primary Lime (#dcfd8b).
- **No Shadows:** Avoid drop shadows. Visual separation is achieved strictly through color value changes and sharp borders.

## Shapes
The shape language is **Strictly Geometric and Sharp**. All corners are 0px (Sharp). This reinforces the uncompromising, technical nature of public safety software. 

- **Interactive Elements:** Buttons and inputs are perfect rectangles. 
- **Icons:** Use linear, 2px stroke icons with square terminals.
- **Data Visualization:** Use sharp-edged bars and area charts. Avoid rounded caps on any graphical representation.

## Components
- **Primary Buttons:** Solid #dcfd8b background with #000000 text. Bold, uppercase Inter. No rounding.
- **Secondary Buttons:** Transparent background with 1px #cbd5e1 border. Text in #cbd5e1.
- **Data Tables:** High-density layouts. Headers in Monospace Small-caps. 1px horizontal dividers in #1e293b. Row hover state uses a subtle #ffffff (5% opacity) tint.
- **Sleek Cards:** #0a192f background, 1px border. Title and "Status Indicator" dot (Lime for active, Slate for inactive) in the top right.
- **Input Fields:** 1px border. On focus, the border turns Lime, and a subtle "glow" (1px Lime outer stroke) is permitted to highlight the active cursor.
- **Status Chips:** Rectangular, small monospace text. Background is a 10% opacity version of the status color (e.g., 10% Lime for "Active").
- **Abstract Networks:** Use thin, 0.5px gray lines with small square nodes to create background patterns or "tech-corporate" textures in empty states.