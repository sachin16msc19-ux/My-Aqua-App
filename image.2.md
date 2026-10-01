---
name: Obsidian Orbit
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#c3c0ff'
  on-secondary: '#1d00a5'
  secondary-container: '#3626ce'
  on-secondary-container: '#b3b1ff'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#009eb9'
  on-tertiary-container: '#002f38'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#e2dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#0f0069'
  on-secondary-fixed-variant: '#3323cc'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.011em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.006em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-inline:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: '0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system targets high-velocity software engineering leaders, technical product managers, and distributed teams who operate in complex digital environments. The visual tone is precise, cerebral, and authoritative—engineered to feel like high-grade mission control software rather than a generic productivity tool.

The style merges **Modern Technical Minimalism** with **Atmospheric Layering**:
- Deep slate canvases with hairline structure instead of heavy cards.
- Highly purposeful neon-tinted indigo accents that communicate state and focus without visual noise.
- Crisp typographic tension: structural, expressive geometric numbers and headers grounded by an ultra-readable utilitarian body font.
- Tactile, low-glow indicators mimicking modern code environments, hardware status consoles, and specialized desktop developer utilities.

## Colors

The palette is engineered specifically for dark-mode productivity, reducing visual fatigue while preserving strict semantic distinction and contrast ratios meeting WCAG AAA for text and AA for active UI components.

### Core Roles
- **Base Canvas (`#090D16` / `#0F172A`)**: Rich, carbon-tinted deep slate foundations. Surfaces rise in luminosity as they step forward in z-index.
- **Primary Indigo (`#6366F1`) & Active Indigo (`#4F46E5`)**: Used selectively for focal calls-to-action, active sprint markers, drag targets, and primary keyboard focus rings.
- **Data Accent / Tertiary Cyan (`#06B6D4`)**: Reserved for live connectivity states, automated agent badges, git branch pins, and real-time multiplayer telemetry.
- **Structural Lines (`#1E293B`, `#334155` at 60% opacity)**: Hairline boundaries separating data grids, split panes, and navigation hierarchies.

### Hierarchy & Tint Rules
- Background surfaces utilize 4 primary layers: `surface-0` (`#090D16`), `surface-1` (`#0F172A`), `surface-2` (`#1E293B`), and `surface-3` (`#243047`).
- Text uses stark high-contrast scaling: `#F8FAFC` for high-emphasis headlines and values, `#94A3B8` for supportive meta-information, and `#64748B` strictly for inactive states and shortcut keys.

## Typography

The type system creates contrast between technical exactitude and sustained reading comfort:
- **Headlines, Metas, and Metrics (Space Grotesk)**: Renders issue counts, milestone tags, velocity counters, and section titles with a confident, modern engineering character.
- **Context, Specs, and Long-form (Inter)**: Handles complex task descriptions, comment threads, audit logs, and settings with neutral legibility and optimal kerning at compact sizes.
- **Tabular Alignment**: Enable `font-feature-settings: "tnum" 1` for all instances displaying cycle times, ticket IDs, sprints, and numeric metrics.

## Layout & Spacing

The layout is built for high information density desktop workstations, multi-pane split workflows, and fluid command-center interfaces.

### Grid & Density
- **Application Shell**: Employs a multi-column pane model (Collapsible Left Rail: `240px`, Workspace Nav: `280px`, Flexible Work Canvas: `minmax(640px, 1fr)`, Context Panel / Drawer: `380px`).
- **Data Workspaces (Kanban / Table / Gantt)**: Full-width fluid responsive container with horizontal scrolling lanes and anchored sticky headers.
- **Responsive Adaptations**:
  - **Desktop (`>= 1280px`)**: Multi-column persistent layout; simultaneous board and task detail viewing.
  - **Tablet (`768px - 1279px`)**: Secondary navigation transforms into an off-canvas drawer; tasks open in stacked flyout modals.
  - **Mobile (`< 768px`)**: Single-column vertical reflow; boards collapse to swipeable tabs; bottom sheet navigation for ticket manipulation.

## Elevation & Depth

Visual hierarchy uses a dark-mode tonal architecture supported by crisp low-contrast borders and subtle luminescence, avoiding muddy black drop shadows.

