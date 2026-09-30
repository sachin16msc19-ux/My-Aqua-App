---
name: Industrial Aqua Pure
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#3f4850'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#707881'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bb9'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#2f6388'
  on-secondary: '#ffffff'
  secondary-container: '#a3d4ff'
  on-secondary-container: '#275c81'
  tertiary: '#006947'
  on-tertiary: '#ffffff'
  tertiary-container: '#00855b'
  on-tertiary-container: '#f5fff6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#cbe6ff'
  secondary-fixed-dim: '#9bccf6'
  on-secondary-fixed: '#001e30'
  on-secondary-fixed-variant: '#0e4b6f'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  metric-display:
    fontFamily: JetBrains Mono
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies an **Industrial-Aquatic Utility** aesthetic engineered for industrial-grade water purification management, camper route delivery logistics, and telemetry-driven plant operations. It merges the clinical precision of laboratory water-testing facilities with the robust practicality of field operations dashboards.

### Personality & Values
- **Clinical Purity:** Imparting uncompromising trust, sanitation, and safety through sharp contrasts, crystalline surfaces, and pristine whitespace.
- **Operational Utility:** Direct, zero-friction task management designed for harsh outdoor sunlight or high-density indoor control consoles.
- **Systematic Precision:** Numerical clarity is paramount; metric tracking (TDS, flow rates, delivery counts) commands instant cognitive capture.

### Target Audience
- Plant managers tracking reverse osmosis membranes, pressure levels, and sanitization cycles.
- Logistics and camper route operators managing empty vs. filled 20L camper inventories and cash collections.
- Enterprise clients and commercial purchasers evaluating water purity compliance and batch deliveries.

## Colors

The palette establishes an immediate sensation of purified water, technical instrumentation, and verified safety. 

- **Primary (`#0284C7` / `#0EA5E9`):** Crystalline Azure represents pure flowing water, active states, and focal UI actions.
- **Secondary (`#0C4A6E` / Deep Aquatic Navy):** Grounding naval tones signify structural stability, headers, heavy industrial equipment status, and structural framing.
- **Tertiary (`#10B981` / Emerald Mint):** Clinical green indicates pristine TDS readings (<50 ppm), operating membrane health, optimal yield, and positive revenue balance.
- **Neutral (`#0F172A` / `#F8FAFC`):** Deep abyssal slate provides deep-contrast typography on laboratory-clean `#FFFFFF` and chilled ice-white `#F0F9FF` background surfaces.

### Functional Roles
- **Surface Cleanliness:** `#FFFFFF` canvas with `#F0F9FF` panel tinting for fluid containers and operational groupings.
- **Telemetry Indicators:** Warning states utilize Amber (`#F59E0B`) for filter servicing, while Danger Red (`#EF4444`) isolates contamination threats, high TDS (>150 ppm), and overdue delivery balances.

## Typography

Typography balances engineered technicality with swift operational scanning.

- **Headlines (`Space Grotesk`):** Structural, geometric, and modern. Conveys engineering confidence on operational titles and enterprise summaries.
- **Body Text (`Manrope`):** Warm, geometric, and exceptionally balanced. Eliminates reading fatigue on inventory sheets, route tables, and customer ledgers.
- **Metrics & Data Labels (`JetBrains Mono`):** Monospaced precision prevents horizontal optical jitter during live real-time telemetry refreshes (e.g., oscillating pressure gauges, dynamic 1000 LPH flow readouts, batch numbers, and rupee cash figures).

## Layout & Spacing

The system implements a rigid 12-column fluid grid system across desktop (`1280px+`), an 8-column layout on tablet (`768px - 1279px`), and a 4-column layout on mobile (`<768px`).

- **Dashboard Layout:** Utilizes a persistent left-rail operational utility bar (64px collapsed, 240px expanded) paired with modular card sections.
- **Data Densities:** Metric tables and flow monitors adhere to compact `0.5rem` row gaps to maintain high informational bandwidth, allowing operators to monitor plant metrics, vehicle dispatch status, and RO membrane readings within a single viewport.
- **Margins & Safe Zones:** Outer canvas margins compress to `1rem` on mobile delivery runs to maximize usable screen estate on handheld rugged devices.

## Elevation & Depth

Visual hierarchy leverages crisp aquatic tonal layers, ultra-soft hydrostatic drop shadows, and delicate cold-tone borders.

- **Flat Layering:** Primary surface is `#F8FAFC`. Active cards sit on pure `#FFFFFF` bounded by a 1px border of `#E2E8F0` or `#BAE6FD` (sky tint).
- **Hydrostatic Depth (Cards & Overlays):** Elevation is featherweight and diffused, tinted with deep navy: `0 4px 20px -2px rgba(12, 74, 110, 0.06)`. This avoids muddy dark shadows and creates an airy, clean-room atmospheric aesthetic.
- **Raised Critical Panels (Active Telemetry/Alerts):** Higher-priority dialogs and sliding route drawers use `0 12px 32px -4px rgba(15, 23, 42, 0.12)` accompanied by high-contrast `#0C4A6E` accents.

## Shapes

The design system maintains a **Soft (`1`)** shape language. Industrial equipment interfaces require structured, crisp containment rather than playfulness. 

- Base UI components (buttons, input boxes, metric cards) feature a sharp `0.25rem` (4px) curvature.
- Containers, modal sheets, and operational panels leverage `rounded-lg` (`0.5rem` / 8px).
- Pill shapes are reserved exclusively for operational tags (e.g., camper return status badges, TDS qualitative tags).

## Components

### Buttons & Interactive Controls
- **Primary Utility Action:** Solid `#0284C7` with `#FFFFFF` text, 4px border radius, transitioning to `#0369A1` on hover. Accompanied by a crisp, single-pixel inner highlight.
- **Secondary Plant Action:** `#F0F9FF` background with `#0C4A6E` text and a subtle `#BAE6FD` border.
- **Destructive/Emergency:** Solid `#EF4444` for emergency valve closures or route aborts.

### Metric Tiles & Sensor Displays
- Enclosed modules featuring a top micro-label in `JetBrains Mono` (`label-caps`), an oversized numerical value in `metric-display`, and a secondary trend delta badge.
- When metrics (e.g., TDS) remain within pure drinking parameters (30–80 ppm), tiles inherit a 1px left accent bar in Emerald Green (`#10B981`).

### Camper Tracking & Inventory Chips
- Dual-indicator status chips:
  - **Camper Dispatched:** `#EFF6FF` with text `#1D4ED8` and azure indicator dot.
  - **Returned Empty:** `#F1F5F9` with text `#475569` and slate indicator dot.
  - **Sterilized & Refilled:** `#ECFDF5` with text `#047857` and emerald indicator dot.

### Inputs & Editable Pricing Fields
- Inputs feature crisp 1px borders in `#CBD5E1`. 
- On focus, trigger a distinct 2px ring in `#0EA5E9` with 0px outline gap, reinforcing technical accuracy.
- Numeric currency fields prefix an immutable currency tag (`₹`) styled in monospaced font.

### Cards & Route Tables
- High-density tabular layouts with alternating subtle fills (`#FFFFFF` to `#F8FAFC`).
- Row borders are thin `1px solid #F1F5F9` with hover highlights in `#F0F9FF`.