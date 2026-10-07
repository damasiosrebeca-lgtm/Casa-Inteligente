---
name: Warm Assistive Home
colors:
  surface: '#fff7fc'
  surface-dim: '#e4d6e5'
  surface-bright: '#fff7fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#feefff'
  surface-container: '#f8e9f9'
  surface-container-high: '#f2e4f3'
  surface-container-highest: '#ecdeed'
  on-surface: '#201923'
  on-surface-variant: '#4c444c'
  inverse-surface: '#362e39'
  inverse-on-surface: '#fbecfc'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#735478'
  primary: '#331839'
  on-primary: '#ffffff'
  primary-container: '#4a2e50'
  on-primary-container: '#ba96be'
  inverse-primary: '#e0bae4'
  secondary: '#705579'
  on-secondary: '#ffffff'
  secondary-container: '#f7d4ff'
  on-secondary-container: '#74597d'
  tertiary: '#23231f'
  on-tertiary: '#ffffff'
  tertiary-container: '#393834'
  on-tertiary-container: '#a3a19c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fcd7ff'
  primary-fixed-dim: '#e0bae4'
  on-primary-fixed: '#2b1131'
  on-primary-fixed-variant: '#593c5f'
  secondary-fixed: '#f8d8ff'
  secondary-fixed-dim: '#ddbbe5'
  on-secondary-fixed: '#291232'
  on-secondary-fixed-variant: '#573d60'
  tertiary-fixed: '#e5e2dc'
  tertiary-fixed-dim: '#c9c6c1'
  on-tertiary-fixed: '#1c1c18'
  on-tertiary-fixed-variant: '#474743'
  background: '#fff7fc'
  on-background: '#201923'
  surface-variant: '#ecdeed'
typography:
  headline-xl:
    fontFamily: Epilogue
    fontSize: 56px
    fontWeight: '900'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Epilogue
    fontSize: 34px
    fontWeight: '900'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Epilogue
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
  headline-md:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '800'
    lineHeight: 32px
    letterSpacing: 0.04em
  headline-sm:
    fontFamily: Epilogue
    fontSize: 18px
    fontWeight: '800'
    lineHeight: 24px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 26px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style
The design system reflects a human-centered, warm, and highly approachable assistive technology initiative. Developed for an academic capstone graduation project (TCC - AMS Desenvolvimento de Sistemas, Etec Pedro Ferreira Alves), it balances technical rigor with accessibility, hospitality, and comfort.

The target audience encompasses evaluation committees, academic peers, sponsors, and primary end-users—specifically seniors, individuals with motor impairments, and their families looking for low-cost home automation.

The design movement merges **Warm Retro-Modernism** with **Soft Tactile Humanism**:
- Heavy reliance on soft organic pill shapes, generous radii (`rounded-2xl` to `rounded-full`), and warm non-clinical surfaces.
- Expressive, cheerful, and approachable bold headline typography balanced with clear, legible humanist body text.
- Friendly, reassuring color harmony (creamy linen, deep aubergine, and muted lavender) that completely avoids cold, clinical, or intimidating tech aesthetics.

## Colors
The palette is built on soft tactile contrast, comforting earth-creme neutrals, and warm floral violets:

- **Primary (`#4A2E50`)**: Deep eggplant/aubergine. Utilized for main headers, prominent call-to-actions, authentication container frames, and key active focal points.
- **Secondary (`#8B6E94`)**: Muted dusky lilac / grayish lavender. Applied to pill navigation capsules, prominent feature callout cards, form input backgrounds, and informational card blocks.
- **Tertiary / Base Surface (`#F2EFE9` / `#EFECE6`)**: Warm linen creme. Serves as the global backdrop, creating an organic, paper-like feeling that relieves eye strain and communicates domestic warmth.
- **Neutral Dark (`#2D2530`)**: Soft graphite plum-tinted black for primary body copy, guaranteeing high contrast and readability according to WCAG standards without the harshness of pure black.
- **Surface Elevation Tone (`#E6E1D8`)**: Slightly deeper linen tone used for the elevated top navigation app bar, footer surfaces, and inset containers.

## Typography
The typography creates an immediate sense of warmth, distinct personality, and utmost legibility:

- **Headlines (`Epilogue`, weights 800 and 900)**: Rendered with bold, rounded energy reminiscent of friendly retro display typography. Major section headers and category callouts utilize full uppercase with slight negative tracking on large displays to feel unified, confident, and welcoming.
- **Body & Labels (`Plus Jakarta Sans`, weights 400, 500, and 700)**: Provides crisp, open geometric contours that ensure high readability across dense explanatory academic text, forms, and descriptive lists. Generous line height (1.6x - 1.7x) maintains comfort for elderly or low-vision readers.

## Layout & Spacing
The layout follows a centered, contained presentation model prioritizing focus and readability:

- **Layout Structure**: Max-width content boundary of 1200px centered on screen. Grid system defaults to a 12-column layout on desktop, transforming into a 6-column grid on tablet, and a single-column flow on mobile.
- **Header & Footer Anchors**: 
  - **Top Navigation Bar**: Full-width fixed/sticky surface with soft bottom drop-shadow, housing the logo/branding aligned left, horizontal pill navigation group centered, and profile avatar on the far right.
  - **Academic Footer**: Full-width shelf with an upward-projected diffuse shadow, separating the main canvas from institutional credits, course details, and contact markers.
- **Vertical Rhythm**: Generous vertical spacing (`space-xl` to `space-2xl`) between narrative sections to prevent cognitive overload.

## Elevation & Depth
Elevation in this design system avoids harsh high-tech drop shadows, relying instead on warm ambient diffusion and clear surface contrast:

- **Level 0 (Base Canvas)**: Flat linen tone (`#F2EFE9`), zero shadow.
- **Level 1 (Top Bar & Cards)**: Soft ambient spread: `box-shadow: 0 4px 20px -2px rgba(74, 46, 80, 0.08)`. Keeps elements floating naturally above the linen plane.
- **Level 1 (Inverted / Footer)**: Upward diffuse shadow: `box-shadow: 0 -8px 24px -4px rgba(74, 46, 80, 0.10)`. Provides anchor grounding.
- **Level 2 (Active Modals & Authentication Containers)**: Pronounced organic shadow: `box-shadow: 0 12px 32px -6px rgba(74, 46, 80, 0.22)`.
- **Form Controls & Embedded Media**: Inset depth with subtle tonal variation or crisp flat fill, maintaining clean accessibility.

## Shapes
The shape philosophy is defined by hyper-rounded, approachable contours that reinforce human warmth and tactile comfort:

- **Pills (`rounded-full` / `9999px`)**: Standard for all primary navigation buttons, status indicators, badges, and primary interactive action pills.
- **Large Containers & Cards (`rounded-2xl` / `1.5rem` to `2rem`)**: Applied to authentication cards, informational callouts, video preview enclosures, and sponsor feature cards.
- **Inputs & Fields**: Fully rounded stadium/pill shapes (`rounded-full`) or extra-soft `rounded-2xl` to ensure consistent tactile visual harmony across every interactive boundary.

## Components

### Top Navigation Bar
- **Surface**: Warm beige-linen (`#EFECE6` or `#F2EFE9`) with subtle bottom ambient blur shadow.
- **Logo**: House silhouette with embedded heart mark in primary aubergine (`#4A2E50`) accompanied by lowercase or small-caps descriptor below.
- **Navigation Cluster**: Centered sequence of pill buttons (`#8B6E94` background, white bold text, `rounded-full`, horizontal padding `1.25rem`, vertical padding `0.5rem`). Hover states shift to `#4A2E50`.
- **User Avatar**: Circular icon/avatar button positioned at the far right with an aubergine outline and soft neutral fill.

### Buttons & Pills
- **Primary Pill**: Background `#8B6E94` (or `#4A2E50` for high-importance submit actions), text `#FFFFFF`, font `Plus Jakarta Sans` or `Epilogue` uppercase bold, fully rounded (`rounded-full`).
- **Secondary Action**: Inverted state or aubergine `#4A2E50` pill with white text.
- **Tag / Badge Pills**: Compact pill with `#8B6E94` background, white label, small uppercase tracking.

### Informational Cards & Callouts
- **Lilac Content Card**: Solid `#8B6E94` fill, `rounded-3xl` (24px - 32px), internal padding of `2rem`. Text rendered in pure white or off-white for crisp contrast.
- **Sponsor / Feature Card**: Off-white / light creme surface, `rounded-2xl`, with contained logo box, structured metadata, and dark plum typography (`#2D2530`).
- **Feature Quad (Pill Cards)**: Uniform squares/rectangles with `rounded-2xl`, filled with `#8B6E94`, centering bold uppercase benefit labels (`INCLUSÃO`, `SEGURANÇA`, `AUTONOMIA`, `CONFORTO`) in `#2D2530` or white.

### Authentication & Input Forms
- **Form Card**: Deep aubergine card (`#4A2E50`), `rounded-3xl`, center-aligned on canvas.
- **Labels**: Uppercase bold text in white or light creme, positioned above each field.
- **Input Fields**: Soft lavender-tinted background (`#8B6E94` at 80% opacity or `#9A80A2`), no harsh borders, `rounded-full` height 48px, inner text colored off-white/linen.
- **Submit Buttons**: Embedded pill `#2D2530` or `#8B6E94` with white text, providing distinct button-in-card hierarchy.

### Academic Institutional Footer
- **Container**: Elevated full-width shelf with top ambient shadow.
- **Content**: Two-column layout on desktop, single-column on mobile.
- **Typography**: Header `TRABALHO DE CONCLUSÃO DE CURSO: CASA INTELIGENTE` in bold uppercase `Epilogue`, with body elements detailing Instagram handle, contact phone, course tier (3 AMS DS), and school unit (ETEC Pedro Ferreira Alves).