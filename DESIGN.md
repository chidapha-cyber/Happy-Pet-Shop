---
name: Warm Pet Commerce
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#584237'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#8c7164'
  outline-variant: '#e0c0b1'
  surface-tint: '#9d4300'
  primary: '#9d4300'
  on-primary: '#ffffff'
  primary-container: '#f97316'
  on-primary-container: '#582200'
  inverse-primary: '#ffb690'
  secondary: '#006c4a'
  on-secondary: '#ffffff'
  secondary-container: '#82f5c1'
  on-secondary-container: '#00714e'
  tertiary: '#795900'
  on-tertiary: '#ffffff'
  tertiary-container: '#c49200'
  on-tertiary-container: '#422f00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ffb690'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#783200'
  secondary-fixed: '#85f8c4'
  secondary-fixed-dim: '#68dba9'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005137'
  tertiary-fixed: '#ffdf9f'
  tertiary-fixed-dim: '#f9bd22'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#5c4300'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 34px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
  gutter-sm: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  container-max: 1280px
---

## Brand & Style

The brand personality is warm, cheerful, playful, trustworthy, and modern. Built for dedicated pet owners who view their pets as family, the interface balances high-energy delight with the nutritional transparency and clinical reliability expected of premium pet wellness brands.

The visual direction blends **Modern Tactile Warmth** with clean, conversion-focused e-commerce patterns. Soft organic rounded forms, generous breathing room, and uplifting chromatic accents pair with crisp typography and subtle micro-elevations to make pet care shopping feel intuitive, joyful, and deeply credible.

## Colors

- **Primary (`#F97316` / `#FF7A30`):** Energetic amber-orange evoking playfulness, vitality, and canine/feline appetite appeal. Used for primary conversion triggers (add to cart, checkout), promotional bursts, and key focal points.
- **Secondary (`#059669` / `#10B981`):** Natural botanical green representing organic ingredients, veterinary wellness, grain-free dietary health, and certified origin badges.
- **Tertiary (`#FBBF24`):** Warm sun gold for product ratings, reward milestones, and pet birthday loyalty cues.
- **Surface & Backgrounds:** The base canvas uses an ultra-warm off-white cream (`#FFFDF9`), transitioning to a crisp surface container (`#FFFFFF`) for product cards, and a subtle soft sand tone (`#F8F6F0`) for secondary layout groupings and informational blocks.
- **Neutral & Typography:** Deep slate (`#1E293B`) serves as the foundational text color to ensure optimal contrast and readability without the harshness of pure black. Supporting captions utilize muted slate (`#64748B`).

## Typography

This system uses **Plus Jakarta Sans** across display, body, and UI labeling. Its wide proportions, gentle geometric curves, and friendly terminals establish an upbeat, welcoming presence without compromising numeric legibility in e-commerce pricing tables or ingredient breakdowns.

- Display and large headlines leverage heavier weights (700/800) with slight negative tracking to produce punchy, inviting storefront hero sections.
- Body levels maintain generous line heights (1.45–1.55) to ensure feeding guides, nutritional analysis, and pet care reviews remain effortless to digest.
- Product badges, ingredient highlights, and metadata rely on compact, uppercase-adjusted small labels (`label-sm`, `label-md`) with boosted letter spacing for immediate visual scanning.

## Layout & Spacing

The layout model uses a responsive 12-column grid system bounded by a max container width of 1280px, anchored by an 8pt spatial cadence:

- **Desktop (1024px+):** 12 columns, 32px gutters (`gutter-lg`), 48px page margins. Product catalog displays a 4-column or 3-column configuration.
- **Tablet (768px - 1023px):** 8 columns, 24px gutters (`gutter-md`), 32px page margins. Category grids reflow to a 2 or 3-column layout.
- **Mobile (under 768px):** 4 columns, 16px gutters (`gutter-sm`), 16px page margins. Product listings switch to a 2-column card matrix or horizontal swipeable carousels.

Spacing between major content blocks leans airy (`space-2xl` to `space-3xl`) to let pet photography shine and prevent promotional fatigue, while in-card product details maintain tight, efficient packing (`space-xs` to `space-md`).

## Elevation & Depth

Visual hierarchy uses a hybrid of **tonal surface stacking** and **warm ambient shadows**:

