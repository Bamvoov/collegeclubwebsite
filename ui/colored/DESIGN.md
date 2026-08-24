---
name: Underground Pulse
colors:
  surface: '#141408'
  surface-dim: '#141408'
  surface-bright: '#3a3a2b'
  surface-container-lowest: '#0f0f04'
  surface-container-low: '#1c1c0f'
  surface-container: '#202013'
  surface-container-high: '#2b2b1d'
  surface-container-highest: '#363527'
  on-surface: '#e6e3ce'
  on-surface-variant: '#cac8aa'
  inverse-surface: '#e6e3ce'
  inverse-on-surface: '#313123'
  outline: '#939277'
  outline-variant: '#484831'
  surface-tint: '#cccd00'
  primary: '#ffffff'
  on-primary: '#323200'
  primary-container: '#e9ea00'
  on-primary-container: '#676800'
  inverse-primary: '#616200'
  secondary: '#ffabf3'
  on-secondary: '#5b005b'
  secondary-container: '#fe00fe'
  on-secondary-container: '#500050'
  tertiary: '#ffffff'
  on-tertiary: '#4a0080'
  tertiary-container: '#f0dbff'
  on-tertiary-container: '#8247b9'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ea00'
  primary-fixed-dim: '#cccd00'
  on-primary-fixed: '#1d1d00'
  on-primary-fixed-variant: '#494900'
  secondary-fixed: '#ffd7f5'
  secondary-fixed-dim: '#ffabf3'
  on-secondary-fixed: '#380038'
  on-secondary-fixed-variant: '#810081'
  tertiary-fixed: '#f0dbff'
  tertiary-fixed-dim: '#ddb7ff'
  on-tertiary-fixed: '#2c0050'
  on-tertiary-fixed-variant: '#622599'
  background: '#141408'
  on-background: '#e6e3ce'
  surface-variant: '#363527'
typography:
  headline-xl:
    fontFamily: Bricolage Grotesque
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.05em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 32px
  subheading:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 16px
  caption:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 14px
spacing:
  margin-page: 2rem
  gutter: 1.5rem
  stack-xs: 0.5rem
  stack-md: 1.5rem
  stack-xl: 4rem
---

## Brand & Style

This design system is built on the raw, anti-establishment aesthetic of **Punk Zine Collage** and **Brutalism**. It is designed for the Journalism Club at VITB to evoke a sense of urgency, DIY activism, and intellectual rebellion. The UI is not meant to be "clean" in the traditional sense; it is a digital "ransom note" that celebrates imperfection.

The visual language utilizes high-contrast overlaps, halftone textures, and jagged edges to simulate physical cut-and-paste techniques. It rejects the polished smoothness of modern SaaS, opting instead for a tactile, gritty experience that feels like a photocopied manifesto.

**Key Stylistic Pillars:**
- **Intentional Chaos:** Overlapping elements and skewed rotations (2° to 5°) create a dynamic, energetic rhythm.
- **Dither & Grain:** Heavy use of halftone patterns and paper-grain overlays to give digital surfaces a physical history.
- **Analogue Artifacts:** Digital representations of "errors" like ink splatters, torn paper borders, and misaligned "registration" marks.

## Colors

The palette is aggressive and high-saturation, designed to grab attention immediately. 

- **Primary (Neon Yellow):** Used for highlighting critical information, news alerts, and primary calls to action. It should always be paired with black text for maximum legibility.
- **Secondary (Vibrant Magenta):** Used for accents, secondary buttons, and decorative ink splatters.
- **Tertiary (Deep Purple):** Acts as the foundational dark layer, providing depth behind the brighter neon elements.
- **Black & White:** Used as the structural backbone. White is often treated as "newsprint" (slightly off-white #F4F4F4) when used for large text blocks to enhance the zine feel.

Colors should be applied with hard edges. Avoid soft gradients; use halftone dots to create transitions between colors if a "gradient" effect is required.

## Typography

The typography strategy focuses on a "Clashing Hierarchy." 

1. **The Lead (Bricolage Grotesque):** Used for headlines. Its quirky, expressive nature mimics the variable weights of woodblock printing. Headlines should often be set in "boxes" (background fills) with slight rotations.
2. **The Intel (Space Grotesk):** Used for body copy. Its geometric but technical feel ensures readability while maintaining the "tech-punk" vibe.
3. **The Metadata (JetBrains Mono):** Used for labels, tags, and small technical details. This reinforces the "unrefined" and "raw data" aspect of the journalism club.

**Ransom Note Effect:** For key section headers, alternate the case or weight of individual words to simulate different paper cutouts being glued together.

## Layout & Spacing

This design system uses a **Fluid/Broken Grid**. While a 12-column underlying structure exists for alignment, elements are encouraged to "break" the grid slightly by overhanging margins or overlapping adjacent columns.

- **Mobile:** 4 columns with tight 16px gutters. Elements usually stack vertically, but images can have a "torn edge" that bleeds off the side of the screen.
- **Desktop:** 12 columns. Use a mix of narrow text columns (inspired by newspapers) and wide, sprawling imagery.
- **Safe Zones:** Maintain a 32px safe margin for critical text, but allow decorative elements (ink splatters, paper scraps) to enter the margins freely.

## Elevation & Depth

Depth is not achieved through shadows, but through **Literal Layering**.

- **Level 0 (Base):** Deep Purple or Black background, often with a subtle halftone or grain texture.
- **Level 1 (Paper):** Newspaper cutouts (White or Yellow) with "torn" border paths. These act as the containers for text.
- **Level 2 (Active Elements):** Vibrant Magenta highlights, buttons, and "taped-on" photos.
- **Shadows:** If shadows are used, they must be "Hard Shadows" (100% opacity, 4px-8px offset, no blur), giving the appearance of thick cardboard cutouts stacked on top of one another.

## Shapes

The shape language is strictly **Sharp and Jagged**. 

- **Corners:** Use 0px radius for all primary containers and buttons. 
- **The "Tear":** Use SVG masks to create irregular, "torn paper" edges on the top or bottom of containers. Avoid straight horizontal lines where possible.
- **Accents:** Use sharp-edged polygons (triangles, starbursts) for callouts and "breaking news" badges.

## Components

- **Buttons:** High-contrast blocks (Primary: Black text on Neon Yellow). On hover, the block should shift its position by 4px (mimicking a physical "click" of a stamp) and change the background to Magenta.
- **Input Fields:** Thick 3px black borders on a white "scrap" background. The cursor should be a thick block.
- **Cards:** Treat cards as "Clippings." Each card should have a slightly different rotation (-2deg to +2deg) and a unique "torn" edge pattern.
- **Chips/Tags:** Use JetBrains Mono text. Backgrounds should look like "Label Maker" tape—black strips with white text.
- **Images:** Use a "Halftone Filter" or high-contrast Black & White thresholding on images to match the zine aesthetic. 
- **The "Splatter" Component:** Randomized SVG ink blots that can be placed behind text or in the corners of sections to break up visual monotony.