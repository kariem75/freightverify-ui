---
name: Logistics Payload Verification IDE
colors:
  surface: '#081425'
  surface-dim: '#081425'
  surface-bright: '#2f3a4c'
  surface-container-lowest: '#040e1f'
  surface-container-low: '#111c2d'
  surface-container: '#152031'
  surface-container-high: '#1f2a3c'
  surface-container-highest: '#2a3548'
  on-surface: '#d8e3fb'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#d8e3fb'
  inverse-on-surface: '#263143'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffb3ad'
  on-tertiary: '#68000a'
  tertiary-container: '#ff5451'
  on-tertiary-container: '#5c0008'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3ad'
  on-tertiary-fixed: '#410004'
  on-tertiary-fixed-variant: '#930013'
  background: '#081425'
  on-background: '#d8e3fb'
  surface-variant: '#2a3548'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  code-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
  label-xs:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.06em
spacing:
  gutter: 1px
  margin: 0rem
  space-xs: 0.25rem
  space-sm: 0.375rem
  space-md: 0.5rem
  space-lg: 0.75rem
  space-xl: 1rem
---

## Brand & Style
The design system targets logistics automation engineers, compliance officers, and platform developers verifying complex multi-modal shipping documentation, bills of lading, customs declarations, and cryptographic manifests. 

The aesthetic is grounded in **Technical Brutalism meets Modern Systems Engineering**: razor-sharp geometry, terminal-grade structural density, high data efficiency, and low-latency readability. The emotional signature is methodical, infallible, and operational—evoking absolute confidence and precision under heavy operational velocity. Visual noise is stripped away in favor of explicit division lines, mechanical hierarchies, and monospaced parity for scannable parsing.

## Colors
The palette is engineered for prolonged operational focus in zero/low-ambient environments, eliminating eye strain while upholding high contrast across data boundaries.

- **Canvas & Structural Paneling**: The root backdrop is `#0F172A` (Deep Navy) for global frame gutters and sidebars, overlaid by `#1E293B` (Charcoal Slate) for primary editors, panels, and document inspector viewports.
- **Borders & Dividers**: Fixed at `#334155` (Muted Slate Wireframe) with zero diffusion. Structural borders maintain a constant 1px hairline thickness.
- **Accents & Signals**:
  - **Primary Action / Focus**: `#6366F1` (Indigo Neon) for active parser focus, cursor indicators, active tree selections, and diff highlights.
  - **Success / Validated**: `#10B981` (Emerald) for cryptographic integrity matches, schema validations, and confirmed customs signatures.
  - **Alert / Schema Fault**: `#EF4444` (Crimson) for parser mismatch, missing payload nodes, and failed manifest verifications.
- **Typography & Meta**: Core data foreground is `#F8FAFC` (Pure Titanium) for active code/keys, `#94A3B8` (Cool Muted Slate) for schema taxonomy, line numbers, and secondary parameters, and `#64748B` for inactive placeholders.

## Typography
The system enforces strict dual-font discipline:
1. **Geist**: Handles structural operational headers, tooltips, dialogs, and breadcrumb navigation. It provides crisp neutral legibility without typographic distraction.
2. **JetBrains Mono**: Assigned to all logistics payloads (JSON, YAML, EDIFACT), tracking hashes, cryptographic keys, tabular metrics, metadata badges, and coordinate points. Strict tabular alignment ensures decimal figures and hex strings remain scan-aligned across horizontal and vertical inspection matrices.

## Layout & Spacing
The layout operates as a split-pane, high-density IDE. Rather than broad negative space, screen real estate is maximized for high data density through strict border-divided compartments.