- **Tonal Layers:** The page background sits on off-white (`#FFFDF9`). Cards and elevated panels sit on pure `#FFFFFF`, complemented by warm neutral containers (`#F8F6F0`) for secondary groupings like nutritional disclosures or bundle options.
- **Ambient Shadows:** Shadows avoid stark cold black, instead using warm amber/slate tinted blurs to evoke gentle indoor sunlight:
  - *Resting Card:* `0 2px 8px -2px rgba(30, 41, 59, 0.05), 0 1px 4px -1px rgba(249, 115, 22, 0.03)`
  - *Interactive Hover:* `0 12px 24px -6px rgba(30, 41, 59, 0.08), 0 4px 10px -2px rgba(249, 115, 22, 0.08)`
  - *Floating Modals / Mini Cart:* `0 20px 40px -10px rgba(30, 41, 59, 0.14), 0 8px 16px -4px rgba(249, 115, 22, 0.05)`
- **Outlines:** Low-contrast borders (`1px solid rgba(226, 232, 240, 0.8)`) are applied to cards and inputs to preserve definition against cream surfaces.

## Shapes

The interface adopts an approachable, soft geometry (`roundedness: 2`):

- **Default Elements (Inputs, Badges, Small Cards):** 0.5rem (8px) radius.
- **Primary Product Cards & Containers (`rounded-lg`):** 1rem (16px) radius, conveying physical tactile friendliness.
- **Hero Banners & Feature Callouts (`rounded-xl`):** 1.5rem (24px) radius.
- **Pill Accents:** Pill shapes (`9999px`) are reserved exclusively for interactive category tags, dietary filter chips, and floating badge counters to contrast against rectangular product packaging visuals.

## Components

### Buttons
- **Primary CTA:** Background `#F97316`, label in white, font weight 600, padding `12px 24px`, rounded to `0.75rem`. On hover: subtle scale `1.02` with elevated warm shadow and `#EA580C` background.
- **Secondary (Health/Action):** Background `#ECFDF5`, text `#059669`, border `1px solid rgba(16, 185, 129, 0.2)`. On hover: `#D1FAE5`.
- **Ghost / Neutral:** Transparent with `#1E293B` text and `1px solid #E2E8F0`. Hover transitions to `#F8FAFC`.

### Product Cards
- Pure white background framed with a crisp `1px solid #F1F5F9` border and resting warm elevation.
- 16px internal padding, top image area enclosed with subtle `12px` rounded corners and a soft neutral backing (`#FBF9F5`) to showcase cut-out pet food packaging.
- Clear vertical stack: Badge shelf (top-left absolute), favorite paw button (top-right), Product Title (`headline-sm`), weight/dietary hint (`body-sm` muted), price block, and quick-add icon button.

### Badges & Chips
- **Dietary & Health Badges:** Pill-shaped, padding `4px 10px`, font size `11px`, bold uppercase. "Organic" / "Grain-Free" in light emerald (`#D1FAE5` with `#065F46` text); "Puppy" / "Senior" in soft cream (`#FEF3C7` with `#92400E` text).
- **Filter Chips:** Pill shape with `8px 16px` padding. Unselected: `#FFFFFF` border `1px solid #E2E8F0` with `#64748B` text. Selected: `#FFF7ED` background with `#F97316` border and text.

### Input Fields & Selectors
- Height 48px, radius `8px`, background `#FFFFFF`, border `1.5px solid #E2E8F0`, text `#1E293B`.
- Focus state: Border transitions to `#F97316` with a soft ring glow: `0 0 0 3px rgba(249, 115, 22, 0.15)`.
- Quantity Selector: Merged pill/box with minus, numeric text, and plus buttons separated by delicate hairline dividers.

### Checkboxes & Radio Buttons
- Custom square with `4px` radius for checkboxes; circular for radios.
- Unchecked: `1.5px solid #CBD5E1`.
- Checked: `#059669` fill with pure white checkmark/dot indicator.

### Specialized Pet Commerce Components
- **Pet Profile Selector:** Circular avatar tabs displaying customer's registered pets (dog/cat icons or photos) to instantly personalize food formulas.
- **Subscription Toggle ("Subscribe & Save"):** Highlighted container with a warm gold/green accent banner, providing clear radio selection between one-time purchase and recurring auto-ship with calculated savings.