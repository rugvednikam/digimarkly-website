---
name: Modern Growth Studio
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#444654'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#747685'
  outline-variant: '#c4c5d6'
  surface-tint: '#2e53d0'
  primary: '#002d9b'
  on-primary: '#ffffff'
  primary-container: '#1a44c2'
  on-primary-container: '#b4c1ff'
  inverse-primary: '#b7c4ff'
  secondary: '#855300'
  on-secondary: '#ffffff'
  secondary-container: '#fea619'
  on-secondary-container: '#684000'
  tertiary: '#00338d'
  on-tertiary: '#ffffff'
  tertiary-container: '#0047be'
  on-tertiary-container: '#b0c2ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#0138b8'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies an energetic, approachable, and empowering partner for small business owners and local entrepreneurs. The brand aesthetic merges the authoritative competence of modern digital marketing with the friendly warmth of a local creative agency. 

The emotional tone balances optimism, clarity, and genuine approachability—steering clear of cold, impersonal corporate consulting or hyper-niche cyberpunk tech tropes. The visual language uses soft curved geometry, luminous white canvas areas, gentle warm and cool tinting, and micro-accents of vibrant energy to make complex growth metrics feel exciting, transparent, and attainable.

## Colors

The palette is engineered around high trust and radiant optimism:

- **Primary (`#1A44C2`):** A deep, resonant royal blue anchoring structural components, main call-to-actions, and high-emphasis headlines. It instills reliability and institutional authority without feeling rigid.
- **Secondary (`#F59E0B`):** A warm, sunlit amber yellow used selectively for milestone highlights, conversion badges, success indicators, and interactive sparks.
- **Tertiary (`#2563EB`):** A luminous vivid blue used for active links, hover transitions, and supportive data visualizations.
- **Neutral Base (`#111827`):** An ink charcoal for readable, high-contrast typography, avoiding pure pitch black to preserve warmth.
- **Surface Canvas:** Clean crisp white (`#FFFFFF`) with subtle layered backdrops spanning soft slate (`#F8FAFC`) and delicate mist (`#F1F5F9`).

## Typography

Plus Jakarta Sans drives the type system across all touchpoints. Its balanced geometry, open apertures, and subtle geometric curves provide high legibility while reinforcing the approachable, forward-moving personality of the agency. 

- Large display tiers leverage tighter tracking (`-0.02em` to `-0.03em`) and heavy weights to anchor hero statements with impact.
- Body tiers maintain open vertical cadence (`1.5` to `1.6` line-height ratio) to ensure effortless readability for long-form case studies, marketing strategies, and client proposals.
- Labels and microcopy retain a slight positive tracking to ensure clarity at compact sizes across badges and chips.

## Layout & Spacing

The layout is built upon a responsive 12-column fluid grid on desktop (max width `1280px`), adapting to 8 columns on tablet devices (`768px - 1024px`) and a 4-column structure on mobile devices (`<768px`).

Content blocks use generous vertical rhythm with section gaps ranging from `4rem` to `6rem` to create breathing room, preventing the clutter common in aggressive marketing templates. Container padding within cards maintains a balanced `1.5rem` to `2.5rem` offset, giving client testimonials, analytics summaries, and service cards plenty of negative space.

## Elevation & Depth

Depth is established via soft ambient illumination rather than harsh borders or dark drop shadows:

- **Level 0 (Flat Canvas):** Clean surface (`#FFFFFF` or `#F8FAFC`) with no shadow.
- **Level 1 (Subtle Cards & Content Tiles):** Soft multi-layered ambient shadow tinted with low-opacity navy: `0 4px 20px -2px rgba(26, 68, 194, 0.05), 0 2px 6px -1px rgba(17, 24, 39, 0.03)`. Includes a hairline border of `rgba(226, 232, 240, 0.8)`.
- **Level 2 (Interactive Floating / Hover):** Expanded dispersion on card hover: `0 12px 32px -4px rgba(26, 68, 194, 0.10), 0 4px 12px -2px rgba(17, 24, 39, 0.04)`.
- **Level 3 (Modals & Overlays):** Deep atmospheric backdrop: `0 24px 48px -12px rgba(15, 23, 42, 0.18)` paired with a soft background scrim (`rgba(17, 24, 39, 0.4)` with `backdrop-blur(4px)`).

## Shapes

The shape hierarchy is soft, friendly, and structured:

- Standard cards, content containers, and client callouts adopt `rounded-2xl` (1rem to 1.5rem border-radius), creating an organic, human feel.
- Form inputs and action buttons sit at a refined `rounded-xl` (0.75rem) to ensure crisp clickability.
- Status badges, category pills, and tag counters utilize fully rounded pill silhouettes (`rounded-full`) to contrast against rectangular content blocks.

## Components

### Buttons
- **Primary:** Deep Royal Blue (`#1A44C2`) fill, white text, bold weight (`600`), `0.75rem` vertical by `1.5rem` horizontal padding, `rounded-xl`. Subtle transition on hover scaling upward to `#0F38B8` with an ambient glow.
- **Accent / Conversion:** Warm Amber (`#F59E0B`) fill, charcoal text (`#111827`), used strictly for high-value conversions like "Get a Free Audit" or "Book Strategy Call".
- **Secondary:** Soft slate surface (`#F1F5F9`) with royal blue label text, shifting to `#E2E8F0` on hover.
- **Ghost:** Transparent background with `#1A44C2` text, displaying an underline or subtle background tint on hover.

### Cards & Case Study Tiles
- Surfaces use crisp white (`#FFFFFF`) framed by `rounded-2xl` geometry and Level 1 elevation.
- Subtle `1px` outer borders in `#E2E8F0` ensure definition against `#F8FAFC` page backdrops.
- Interactive cards shift vertically by `-4px` on hover with an elevation increase to Level 2.

### Chips & Badges
- Built as pill shapes (`rounded-full`) with `0.25rem` vertical and `0.75rem` horizontal padding.
- Growth badges pair a soft yellow tint (`#FEF3C7`) with amber text (`#B45309`).
- Category chips use soft blue (`#EFF6FF`) with deep blue text (`#1A44C2`).

### Form Controls & Inputs
- Height at `48px` with `rounded-xl` corners.
- Inactive state features `#F8FAFC` background with a `#CBD5E1` border.
- Active/focus state transitions border to `#1A44C2` along with a delicate `3px` focus ring tinted at `rgba(26, 68, 194, 0.15)`.

### Selection Controls (Checkboxes & Radios)
- Checkboxes use `rounded-md` borders with `#1A44C2` fill and crisp white check icons when checked.
- Radio buttons feature concentric rings with a central `#1A44C2` dot on active state.

### Metric Callouts & Growth Indicators
- Large display numerals utilizing Plus Jakarta Sans 800 weight, paired with small upward trending badges in emerald or amber to celebrate client wins with immediate clarity.