### Depth Hierarchy
1. **Canvas Level (Elevation 0)**: Background `#090D16`. Flat baseline for primary window framing and backdrop workspace.
2. **Structural Panels (Elevation 1)**: Fill `#0F172A`, framed with `1px solid rgba(51, 65, 85, 0.45)`. Used for side navigation rails, static lists, and board lane tracks.
3. **Interactive Tiles & Cards (Elevation 2)**: Fill `#1E293B` at 70% opacity, bordered by `1px solid rgba(51, 65, 85, 0.70)`. Card hover state introduces an inner highlight line: `inset 0 1px 0 0 rgba(255, 255, 255, 0.08)`.
4. **Floating Overlays & Modals (Elevation 3)**: Fill `#1E293B`, framed with `1px solid #334155`, complemented by a directional ambient shadow: `0 20px 40px -15px rgba(0, 0, 0, 0.75)`.
5. **Focused / Active Glow**: Elements currently engaged or dragged utilize an outer halo: `0 0 0 1px #6366F1, 0 8px 24px -4px rgba(99, 102, 241, 0.25)`.

## Shapes

The geometric framework balances technical precision with modern ergonomics:
- **Base Components (Inputs, Small Buttons, Chips)**: `rounded` (8px / `0.5rem`). Clean, compact, fits high-density data tables without feeling sharp.
- **Interactive Cards & Containers**: `rounded-lg` (12px / `0.75rem` to `1rem`). Provides clear separation between stacked cards within Kanban boards and milestone tracks.
- **Command Palettes & Primary Modals**: `rounded-xl` (16px / `1.5rem`). Softens major UI transitions and focus takeovers.
- **Status Indicators & Avatars**: Fully circular (`rounded-full`) to contrast against rectangular sprint and task blocks.

## Components

### Buttons
- **Primary**: Background `#6366F1`, text `#FFFFFF`, font `Space Grotesk` (semi-bold, 13px), border `1px solid rgba(255, 255, 255, 0.15)`, top inner shadow `inset 0 1px 0 rgba(255, 255, 255, 0.2)`. On hover: `#4F46E5` with ambient glow `0 4px 14px rgba(79, 70, 229, 0.4)`.
- **Secondary / Ghost**: Background `rgba(30, 41, 59, 0.6)`, text `#F8FAFC`, border `1px solid rgba(51, 65, 85, 0.6)`. Hover: Background `#1E293B`, border-color `#6366F1`.
- **Destructive**: Background `rgba(239, 68, 68, 0.1)`, text `#F87171`, border `1px solid rgba(239, 68, 68, 0.25)`. Hover: Background `#EF4444`, text `#FFFFFF`.

### Task Cards & Board Items
- **Container**: Fill `#0F172A` with `1px solid #1E293B` baseline border.
- **Header**: Ticket key (e.g., `DEV-402`) in `Space Grotesk` 11px muted gray-400; Priority indicator (4-tier icon with subtle color accents: Critical `#EF4444`, High `#F59E0B`, Medium `#6366F1`, Low `#64748B`).
- **Interactive States**: On cursor hover, border transitions smoothly to `rgba(99, 102, 241, 0.5)` with a `1px` subtle translation on the y-axis. Active dragging triggers a 3-degree skew and `Elevation 3` shadow.

### Inputs & Command Palette
- **Text Inputs**: Fill `#090D16`, text `#F8FAFC`, placeholder `#64748B`, border `1px solid #1E293B`, radius `8px`. Focus: Border `#6366F1`, ring `2px rgba(99, 102, 241, 0.2)`.
- **Command Palette (`Cmd+K`)**: Floating backdrop modal with `backdrop-filter: blur(16px)`, background `rgba(15, 23, 42, 0.85)`, input integrated with a leading cyan search glyph, quick-filter key-hints rendered in monospaced tags (`#334155` background, `#94A3B8` text).

### Chips & Status Tags
- **Sprint / Status Chips**: Height `22px`, padding `0 8px`, radius `6px`, font `Space Grotesk` 11px.
  - *In Progress*: `#6366F1` text with `rgba(99, 102, 241, 0.12)` fill and `rgba(99, 102, 241, 0.3)` border.
  - *Live / Complete*: `#06B6D4` text with `rgba(6, 182, 212, 0.12)` fill and `rgba(6, 182, 212, 0.3)` border.

### Checkboxes & Selectors
- **Checkbox**: Size `16px x 16px`, radius `4px`, background `#090D16`, border `1.5px solid #334155`. Checked state: Background `#6366F1`, border `#6366F1` displaying a crisp white micro checkmark.
- **Custom Milestone Radios**: Concentric ring transition with immediate feedback and `#6366F1` inner pip expansion.

### Telemetry & Developer Specifics
- **Git Branch Pills**: Minimal monospace tags displaying truncated commit SHAs and branch branches with automated conflict alert icons.
- **Active Member Presence**: Overlapping `28px` circular avatars bounded by `#0F172A` borders, with real-time green/cyan presence dots on the bottom-right quadrant.