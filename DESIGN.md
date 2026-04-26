---
name: Cybernetic Stealth
colors:
  surface: '#14121d'
  surface-dim: '#14121d'
  surface-bright: '#3a3744'
  surface-container-lowest: '#0f0d17'
  surface-container-low: '#1c1a25'
  surface-container: '#201e29'
  surface-container-high: '#2b2834'
  surface-container-highest: '#36333f'
  on-surface: '#e6e0f0'
  on-surface-variant: '#c9c3da'
  inverse-surface: '#e6e0f0'
  inverse-on-surface: '#312f3b'
  outline: '#928ea3'
  outline-variant: '#484457'
  surface-tint: '#c8bfff'
  primary: '#c8bfff'
  on-primary: '#2d009d'
  primary-container: '#5826fe'
  on-primary-container: '#d7cfff'
  inverse-primary: '#5b2cff'
  secondary: '#c8bfff'
  on-secondary: '#2f1c80'
  secondary-container: '#463698'
  on-secondary-container: '#b6abff'
  tertiary: '#ffb5a0'
  on-tertiary: '#601400'
  tertiary-container: '#a9310b'
  on-tertiary-container: '#ffc8ba'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5deff'
  primary-fixed-dim: '#c8bfff'
  on-primary-fixed: '#1a0064'
  on-primary-fixed-variant: '#4300da'
  secondary-fixed: '#e5deff'
  secondary-fixed-dim: '#c8bfff'
  on-secondary-fixed: '#1a0064'
  on-secondary-fixed-variant: '#463698'
  tertiary-fixed: '#ffdbd1'
  tertiary-fixed-dim: '#ffb5a0'
  on-tertiary-fixed: '#3b0900'
  on-tertiary-fixed-variant: '#872100'
  background: '#14121d'
  on-background: '#e6e0f0'
  surface-variant: '#36333f'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
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
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.15em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin: 40px
  unit: 8px
---

## Brand & Style

This design system targets high-end privacy-conscious users and enterprise security firms. The brand personality is authoritative, impenetrable, and technologically superior. It evokes an emotional response of absolute safety within a high-speed digital frontier.

The visual style is a fusion of **Glassmorphism** and **High-Contrast Futuristic**. It utilizes deep, immersive layering to simulate a digital "cockpit" experience. Expect to see intricate "circuit-board" linework, vibrant electric glows that pierce through atmospheric backgrounds, and frosted glass panels that provide structural hierarchy without breaking the sense of an infinite digital void. The aesthetic is heavily inspired by sci-fi HUDs (Heads-Up Displays) and advanced encryption interfaces.

## Colors

The palette is anchored in a weighted **Slate Neutral (#797583)** background, which serves as the technical canvas for the cybernetic elements. The **Electric Violet (#5826fe)** is used for high-energy interactions and focal points, creating a sense of sophisticated power.

**Muted Lavender (#7769cc)** acts as a atmospheric accent, representing data flow and secure connection states. **Industrial Rust (#992600)** is used sparingly for high-alert details, warnings, and high-fidelity technical borders to give components a physical, manufactured feel. All interactive states should leverage `box-shadow` with the primary color to simulate a "glow" rather than a traditional drop shadow.

## Typography

This design system utilizes **Space Grotesk** for its technical, geometric rhythm. It is used for all headings and labels to maintain a "data-heavy" and futuristic appearance. Large display headings should be tightly kerned to emphasize the bold, aggressive nature of the brand.

**Inter** is employed for body copy to ensure maximum readability against dark, vibrant backgrounds. To enhance the futuristic feel, "Label-caps" are frequently used for metadata, status indicators, and small callouts, often paired with a slight electric glow or a thin industrial border.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop, centered within the viewport to create a sense of focus. A 12-column system is used with generous 24px gutters, allowing "cybernetic" decorative lines to run through the negative space between columns.

Spacing is based on an 8px base unit. Component internal padding is generous, creating "breathing room" within high-contrast containers. Layouts should prioritize verticality, with sections separated by distinct gradients or horizontal "divider beams" that glow at the terminal ends.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Backdrop Blurs**. Instead of traditional shadows, surfaces are defined by their opacity and border luminosity.

1.  **Base Layer:** The deepest slate neutral.
2.  **Surface Layer:** Semi-transparent (10-20% opacity) violet tint with a 20px backdrop blur.
3.  **Accent Layer:** Components that are "active" feature a 1px solid industrial rust border and an outer `0 0 15px` glow in the primary electric violet.
4.  **Floating Elements:** Elements like tooltips use high-opacity glass with a secondary lavender "scanner line" animation across the top edge.

## Shapes

The shape language is **Rounded**, using a 0.5rem (8px) base radius. This softens the aggressive nature of the high-tech aesthetic, making the interface feel modern rather than dated.

Buttons and high-priority cards may use larger radii (up to 1.5rem) to suggest a more ergonomic, tactile "pod" feel. Occasionally, certain decorative elements may use 45-degree clipped corners (chamfers) to reinforce the cybernetic/industrial-grade theme.

## Components

### Buttons
Primary buttons are solid electric violet with white text, featuring a subtle outer glow. Secondary buttons use a "Ghost" style with a 1px industrial rust border that illuminates on hover. The cursor interaction should trigger a pulse effect.

### Cards & Containers
Cards must use the glassmorphic style described in Elevation. They should feature a "corner accent"—a small, muted lavender L-shape in one corner—to simulate a digital HUD frame.

### Input Fields
Inputs are dark, recessed rectangles with a 10% opacity white fill. On focus, the border transitions from muted slate to electric violet, and a subtle text-shadow is applied to the input text to make it appear "backlit."

### Status Chips
Chips represent system states (e.g., "Protected," "Encrypted"). They should use the "Label-caps" typography and be encased in a pill-shaped container with a high-saturation background and a matching glowing dot icon.

### Technical Elements
Include specialized components like "Data Stream" dividers (thin animated lines), "Node Maps" (small circular icons connected by 1px paths), and "Scan Overlays" (subtle horizontal gradients that move vertically over images).