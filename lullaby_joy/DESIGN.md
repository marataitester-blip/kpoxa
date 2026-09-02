---
name: Lullaby & Joy
colors:
  surface: '#f7f9fc'
  surface-dim: '#d8dadd'
  surface-bright: '#f7f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#191c1e'
  on-surface-variant: '#40484b'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f4'
  outline: '#71787b'
  outline-variant: '#c0c8cb'
  surface-tint: '#356573'
  primary: '#356573'
  on-primary: '#ffffff'
  primary-container: '#a7d7e8'
  on-primary-container: '#2e5f6d'
  inverse-primary: '#9ecedf'
  secondary: '#366758'
  on-secondary: '#ffffff'
  secondary-container: '#b6ebd8'
  on-secondary-container: '#3a6c5d'
  tertiary: '#745945'
  on-tertiary: '#ffffff'
  tertiary-container: '#edc9b0'
  on-tertiary-container: '#6d5340'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#baeafb'
  primary-fixed-dim: '#9ecedf'
  on-primary-fixed: '#001f27'
  on-primary-fixed-variant: '#1a4d5b'
  secondary-fixed: '#b9eedb'
  secondary-fixed-dim: '#9dd1bf'
  on-secondary-fixed: '#002018'
  on-secondary-fixed-variant: '#1c4f41'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#e3c0a8'
  on-tertiary-fixed: '#2a1708'
  on-tertiary-fixed-variant: '#5a422f'
  background: '#f7f9fc'
  on-background: '#191c1e'
  surface-variant: '#e0e3e6'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The brand personality is nurturing, cheerful, and inherently safe. It aims to evoke a sense of calm and reliability for parents while remaining playful and engaging for children. The target audience includes modern parents and gift-buyers looking for a curated, stress-free shopping experience.

The design style is a blend of **Soft Minimalism** and **Modern Playfulness**. It utilizes a "Cloud-like" aesthetic: generous whitespace to reduce cognitive load, soft shadows to create gentle depth, and organic, rounded forms that feel approachable and "child-proof." Every element is designed to feel soft to the touch, avoiding sharp edges or aggressive transitions.

## Colors

The palette is rooted in soft, desaturated pastels that create a "sanctuary" feel. 

- **Primary (Sky Blue):** Used for main actions, brand identifiers, and highlights. It represents trust and serenity.
- **Secondary (Mint Green):** Used for success states, eco-friendly badges, and secondary accents. It feels fresh and organic.
- **Tertiary (Soft Yellow):** Used for attention-seeking elements like "New Arrivals" or "Sale" tags. It adds warmth and sunshine to the UI.
- **Neutral:** A very light grey-blue is used for backgrounds instead of pure white to reduce eye strain and maintain the soft aesthetic.
- **Text:** Dark slate grey (#334155) is used instead of black to keep the contrast high for readability while maintaining a gentle tone.

## Typography

The typography system prioritizes legibility and a friendly "roundness" that echoes the brand's shapes. 

- **Headlines:** Use *Plus Jakarta Sans*. Its modern, geometric curves feel optimistic and premium.
- **Body & Labels:** Use *Be Vietnam Pro*. It offers exceptional readability at smaller sizes with a warm, contemporary character.
- **Formatting:** Use generous line-heights (1.6 for body) to ensure descriptions of products and safety information are easy to digest for busy parents.

## Layout & Spacing

The layout follows a **Fluid Grid** system with a focus on "breathability." 

- **Desktop:** A 12-column grid with wide 24px gutters. Content is centered with a max-width of 1280px to prevent lines of text from becoming too long.
- **Mobile:** A 2-column or 1-column layout depending on the component, utilizing a 20px side margin to ensure content doesn't feel cramped.
- **Spacing Rhythm:** Based on an 8px scale. Use 16px (2u) for related elements and 32px-48px (4u-6u) for section breathing room.

## Elevation & Depth

This design system uses **Tonal Layers** and **Ambient Shadows** to define hierarchy.

- **Surface 1 (Base):** The neutral background color.
- **Surface 2 (Cards/Containers):** Pure white surfaces that sit atop the base.
- **Shadows:** Avoid harsh, dark shadows. Use a "Cloud Shadow" style: high blur (20px-40px), very low opacity (4-8%), and a slight tint of the primary color (#A7D7E8) to keep the depth feeling light and airy.
- **Interactions:** When a user hovers over a product card, the elevation should increase slightly with a more pronounced, soft shadow to signify interactivity.

## Shapes

The shape language is strictly **Rounded**. There are no sharp 90-degree angles in the UI.

- **Standard Elements:** Buttons, inputs, and small chips use a 0.5rem (8px) radius.
- **Large Elements:** Product cards and hero sections use "rounded-xl" (1.5rem / 24px) to emphasize the soft, safe nature of the products.
- **Icons:** Use icons with rounded terminals and thick, consistent stroke weights to match the typography's friendliness.

## Components

- **Buttons:** Primary buttons are pill-shaped or highly rounded with the Primary Blue color. Use subtle scale-down transforms on click to provide tactile, "squishy" feedback.
- **Cards:** Product cards must have a 24px border radius. They should feature a white background and a very soft blue-tinted ambient shadow. Images within cards should also have a slightly smaller border radius (12px).
- **Input Fields:** Use a light grey-blue background for inputs with a subtle 1px border. When focused, the border transitions to Primary Blue with a soft glow effect (0px 0px 8px).
- **Chips & Tags:** Use low-contrast background colors (e.g., light version of the Tertiary Yellow) for "Sale" or "New" tags, keeping them noticeable but not jarring.
- **Progress Indicators:** Use rounded bars and soft animations for step-by-step checkout processes to maintain the calm atmosphere.
- **Additional Suggestion:** **Category Bubbles.** Circular navigation elements with illustrative icons representing categories (Toys, Clothing, Nursery) to make the mobile experience more playful.