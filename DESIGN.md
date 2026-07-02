---
name: StyleAI
colors:
  surface: '#faf9fe'
  surface-dim: '#dad9df'
  surface-bright: '#faf9fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f8'
  surface-container: '#eeedf3'
  surface-container-high: '#e9e7ed'
  surface-container-highest: '#e3e2e7'
  on-surface: '#1a1b1f'
  on-surface-variant: '#46464a'
  inverse-surface: '#2f3034'
  inverse-on-surface: '#f1f0f5'
  outline: '#77777b'
  outline-variant: '#c7c6ca'
  surface-tint: '#5f5e60'
  primary: '#171819'
  on-primary: '#ffffff'
  primary-container: '#2c2c2e'
  on-primary-container: '#949395'
  inverse-primary: '#c8c6c8'
  secondary: '#5f5e5b'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2dd'
  on-secondary-container: '#656461'
  tertiary: '#320a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#551700'
  on-tertiary-container: '#ea6f42'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e2e4'
  primary-fixed-dim: '#c8c6c8'
  on-primary-fixed: '#1b1b1d'
  on-primary-fixed-variant: '#474649'
  secondary-fixed: '#e5e2dd'
  secondary-fixed-dim: '#c9c6c2'
  on-secondary-fixed: '#1c1c19'
  on-secondary-fixed-variant: '#474743'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59c'
  on-tertiary-fixed: '#380c00'
  on-tertiary-fixed-variant: '#822800'
  background: '#faf9fe'
  on-background: '#1a1b1f'
  surface-variant: '#e3e2e7'
typography:
  display-lg:
    fontFamily: DM Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: DM Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: DM Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: DM Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  container-max: 1200px
  gutter: 20px
---

## Brand & Style
The design system is built on a foundation of **Minimalism** infused with **Editorial Modernism**. It aims to evoke the feeling of a high-end personal concierge: professional, authoritative on trend, yet warm and accessible. The interface prioritizes high-quality lifestyle photography, using generous whitespace to allow imagery to serve as the primary visual driver.

The emotional response should be one of "effortless chic." The UI stays out of the way, acting as a sophisticated frame for the user's personal style journey. Expect clean lines, intentional use of negative space, and a focus on clarity over decorative elements.

## Colors
The palette is centered around "Sophisticated Neutrals" to ensure that the user's clothing photos and trend inspirations remain the focal point.

- **Primary (Charcoal Grey):** Used for typography and structural elements to provide a grounded, high-contrast feel.
- **Secondary (Soft Beige):** The "Paper" tone. Used for large surface areas and background layers to provide warmth and a premium, tactile feel compared to stark white.
- **Tertiary (Coral Accent):** A vibrant, optimistic "Soft Coral" used sparingly for primary actions, notifications, and key highlights to inject energy into the neutral base.
- **Neutral (Slate):** Used for secondary text, borders, and disabled states.

## Typography
This design system utilizes a pairing of two modern sans-serifs. **DM Sans** provides a geometric, high-fashion structure for headlines, while **Hanken Grotesk** offers exceptional legibility and a contemporary technical edge for body copy and data input.

Labels and small metadata should use uppercase styling with slight letter spacing to maintain an "editorial tag" aesthetic. Line heights are generous to preserve the minimalist, airy feel of the brand.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop and a **Fluid 4-column Grid** on mobile.

- **Desktop:** 12-column grid centered in a 1200px container.
- **Mobile:** 20px side margins with a 16px gutter.
- **Spacing Philosophy:** Use 'lg' (40px) and 'xl' (64px) spacing between major sections to emphasize the minimalist "gallery" feel. Data input forms should use 'md' (24px) vertical rhythm to maintain focus and clarity.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows. 

- **Level 0 (Base):** Soft Beige background.
- **Level 1 (Cards/Inputs):** Pure white surfaces with a 1px solid border in a very light neutral (10% opacity Charcoal).
- **Level 2 (Interactive):** Use a subtle, highly diffused "Ambient Shadow" (offset: 0, 10; blur: 20; color: Charcoal at 5% opacity) only for active recommendation cards or floating action buttons.
- **Imagery:** Photos should have no borders but may use subtle inner glows to sit softly against the beige background.

## Shapes
The design system uses "Soft" roundedness to balance professional structure with approachable warmth. 

- **Small elements (Inputs, Buttons):** 4px (0.25rem) radius for a sharp, precise look.
- **Large elements (Recommendation Cards, Image Uploaders):** 8px (0.5rem) radius.
- **Icons:** Use a 2px stroke weight with slightly rounded caps to match the typography's geometric nature.

## Components

### Buttons & Interaction
- **Primary Button:** Solid Charcoal Grey background with white Hanken Grotesk text. No rounded corners (0px) to provide a high-fashion "label" look.
- **Secondary Button:** Outline style with 1px Charcoal border.
- **Accent Action:** Soft Coral background for high-priority AI prompts.

### Data Input & Uploads
- **Input Fields:** Minimalist underlines or 1px bordered boxes with Soft Beige fill. Labels sit above the input in `label-md` style.
- **Measurement Input:** Large, clear numerical inputs for height/weight with integrated unit toggles (cm/in).
- **Image Uploader:** A large, dashed-border zone in Soft Beige. On upload, the image should occupy the full container with a "Success" checkmark in Coral.

### Recommendation Cards
- **Structure:** Full-bleed imagery at the top (2:3 aspect ratio).
- **Content:** Item name in `headline-md`, followed by a "Reasoning" chip (e.g., "Matches your skin tone") using `label-sm` on a white background.
- **Action:** A "Shop Now" or "Add to Look" ghost button at the bottom.

### Additional Components
- **Style Progress Bar:** A thin, 2px Coral line showing AI analysis progress.
- **Attribute Chips:** Small, Soft Beige rounded capsules for tags like "Sustainable," "Casual," or "Winter."