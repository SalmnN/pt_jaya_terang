---
name: Global Excellence Design System
colors:
  surface: '#fff8f7'
  surface-dim: '#e8d6d4'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ee'
  surface-container: '#fceae7'
  surface-container-high: '#f6e4e2'
  surface-container-highest: '#f1dfdc'
  on-surface: '#231918'
  on-surface-variant: '#55423f'
  inverse-surface: '#382e2c'
  inverse-on-surface: '#ffedea'
  outline: '#88726e'
  outline-variant: '#dcc0bc'
  surface-tint: '#9c4236'
  primary: '#400000'
  on-primary: '#ffffff'
  primary-container: '#5e150d'
  on-primary-container: '#e3796a'
  inverse-primary: '#ffb4a8'
  secondary: '#81524b'
  on-secondary: '#ffffff'
  secondary-container: '#fec0b6'
  on-secondary-container: '#7a4c45'
  tertiary: '#001c38'
  on-tertiary: '#ffffff'
  tertiary-container: '#00315b'
  on-tertiary-container: '#779aca'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410100'
  on-primary-fixed-variant: '#7d2c21'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#f5b8ae'
  on-secondary-fixed: '#32110d'
  on-secondary-fixed-variant: '#663b35'
  tertiary-fixed: '#d3e4ff'
  tertiary-fixed-dim: '#a5c9fb'
  on-tertiary-fixed: '#001c38'
  on-tertiary-fixed-variant: '#224873'
  background: '#fff8f7'
  on-background: '#231918'
  surface-variant: '#f1dfdc'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Inter
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
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
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
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  unit-xs: 4px
  unit-sm: 8px
  unit-md: 16px
  unit-lg: 24px
  unit-xl: 48px
  unit-xxl: 96px
---

## Brand & Style
The brand personality reflects a world-class FMCG manufacturer that balances industrial scale with consumer-facing quality. The target audience includes international retail partners, supply chain stakeholders, and regional distributors. 

The design style is **Corporate / Modern** with a focus on precision and high-end manufacturing aesthetics. It utilizes a refined architectural structure, generous whitespace to denote "premium" positioning, and crisp visual hierarchy. The emotional response should be one of unwavering reliability, logistical mastery, and culinary excellence. Every element is intentional, avoiding unnecessary flourish in favor of clear, impactful communication of scale and quality.

## Colors
The palette is anchored by **Terracotta Red (#BB5A4C)**, representing a modern, warm, and grounded industrial heritage. This is the dominant color for headers, primary actions, and structural grounding. **Muted Clay (#9D6A62)** acts as a secondary support, while **Deep Indigo (#00315B)** is used surgically as a tertiary accent for high-value Call-to-Actions (CTAs) and success states, evoking a sense of deep-seated trust and professional stability.

**White (#FFFFFF)** serves as the primary canvas to maintain a clean, hygienic feel essential for an FMCG brand. Neutral tones are derived from a warm **Taupe Gray (#827472)**, providing subtle background differentiation for alternating sections (like statistics or logistical details), ensuring the interface feels layered rather than flat. Text utilizes deep earthy neutrals for optimal legibility without the harshness of pure black.

## Typography
This design system utilizes **Inter** exclusively to achieve a systematic, utilitarian, yet modern corporate feel. The typeface’s high x-height ensures exceptional legibility across technical distribution data and marketing copy.

Headlines use tight letter-spacing and bold weights to command attention, while body text maintains generous line-heights for readability in long-form "About Us" or "Investor Relations" content. Labels utilize uppercase tracking to provide a clear distinction for categories and metadata. For mobile, headline sizes scale down aggressively to ensure no more than three words per line on hero sections.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop to ensure content remains centered and readable on large corporate monitors, transitioning to a fluid model for tablets and mobile. 

- **Desktop (1200px+):** 12-column grid, 24px gutters, 64px side margins.
- **Tablet (768px - 1199px):** 8-column grid, 16px gutters, 40px side margins.
- **Mobile (Below 768px):** 4-column grid, 16px gutters, 20px side margins.

Spacing follows an 8px base unit. Section vertical spacing (unit-xxl) is intentionally large to create a sense of prestige and focus. Product grids should use "unit-lg" for internal padding and "unit-xl" for separation between product categories.

## Elevation & Depth
Hierarchy is established primarily through **Tonal Layers** and **Low-Contrast Outlines**. Deep terracotta and indigo surfaces represent the base "foundation" (footers/navigation), while white containers sit on top.

Shadows are used sparingly and should be "Ambient" in nature—extremely soft, with a large blur radius and very low opacity (3-5%). This avoids a "floating" look, instead making components feel as though they are resting gently on a solid surface. For high-importance items like Featured Product Cards, use a subtle 1px border in a slightly darker neutral (#827472) instead of a heavy shadow to maintain the clean corporate aesthetic.

## Shapes
The design system employs **Soft (1)** roundedness. This 4px (0.25rem) base radius provides a subtle modern touch that softens the "cold" feel of a traditional corporate site without becoming too casual or playful. 

Buttons and input fields follow this 4px standard. Large containers, such as product cards or image modules, may scale to 8px (rounded-lg) to accommodate larger photography without looking sharp. Statistical counters and badges remain strictly at the 4px radius to maintain a technical, data-driven appearance.

## Components
- **Buttons:** Primary buttons are Terracotta Red (#BB5A4C) with White text. Secondary/CTA buttons are Deep Indigo (#00315B) with White text. Hover states should involve a subtle shift in brightness, not color.
- **Product Cards:** Use a white background with a 1px #827472 border. Images of canned fish or cooking oil should be high-resolution with consistent lighting. Product titles use `headline-sm`.
- **Statistical Counters:** Large Terracotta numbers (`headline-lg`) paired with Indigo decorative underlines or icons. Labels use `label-md`.
- **Input Fields:** Minimalist design with a 1px gray border that shifts to Terracotta Red on focus. Labels sit above the field in `label-sm`.
- **Lists:** Bulleted lists in "Capabilities" sections should use custom Indigo checkmark icons rather than standard discs.
- **Logistics/Warehouse Modules:** Full-width image backgrounds with `display-lg` typography overlaying a semi-transparent Terracotta scrim (opacity 40%) for maximum legibility of corporate slogans.