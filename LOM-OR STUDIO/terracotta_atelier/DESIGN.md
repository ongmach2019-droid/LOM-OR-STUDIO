---
name: Terracotta Atelier
colors:
  surface: '#fcf8ff'
  surface-dim: '#dbd8e7'
  surface-bright: '#fcf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2ff'
  surface-container: '#efecfb'
  surface-container-high: '#e9e6f5'
  surface-container-highest: '#e3e1f0'
  on-surface: '#1a1b25'
  on-surface-variant: '#464557'
  inverse-surface: '#2f2f3a'
  inverse-on-surface: '#f2effe'
  outline: '#777589'
  outline-variant: '#c7c4da'
  surface-tint: '#4537ff'
  primary: '#2700d9'
  on-primary: '#ffffff'
  primary-container: '#3f2dfe'
  on-primary-container: '#ceccff'
  inverse-primary: '#c2c1ff'
  secondary: '#5553b1'
  on-secondary: '#ffffff'
  secondary-container: '#9d9bff'
  on-secondary-container: '#312d8c'
  tertiary: '#801c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#aa2800'
  on-tertiary-container: '#ffc3b4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c2c1ff'
  on-primary-fixed: '#0d006a'
  on-primary-fixed-variant: '#2a00e7'
  secondary-fixed: '#e2dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#0e006a'
  on-secondary-fixed-variant: '#3d3a98'
  tertiary-fixed: '#ffdbd2'
  tertiary-fixed-dim: '#ffb4a1'
  on-tertiary-fixed: '#3c0800'
  on-tertiary-fixed-variant: '#891e00'
  background: '#fcf8ff'
  on-background: '#1a1b25'
  surface-variant: '#e3e1f0'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system is tailored for high-end architectural studios, interior design practices, and structural engineering firms operating in Southeast Asia and internationally. The brand personality blends organic craftsmanship with structural discipline: architectural precision, materiality, grounded luxury, and deliberate restraint.

The design movement combines **Minimalism** with an **Architectural Warmth** aesthetic. It moves away from cold, generic enterprise software by incorporating tactile, mineral-inspired surfaces—limestone canvas, electric indigo, raw clay, and deep smoked umber. The interface conveys calm mastery over complex operations (budgets, schedules, pipeline stages, client approvals, and project milestones), elevating utilitarian workflows into an inspiring, studio-grade workspace.

## Colors

The palette is rooted in modern digital precision paired with structural timber and stone:

- **Primary (`#3F2DFE`)**: A rich, vibrant electric indigo used for primary actions, active navigation states, high-priority stage indicators, and critical progress bars.
- **Secondary (`#6E6CCC`)**: Soft slate indigo used for supportive interactive elements, secondary tags, structural headers, and hover accents.
- **Tertiary (`#AD2900`)**: Deep burnt orange utilized for warnings, impending deadline notifications, and pending financial reconciliations.
- **Neutral Base & Canvas**: The canvas employs soft warm plaster (`#FAF7F2` and `#F5EFEB`), transitioning to pure white (`#FFFFFF`) on card surfaces to maintain optimal data contrast. Borders utilize a gentle sandstone tone (`#E8DFD8`).
- **Typography & Ink (`#777683` / `#4A3B32`)**: High-contrast, balanced neutral ink ensures high readability without the harsh synthetic contrast of pure pitch black.

## Typography

The type system prioritizes precision and bilingual harmony between English and Khmer scripts. In runtime environments with Khmer localization, clean sans-serif Khmer typefaces such as **Kantumruy Pro** or **Battambang** cascade seamlessly alongside **Inter**.

- **Headline Roles**: Bold, architectural weights anchor sections and primary metrics. Letter spacing is slightly tightened on larger display tiers for dense, professional balance.
- **Data & Tables**: Numerical values, currencies, IDs, and tabular metadata leverage proportional tabular figures (`tnum`) for straight vertical alignment down complex pipeline ledgers.
- **Labels & Micro-copy**: Distinct medium-weight tracking prevents legibility degradation in smaller UI pills, status badges, and module tabs.

