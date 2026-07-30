---
name: Lumina Tech
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#3a393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#b9ccb2'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#84967e'
  outline-variant: '#3b4b37'
  surface-tint: '#00e639'
  primary: '#ebffe2'
  on-primary: '#003907'
  primary-container: '#00ff41'
  on-primary-container: '#007117'
  inverse-primary: '#006e16'
  secondary: '#99d688'
  on-secondary: '#003a00'
  secondary-container: '#1e5416'
  on-secondary-container: '#8cc77b'
  tertiary: '#fff8f4'
  on-tertiary: '#442b10'
  tertiary-container: '#ffd5ae'
  on-tertiary-container: '#7a5b3c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#72ff70'
  primary-fixed-dim: '#00e639'
  on-primary-fixed: '#002203'
  on-primary-fixed-variant: '#00530e'
  secondary-fixed: '#b5f3a2'
  secondary-fixed-dim: '#99d688'
  on-secondary-fixed: '#002200'
  on-secondary-fixed-variant: '#1b5114'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#e7bf99'
  on-tertiary-fixed: '#2c1701'
  on-tertiary-fixed-variant: '#5d4124'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  button:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style

This design system establishes a **High-End Tech** aesthetic that bridges the gap between terminal-inspired developer tools and premium enterprise software. The brand personality is authoritative, precise, and sophisticated. It moves away from chaotic cyberpunk tropes toward a disciplined "Obsidian & Neon" look.

The visual direction utilizes a **Corporate Modern** foundation infused with **Luminescent Minimalism**. By using a deep charcoal base, the interface creates a vacuum-like space where data and calls-to-action "glow" with purpose. The emotional response should be one of absolute reliability and cutting-edge performance.

Key stylistic principles include:
- **Purposeful Radiance:** Luminescence is reserved for active states, critical data points, and primary interactions.
- **Micro-Precision:** Using hair-line borders and monospaced accents to signal technical rigor.
- **Negative Space:** Generous breathing room between complex data modules to prevent cognitive overload.

## Colors

The palette is strictly engineered for high-contrast legibility in a dark environment.

- **Primary (Matrix Green):** A vibrant, high-saturation green used for the "system-on" state. It should be applied to primary buttons, active toggles, and critical data visualizations.
- **Secondary (Forest Depth):** A muted, deep green used for hover states, subtle fills behind primary elements, and low-priority accents.
- **Neutral (Obsidian):** The foundation of the system. We use a tiered system of blacks: `#0A0A0B` for the global background and `#141416` for surface containers.
- **Support Colors:** 
    - **Status Red:** Used sparingly for system alerts or "Live" indicators.
    - **Text Primary:** Pure White (`#FFFFFF`) for maximum contrast against dark backgrounds.
    - **Text Secondary:** Muted Slate (`#8E8E93`) for metadata and labels.

## Typography

The typography system relies on a three-tier hierarchy to balance modern aesthetics with technical utility.

1.  **Headlines (Geist):** A high-performance sans-serif with a geometric but human character. Used for large displays and section headers.
2.  **Body (Hanken Grotesk):** Provides exceptional readability at scale for documentation and descriptive text.
3.  **Utility/Data (JetBrains Mono):** Used for all technical labels, system status indicators, and numerical data to reinforce the "engine" feel of the product.

**Formatting Rules:**
- All technical labels (e.g., `MODULE // 01`) must be in JetBrains Mono and set to Uppercase.
- Use tight letter spacing for large headlines to maintain a "high-end" editorial feel.
- Ensure all body text maintains at least a 1.6x line height to prevent the dark theme from feeling cramped.

## Layout & Spacing

This design system employs a **12-column Fluid Grid** for desktop and a **4-column grid** for mobile. The layout philosophy is built on "Logical Sections" separated by significant vertical whitespace to allow the glowing elements room to breathe.

**Rhythm:**
- A base unit of **4px** governs all spacing (4, 8, 12, 16, 24, 32, 48, 64).
- **Desktop Margins:** Fixed at 80px to create a cinematic, widescreen feel.
- **Gutter Width:** 24px for all screen sizes to maintain consistent density within components.

**Reflow Rules:**
- On mobile, complex side-by-side data visualizations must stack vertically. 
- Technical metadata (labels) may be hidden or moved to tooltips on small screens to maintain visual clarity.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Controlled Luminescence** rather than traditional drop shadows.

1.  **Base Layer:** `#0A0A0B` (Global background).
2.  **Surface Layer:** `#141416` (Cards and containers).
3.  **Accent Layer:** Thin 1px borders using `#232326`.
4.  **The Glow:** Active components use an "Inner Glow" effect (box-shadow: inset or small spread) using the Matrix Green color at 20-30% opacity. This creates a "backlit" effect common in high-end instrumentation.

**Glassmorphism:** Reserved exclusively for navigation bars and floating modals. Use a `backdrop-filter: blur(20px)` with a slightly transparent surface (`rgba(20, 20, 22, 0.8)`) to maintain the sense of depth.

## Shapes

The shape language is **Soft (Level 1)**. This system avoids the "friendliness" of pill shapes and the "harshness" of sharp corners.

- **Standard Radius:** 4px (`0.25rem`) for buttons, inputs, and small chips.
- **Container Radius:** 8px (`0.5rem`) for cards and modular blocks.
- **Interactions:** Hover states should not change shape, but rather trigger a transition in border-color and a subtle glow.

## Components

### Buttons
- **Primary:** Solid Matrix Green background with black text. On hover, apply a soft green outer glow (spread 10px).
- **Secondary:** Transparent background with a 1px Matrix Green border. Text is Matrix Green.
- **Ghost:** No border, grey text, becomes Matrix Green on hover.

### Inputs & Selects
- Background: Surface Layer (`#141416`).
- Border: 1px Slate (`#232326`).
- Focus State: Border changes to Matrix Green with a subtle 2px glow.

### Cards (Modules)
- Cards should have a 1px top border slightly lighter than the rest to simulate a light source from above.
- Headers within cards should use the `label-mono` style for a "system output" appearance.

### Data Visualization
- Lines and bars must use Matrix Green.
- Background grid lines in charts should be extremely subtle (`#1A1A1C`).
- Use "Glow Points" (small glowing circles) for current data values on line graphs.

### Chips & Tags
- Used for status indicators (e.g., `[SYSTEM: ONLINE]`).
- Style: Monospaced font, all-caps, with a small 6px glowing dot prefix.