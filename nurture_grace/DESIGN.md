---
name: Nurture & Grace
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#4e453f'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#7f756e'
  outline-variant: '#d1c4bc'
  surface-tint: '#6b5b4f'
  primary: '#68594d'
  on-primary: '#ffffff'
  primary-container: '#827165'
  on-primary-container: '#fffbff'
  inverse-primary: '#d7c3b4'
  secondary: '#6b5c4c'
  on-secondary: '#ffffff'
  secondary-container: '#f4dfcb'
  on-secondary-container: '#716252'
  tertiary: '#5f5b55'
  on-tertiary: '#ffffff'
  tertiary-container: '#79746d'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f4dfcf'
  primary-fixed-dim: '#d7c3b4'
  on-primary-fixed: '#241910'
  on-primary-fixed-variant: '#524439'
  secondary-fixed: '#f4dfcb'
  secondary-fixed-dim: '#d7c3b0'
  on-secondary-fixed: '#241a0e'
  on-secondary-fixed-variant: '#524436'
  tertiary-fixed: '#e8e1d9'
  tertiary-fixed-dim: '#ccc5be'
  on-tertiary-fixed: '#1e1b17'
  on-tertiary-fixed-variant: '#4a4641'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
  warm-bg: '#F9F7F5'
  sage-accent: '#A3AC9A'
  sale-blush: '#D4A5A5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-upper:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
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
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 80px
---

## Brand & Style

The design system is crafted for a premium children's retail experience, specifically catering to parents who value both aesthetic sophistication and uncompromising quality. The brand personality is **nurturing, serene, and sophisticated**. It balances the emotional warmth of parenthood with the clean, organized efficiency of a high-end boutique.

The visual direction follows a **Modern Minimalist** aesthetic with **Tactile** influences. It avoids the typical "loud" primary colors associated with children's products in favor of a "quiet luxury" approach. This is achieved through:
- **Generous Whitespace:** Creating a sense of calm and clarity.
- **Soft Layering:** Using subtle shadows and tonal shifts to mimic the softness of premium textiles.
- **Refined Materiality:** UI elements should feel as tactile and high-quality as the products themselves (Carrello strollers, Perina linens).
- **Curated Content:** Large, editorial-style photography is the centerpiece, supported by a clean, geometric UI.

## Colors

The color palette is rooted in a "New Neutral" philosophy, drawing inspiration from natural materials like linen, oak, and stone.

- **Primary (#8C7B6E):** A deep, warm taupe used for key interactions and primary headings. It conveys stability and premium quality.
- **Secondary (#D9C5B2):** A soft sand tone used for secondary actions and subtle background containers.
- **Tertiary (#EAE3DB):** A light cream for large surface areas and separators, keeping the UI airy.
- **Neutral (#2D2926):** A "soft black" (off-charcoal) used for maximum readability without the harshness of pure black.

**Named Colors:**
- `warm-bg`: The primary canvas color for the application to avoid "screen glare."
- `sage-accent`: A muted green used sparingly for organic or eco-friendly callouts.
- `sale-blush`: A sophisticated alternative to bright red for discounts and promotions, maintaining the premium feel.

## Typography

This design system uses **Plus Jakarta Sans** as its sole typeface to ensure a modern, clean, and highly legible experience across all touchpoints. 

- **Display & Headlines:** Use semi-bold weights with slight negative letter-spacing to create a compact, premium editorial look. These should be used for brand statements and collection titles.
- **Body Text:** Optimized for readability with a generous line height (1.5x) to prevent visual fatigue.
- **Labels:** Small, uppercase labels with increased tracking (letter-spacing) are used for metadata, category tags, and overlines to add a touch of structural elegance.
- **Hierarchy:** Maintain a clear contrast between "Display" levels for marketing and "Body" levels for product specifications.

## Layout & Spacing

The layout philosophy is based on a **Fixed-Fluid Hybrid Grid**. Content is contained within a max-width for desktop to preserve the premium boutique feel, while margins expand fluidly on smaller screens.

- **Grid:** A 12-column grid for desktop, 6-column for tablet, and 2-column for mobile product listings.
- **Rhythm:** An 8px base unit governs all spacing.
- **Sectioning:** Large vertical gaps (80px+) are used between major content blocks (e.g., Hero to Featured Collection) to give the products "room to breathe."
- **Component Padding:** Internal component padding should be generous (e.g., 24px for cards) to maintain the airy aesthetic.

## Elevation & Depth

To reflect the softness of baby products, the design system avoids harsh shadows. Instead, it utilizes:

- **Tonal Layering:** Using the `tertiary` and `warm-bg` colors to create depth through subtle contrast rather than shadows.
- **Soft Ambient Occlusion:** When elevation is required (e.g., for "Add to Cart" sticky bars or Modals), use a very large blur (32px+) with a very low opacity (4-6%) shadow tinted with the `primary` color.
- **Glassmorphism (Subtle):** Use background blurs (10px-15px) on header navigation and mobile menus to maintain a sense of context and lightness.
- **Ghost Outlines:** Use 1px solid lines in `secondary_color` for form fields and card borders to maintain structure without adding visual weight.

## Shapes

The shape language is defined by **Soft Geometricism**. Every corner is rounded to evoke safety, comfort, and friendliness.

- **Standard Radius:** 8px (`rounded`) for most components like input fields and small buttons.
- **Large Radius:** 16px (`rounded-lg`) for product cards and featured banners to make them feel inviting.
- **Extra Large Radius:** 24px (`rounded-xl`) for main containers or unique "organic" layout masks.
- **Circular/Pill:** Reserved for status chips (e.g., "New," "Hit") and floating action buttons.

## Components

### Buttons
- **Primary:** Solid `primary_color` with white text. Rounded (8px). High-density padding (16px 32px).
- **Secondary:** Outlined with `primary_color`. 
- **Tertiary/Text:** Pure text in `primary_color` with a subtle underline transition.

### Cards
Product cards should be borderless or have a very faint `tertiary` border. The background should be slightly different from the main page background to define the area. Images should have a `rounded-lg` corner.

### Input Fields
Soft, neutral backgrounds (`warm-bg`) with `primary_color` labels. Focus states should use a 2px `secondary_color` border.

### Chips & Badges
Small, pill-shaped elements. Use `sale-blush` for discounts and `sage-accent` for "In Stock" or "Organic" markers. The text should always use the `label-upper` typography style.

### Lists & Navigation
Vertical lists in menus should have generous hit areas (44px minimum height) with subtle `secondary_color` hover states that use the `rounded` corner token.