- **Global Shell**: Full-bleed edge-to-edge canvas with `0rem` outer margins. Structural panels (Navigation Sidebar, Verification Tree, Main Document Editor, Validation Output Console) are divided by monolithic `1px` hairlines (`#334155`).
- **Internal Paneling**: Interior layouts use compact padding steps. `space-xs` (4px) and `space-sm` (6px) govern interactive element insets and icon-label pairs. `space-md` (8px) separates structural sub-panes.
- **Responsive Adaptation**:
  - **Desktop (1280px+)**: 4-column workbench: Collapsible schema rail (240px), document AST tree (280px), verification code editor (flex-grow), inspector telemetry rail (320px).
  - **Tablet / Small Displays (<1280px)**: Collapses inspector and schema rails into stacked sliding drawers, maintaining an uncompromised dual-pane diff comparison view.

## Elevation & Depth
This design system rejects ambient blur and soft drop shadows entirely. Depth is structural, mechanical, and binary.

- **Flat Wireframe Z-Index**: All hierarchy is achieved via surface tonal shifts and explicit 1px `#334155` borders. Base layers reside on `#0F172A`, active panels step up to `#1E293B`, and elevated transient states (command palette, context dropdowns, inspector overlays) rest on `#1E293B` surrounded by a mandatory 1px `#6366F1` stroke.
- **Focus Rings**: Strict 1px inset or flush outline in primary `#6366F1` without blur radius.
- **Modal Backdrops**: Heavy solid `#0B0F19` at 85% opacity with no blur filter, keeping GPU overhead non-existent and system focus absolute.

## Shapes
The shape language is strictly **Sharp (0px radius)**. Every card, button, tab, payload block, modal, and input field uses unrounded 90-degree corners. 

This absolute square discipline reinforces the industrial, non-decorative CAD/IDE utility of the application, maximizes every pixel of render space on dense terminal panels, and echoes hardware telemetry instrumentation.

## Components

### Buttons
- **Primary**: Solid `#6366F1` background, `#FFFFFF` text (`label-md`), 0px corners, height 28px, horizontal padding `space-md`. Active: `#4F46E5`.
- **Secondary / Ghost**: Transparent fill, 1px border `#334155`, `#94A3B8` text. Hover: `#1E293B` background with `#F8FAFC` text and border `#64748B`.
- **Destructive**: 1px border `#EF4444`, transparent fill, `#EF4444` text. Hover: `#EF4444` background, `#FFFFFF` text.

### Inputs & Key-Value Fields
- **Terminal Inputs**: Fixed height 28px, background `#0F172A`, 1px border `#334155`, font `code-sm`. Active focus switches border to `#6366F1` with an active monospaced block caret.
- **Validation Key Fields**: Monospaced labels `#94A3B8` left-aligned with a continuous `#334155` dot-leader connecting to the right-aligned value `#F8FAFC`.

### Chips & Badges
- Height 18px, 0px border radius, font `label-xs`, all-caps tracking.
- **Success (Verified)**: `#10B981` at 10% opacity, border 1px solid `#10B981`, text `#10B981`.
- **Error (Schema Fail)**: `#EF4444` at 10% opacity, border 1px solid `#EF4444`, text `#EF4444`.
- **Pending/Manifest Hash**: `#6366F1` at 10% opacity, border 1px solid `#6366F1`, text `#6366F1`.

### Data Panels & Cards
- Replaced by rigid border-bound inspection tiles. Zero drop-shadow. Background `#1E293B`, continuous 1px border `#334155`. Header bar fixed at 24px height, background `#0F172A`, bottom border `#334155`, text `label-xs` in uppercase.

### Verification Lists & Tree Viewers
- Row height fixed at 22px with vertical guide lines connecting nested JSON/EDIFACT nodes. Hover row fills with `#1E293B` at full width. Active row exhibits a 2px left border strip in `#6366F1`.
- Mismatched line items alternate with a full-row background tint of `#EF4444` at 15% opacity with an inline crimson crosshair marker.

### Checkboxes & Radios
- Sharp 12x12px squares. 1px border `#334155`, background `#0F172A`. Checked: Solid `#6366F1` with an interior sharp square core or check glyph rendered in `#FFFFFF`.