---
name: Regal Corporate Heritage
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#434651'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#747782'
  outline-variant: '#c4c6d2'
  surface-tint: '#3b5ca5'
  primary: '#002b6d'
  on-primary: '#ffffff'
  primary-container: '#1d428a'
  on-primary-container: '#93b2ff'
  inverse-primary: '#b1c6ff'
  secondary: '#bb0014'
  on-secondary: '#ffffff'
  secondary-container: '#e51d24'
  on-secondary-container: '#fffbff'
  tertiary: '#482700'
  on-tertiary: '#ffffff'
  tertiary-container: '#673b00'
  on-tertiary-container: '#ff9c1a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b1c6ff'
  on-primary-fixed: '#001946'
  on-primary-fixed-variant: '#1f438b'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ac'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#93000d'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#ffb86f'
  on-tertiary-fixed: '#2c1600'
  on-tertiary-fixed-variant: '#693c00'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: IBM Plex Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
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
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

This design system is built for a premium FMCG corporate environment, emphasizing stability, heritage, and high-quality standards. The visual direction is **Corporate / Modern** with a slight lean toward **Minimalism** to ensure the brand's bold colors remain the focal point. 

The system aims to evoke a sense of "Established Trust" and "Operational Excellence." It targets B2B stakeholders and retail partners who value reliability and a clear, professional hierarchy. The interface utilizes generous whitespace, crisp structural alignment, and a sophisticated use of brand accents to guide the user through complex information without visual fatigue.

## Colors

The palette is derived directly from the corporate mark to reinforce brand equity across all digital touchpoints.

- **Primary (Deep Navy):** Extracted from the 'J' and 'B', this color is used for structural elements, headers, and primary navigation to communicate authority.
- **Secondary (Vibrant Red):** Used sparingly as an action-oriented accent for critical notifications, primary buttons, or semantic "live" indicators.
- **Tertiary (Crown Gold):** Reserved for highlights, special call-to-actions, and "Premium" tier indicators. It should be used to draw the eye to high-value features.
- **Neutral (Slate & Smoke):** A range of greys starting from a deep near-black for text, down to a light grey background, ensuring the vibrant primary and secondary colors do not overwhelm the layout.

## Typography

The typographic system utilizes a pairing of **IBM Plex Sans** for headings and **Inter** for UI and body text. 

IBM Plex Sans provides a technical, engineered feel that aligns with industrial FMCG roots, while Inter ensures maximum legibility in data-heavy dashboards and long-form reports. Headers utilize a tighter letter-spacing and heavier weights to command attention. For mobile devices, large headlines are stepped down to maintain a balanced viewport-to-content ratio.

## Layout & Spacing

The design system employs a **Fixed Grid** approach for desktop views to maintain a curated, editorial feel, while transitioning to a **Fluid Grid** for mobile.

- **Grid:** A 12-column grid is used for desktop (1280px max-width) with 24px gutters.
- **Rhythm:** Spacing follows an 8px linear scale. Internal component padding should be strictly 8px, 16px, or 24px to ensure a consistent vertical rhythm.
- **Breakpoints:** 
  - Mobile: < 600px (4 columns, 16px margins)
  - Tablet: 600px - 1024px (8 columns, 24px margins)
  - Desktop: > 1024px (12 columns, 40px margins)

## Elevation & Depth

To maintain a professional FMCG aesthetic, this system uses **Tonal Layers** supplemented by **Low-contrast outlines**. 

Depth is primarily communicated through subtle shifts in background color (e.g., a slightly darker grey for sidebars) rather than heavy shadows. Where elevation is necessary—such as in modals or dropdowns—use an "Ambient Shadow": a very soft, multi-layered shadow with low opacity (10%) and a slight tint of the Primary Navy color to integrate the element into the brand environment. Flat surfaces with 1px borders in a light neutral grey are preferred for card containers to keep the UI feeling "lean."

## Shapes

The shape language is **Soft**. A base radius of 4px (`0.25rem`) is applied to buttons, input fields, and small UI components. Larger containers like cards use 8px (`0.5rem`).

This subtle rounding strikes a balance between the precision of a sharp-edged industrial look and the approachability of a modern digital product. Avoid fully pill-shaped elements unless used for specialized status "chips" to ensure the interface maintains a structured, architectural feel.

## Components

- **Buttons:** Primary buttons use the Primary Navy with white text. Secondary actions use the Vibrant Red but are reserved for high-impact conversions or destructive actions. Ghost buttons use a 1px border.
- **Inputs:** Clean, outlined fields with 4px corner radius. Labels sit above the field in `label-md` style. Focus states use a 2px Primary Navy ring.
- **Chips:** Used for filtering and status. "Premium" or "Gold" status chips should utilize the Tertiary Gold background with dark neutral text.
- **Cards:** White background with a 1px `Neutral-200` border and no shadow. On hover, apply a soft ambient shadow to indicate interactivity.
- **Lists:** High-density lists with subtle dividers. Use Primary Navy for primary list text and `Body-md` for secondary metadata.
- **Data Tables:** Clear header rows using the Primary Navy background with white text to provide strong grounding for complex data sets.