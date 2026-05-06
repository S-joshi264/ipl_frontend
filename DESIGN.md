---
name: Stadium Prestige
colors:
  surface: '#161308'
  surface-dim: '#161308'
  surface-bright: '#3d392c'
  surface-container-lowest: '#110e05'
  surface-container-low: '#1f1b10'
  surface-container: '#231f14'
  surface-container-high: '#2e2a1e'
  surface-container-highest: '#393528'
  on-surface: '#eae2cf'
  on-surface-variant: '#d0c6ab'
  inverse-surface: '#eae2cf'
  inverse-on-surface: '#343024'
  outline: '#999077'
  outline-variant: '#4d4732'
  surface-tint: '#e9c400'
  primary: '#fff6df'
  on-primary: '#3a3000'
  primary-container: '#ffd700'
  on-primary-container: '#705e00'
  inverse-primary: '#705d00'
  secondary: '#ffb77d'
  on-secondary: '#4d2600'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#fff4f2'
  on-tertiary: '#690000'
  tertiary-container: '#ffcfc7'
  on-tertiary-container: '#c20000'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe16d'
  primary-fixed-dim: '#e9c400'
  on-primary-fixed: '#221b00'
  on-primary-fixed-variant: '#544600'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#ffdad4'
  tertiary-fixed-dim: '#ffb4a8'
  on-tertiary-fixed: '#410000'
  on-tertiary-fixed-variant: '#930000'
  background: '#161308'
  on-background: '#eae2cf'
  surface-variant: '#393528'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  title-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
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
  unit: 4px
  xs: 0.5rem
  sm: 1rem
  md: 1.5rem
  lg: 2.5rem
  xl: 4rem
  gutter: 24px
  margin: 40px
---

## Brand & Style

The design system is engineered to evoke the high-stakes adrenaline of a professional sports auction held under floodlights. It targets a sophisticated audience that appreciates the intersection of traditional sports heritage and futuristic digital precision. 

The aesthetic is anchored in **Glassmorphism**, utilizing translucent layers to suggest depth and clarity. This is elevated by a "Stadium Lighting" concept—where subtle light beams and soft glows simulate the atmosphere of a night match. The overall personality is authoritative, premium, and cinematic, moving away from flat design toward a high-fidelity, tactile digital environment.

## Colors

The palette is rooted in a deep, multi-layered dark mode. The foundation uses **Deep Black** for primary backgrounds to ensure absolute contrast, with **Dark Navy** used for structural containers and sectioning.

- **Gold (#FFD700):** Reserved for "Winner" states, high-value auction items, and primary call-to-actions.
- **Vibrant Orange (#FF8C00):** Used for interactive elements, live status indicators, and momentum shifts.
- **Cricket Red (#D50000):** Utilized for critical alerts, "Sold" markers, and high-energy accents.
- **Team Blue (#004BA0):** Provides a professional, steadying influence for utility icons and secondary information.

Gradients should be used sparingly, primarily as "light leaks" emanating from corners to simulate stadium floodlights.

## Typography

This design system utilizes **Inter** for its systematic clarity and modern corporate feel, ensuring readability against dark, textured backgrounds. For technical data, player stats, and auction numbers, **Space Grotesk** is introduced as a secondary font to inject a futuristic, "digital scoreboard" aesthetic.

Typography should prioritize hierarchy through weight and casing. Use all-caps with generous tracking for labels and category tags to mimic professional sports broadcast graphics.

## Layout & Spacing

The layout follows a **Fixed 12-Column Grid** for desktop views, ensuring that content feels anchored and intentional like a stadium's structural beams. Spacing is generous to allow the "glass" elements room to breathe without overlapping shadows creating visual mud.

A strictly linear 4px scale is used for all internal padding and margins. Vertical rhythm should be exaggerated in hero sections (using `xl` spacing) to create a sense of scale and importance.

## Elevation & Depth

Elevation is conveyed through **Backdrop Blurs (Glassmorphism)** rather than traditional drop shadows. Surfaces closer to the user have a lighter semi-transparent fill and a higher blur radius.

- **Level 1 (Base):** Deep Black background.
- **Level 2 (Cards):** Navy background at 40% opacity, 20px backdrop blur, and a 1px border at 10% white.
- **Level 3 (Modals/Popovers):** Navy background at 60% opacity, 40px backdrop blur, with a subtle **Gold or Orange inner glow** on the top edge to simulate overhead stadium lighting.

Borders are essential; they should be extremely thin (1px) and use linear gradients that transition from semi-transparent white to fully transparent to create "light-catching" edges.

## Shapes

The shape language balances modern approachability with professional precision. A **Rounded (0.5rem)** base is used for most UI components. However, "Action" elements like auction buttons or live badges may use **Pill-shaped (3)** geometry to stand out against the more architectural grid. Large containers and cards should stick to the standard `rounded-lg` (1rem) to maintain a structural, high-end feel.

## Components

### Buttons
Primary buttons use a "Glow-State" approach: a solid color fill (Gold or Orange) with a soft outer glow of the same hue. Secondary buttons are "Ghost" style with a 1px border and a backdrop blur, making them feel like glass plates.

### Cards (The "Glass Plate")
The signature component of this design system. They must feature a subtle gradient border. In the top-right corner of a card, a soft "light beam" effect (a radial gradient with low opacity) should be applied to simulate a stadium spotlight hitting the surface.

### Inputs & Selection
Text fields use a dark, inset appearance with a 1px bottom border that illuminates in Gold when focused. Radio buttons and checkboxes utilize the "Cricket Red" or "Team Blue" for selection states to differentiate between technical choices and high-action auction bids.

### The "Auction Ticker"
A custom component designed for this system—a horizontal scrolling bar at the bottom of the screen with live price updates, using **Space Grotesk** and high-contrast Gold text against a blurred navy background.

### Player Badges
Small chips with a 50% opacity background of the Team Blue, using sharp, uppercase typography to denote player roles (e.g., ALL-ROUNDER, BOWLER).