## Layout & Spacing

The layout is built around a flexible, structured enterprise grid with dedicated responsive behaviors:

- **Desktop (12 Columns)**: Max container width pinned to 1440px or fluid edge-to-edge with minimum `1.5rem` margins. Gutters are locked at `1rem` for metric card bands and `1.5rem` for major layout split-views (e.g., project details pane beside documentation list).
- **Metric Grids**: The top performance ribbon distributes key operational counters (Leads, Active Pipelines, Conversion Rates, Valuation) in an auto-fit 6 to 8-column compact row with tight internal padding (`space-sm` to `space-md`).
- **Data Tables & Pipeline Views**: Fixed top search/filter utility bar with standardized `0.5rem` gap arrays, flowing directly into multi-column tabular cards.
- **Mobile/Tablet Breakpoints**: Under 768px, navigation tabs transform into a horizontally scrollable strip; multi-column metric arrays collapse into 2-column or 4-column balanced modules.

## Elevation & Depth

This design system avoids heavy drop shadows in favor of **Tonal Layering** and **Subtle Warm Outlines**, mirroring physical architectural sheets:

- **Canvas Level (Ground)**: Textured warm clay wash (`#FAF7F2`), absorbing ambient eye strain over long operational hours.
- **Card Tier 1 (Structure)**: Pure white (`#FFFFFF`) with a delicate 1px warm sand border (`#E8DFD8`). Cards do not float aggressively; instead, they sit cleanly on the canvas plane.
- **Interactive Modals & Menus (Floating)**: Soft ambient tint shadow: `0 8px 24px -4px rgba(45, 36, 30, 0.08)`, combined with a 1px border (`#E8DFD8`).
- **Table Headers & Active Tiers**: Soft indigo/tan wash separates headers from interactive rows without requiring heavy dividers.

## Shapes

The shape system adopts a **Soft (`1`)** approach (base radius of `4px` / `0.25rem`, scaling to `8px` / `0.5rem` on cards and containers).

- **Philosophy**: Pure brutalist sharp corners feel overly clinical, while large pill shapes erode the structural, rigorous impression expected of an architectural firm. Subtly rounded geometry reflects honed stone, milled joinery, and clean drafting corners.
- **Pills**: Reserved strictly for micro-status indicators (e.g., `Won`, `Open`, deadline counters) where complete pill radii maximize visual distinctiveness.

## Components

### Buttons & Actions
- **Primary Button**: Solid electric indigo fill (`#3F2DFE`), white text, crisp 4px radius, `8px 16px` padding. Active state darkens to `#6E6CCC`.
- **Secondary / Action Button**: Crisp white background, 1px border (`#E8DFD8`), text `#777683`. Subtle indigo tint on hover.
- **Utility / Export Buttons**: Compact footprint, muted neutral icons (CSV, Excel) paired with clean label typography.

### Navigation Strip (Workspace Tabs)
- Encapsulated rounded tab items sitting directly below the global studio brand bar.
- **Active Tab**: Filled electric indigo (`#3F2DFE`), white text, subtle corner rounding.
- **Inactive Tab**: Outlined white card shape with muted sand border (`#E8DFD8`) and neutral text.

### Metric & KPI Cards
- Crisp white background (`#FFFFFF`), border `1px solid #E8DFD8`, soft 8px radius.
- Top label: Muted, compact neutral typography (`body-sm`).
- Value indicator: Prominent, high-contrast bold counter (`headline-lg`), tinted indigo when alert thresholds trigger (e.g., overdue tasks).

### Data Tables
- Header row wrapped in warm limestone tint with uppercase or semi-bold labels.
- Alternating subtle row separators (`1px solid #F3ECE6`). Hover transitions to an ultra-light indigo tint.
- Action columns feature micro-ghost buttons with 1px hairline borders for editing and item deletion.

### Pipeline Progress Bars & Badges
- Thick 4px to 6px linear bars filled with solid mineral indigo (`#6E6CCC`), set against soft neutral sand tracks.
- Stage Pills: Soft muted pastel backgrounds accompanied by deep chromatic text.