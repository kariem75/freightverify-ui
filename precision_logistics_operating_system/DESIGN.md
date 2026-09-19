---
name: Precision Logistics Operating System
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
  on-surface-variant: '#434655'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#ab0b1c'
  on-tertiary: '#ffffff'
  tertiary-container: '#cf2c30'
  on-tertiary-container: '#ffecea'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3ad'
  on-tertiary-fixed: '#410004'
  on-tertiary-fixed-variant: '#930013'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  body-xs:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  data-mono-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
  data-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-dense: 0.5rem
  margin: 1.5rem
  margin-mobile: 0.75rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system serves high-velocity enterprise freight operations, trade compliance teams, and supply chain analysts. The brand aesthetic merges industrial precision with calm, analytical software utility. The visual tone communicates certainty, immediate error identification, and verified ground-truth reliability.

The design movement is **Corporate Precision & High-Density Utility**. It avoids decorative frivolity, consumer-grade oversized spacing, or distracting dramatic elevations in favor of structured data layouts, razor-sharp outlines, micro-feedback states, and strict operational legibility. Visual priority is dictated strictly by status semantics: primary blue anchors systematic interaction, while verification emerald, discrepancy crimson, and pending amber guide the operator's eye directly to actionable points of friction across bills of lading, manifests, and shipping ledgers.

## Colors

The color palette is architected around high contrast, operational clarity, and strict semantic governance.

### Core Canvas & Surfaces
- **Header & Command Surfaces:** Deep Navy Slate (`#0F172A`) grounds the top-level persistent navigation, establishing authority and framing the analytical viewport.
- **Root Background:** Slate-50 (`#F8FAFC`) provides a low-strain, glare-free working canvas for extended desk shifts.
- **Card & Cell Surfaces:** Pure White (`#FFFFFF`) forms the elevated operational layer, enclosed by micro-borders in Slate-200 (`#E2E8F0`) to ensure distinct card isolation.
- **Muted Surface Fill:** Slate-100 (`#F1F5F9`) serves as the resting state for table header bands, inactive inputs, and segmented controls.

### Functional & Semantic Accents
- **Primary Action (Enterprise Blue):** `#2563EB` handles active selections, primary verification triggers, focused tab indicators, and interactive links. Hover states step down to `#1D4ED8`.
- **Ground Truth & Matched (Emerald Green):** `#10B981` signals verified records, confirmed Bill of Lading (BL) data matches, and customs clearances. Tint surfaces use `#ECFDF5` with `#A7F3D0` borders.
- **Discrepancy & Critical Alert (Crimson Red):** `#EF4444` flags mismatched manifests, overweight violations, and missing customs paperwork. Surface indicators utilize `#FEF2F2` paired with `#FECACA` borders.
- **Review Required & In-Transit (Amber Warning):** `#F59E0B` identifies fuzzy matches, OCR parsing warnings, and pending vessel departures. Muted backings leverage `#FFFBEB` with `#FDE68A` borders.

### Text Contrast
- Primary copy uses Slate-900 (`#0F172A`), secondary attributes utilize Slate-600 (`#475569`), and placeholder/disabled text rests at Slate-400 (`#94A3B8`).

## Typography

The typographic scale enforces readability in information-dense workflows. 

- **Primary Interface (Inter):** Applied across global UI, navigation controls, status dialogues, and analytical readouts. All numeric data rendered in Inter must apply the OpenType feature `font-feature-settings: 'tnum' 1, 'cv05' 1` to guarantee monospaced tabular alignment across scrolling data tables.
- **Logistics References & Code Identifiers (JetBrains Mono):** Dedicated to machine-readable attributes including Container IDs (e.g., `MSKU0928311`), Master Bill of Lading (MBL) hashes, HS tariff codes, customs declaration stamps, and micro audit trails.
- **Header Case & Caps:** Labels in `label-sm` and `label-md` employ uppercase treatment with relaxed letter-spacing (`0.03em` - `0.04em`) to distinctly classify table columns and metadata section titles without visually competing with data values.

## Layout & Spacing

The layout is built for complex, side-by-side data reconciliation (e.g., comparing extracted OCR document text against ERP database records).

### Grid System & Shell Structure
- **Global Architecture:** Fixed 56px Dark Slate header, an optional 64px collapsible left-hand utility icon rail, and a fluid-width viewport main body.
- **Document Split-View:** Verification views split into an asymmetric 12-column grid: 5 columns dedicated to the native document preview/OCR inspector and 7 columns for interactive validation cards and discrepancy resolution grids.
- **Gutter Strategy:** Default grid gutter rests at `1rem` (16px), but contracts to `gutter-dense` (8px) within comparative data grids and key-value inspector sidebars to minimize scanning fatigue.

### Responsive Reflow Rules
- **Desktop (>= 1280px):** High-density multi-pane inspection active. Tables render full field sets with inline verification actions.
- **Tablet / Laptop (1024px - 1279px):** Split-view shifts to a toggled tabbed layout between document viewer and verification fields. Secondary data table columns drop into an expandable drawer.
- **Mobile (< 1024px):** Linear stacked cards replace tabular tables. Critical alerts and pass/fail summary banners move to a sticky bottom control bar.

## Elevation & Depth

This system avoids expressive drop shadows in favor of low-contrast borders and surgical surface elevation.

- **Level 0 (Canvas Base):** Slate-50 (`#F8FAFC`), entirely flat.
- **Level 1 (Data Cards & Table Blocks):** White (`#FFFFFF`) surface framed by a 1px solid border in Slate-200 (`#E2E8F0`). No shadow is cast; surface differentiation is achieved entirely through line contrast against the Slate-50 backdrop.
- **Level 2 (Hovered Rows & Active Table Focus):** Background shifts to Slate-50/50, retaining the 1px Slate-200 boundary, accented with a 2px vertical indicator bar in Primary Blue or semantic status color along the row's leading edge.
- **Level 3 (Flyout Drawers, Context Popovers, & Dropdowns):** White surface with a 1px Slate-200 boundary, complemented by a crisp, structured ambient shadow: `0 4px 12px -2px rgba(15, 23, 42, 0.08), 0 2px 6px -1px rgba(15, 23, 42, 0.04)`.
- **Level 4 (Modal Verification Confirmations):** White surface with a sharp perimeter shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`. Backdrop is tinted with Slate-900 at 60% opacity (`rgba(15, 23, 42, 0.60)`) featuring a subtle 2px backdrop blur.

## Shapes

The design system maintains a **Soft (Level 1)** geometric silhouette. Tight, disciplined corner radiuses preserve the professional, technical utility required for enterprise logistics tools.

- **Base Components (Inputs, Buttons, Badges):** `4px` (`0.25rem`) border radius. This subtle radius softens hard corners while maintaining structural alignment in packed data grids.
- **Containers & Data Tables:** `6px` (`0.375rem`) to `8px` (`0.5rem`) on outer card boundaries, ensuring panels remain distinct without wasting interior corner padding.
- **Pill Exceptions:** Rounded pills (`9999px`) are strictly forbidden for buttons or cards; they are reserved solely for high-visibility micro status chips (e.g., "VERIFIED", "FLAGGED") to provide immediate shape contrast against squared rectangular input matrices.

## Components

### Buttons
- **Primary:** Solid `#2563EB` fill, white text, 4px radius, 32px height for high density (36px standard). Hover: `#1D4ED8`. Active: `#1E40AF`. Focus: 2px offset ring in `#93C5FD`.
- **Secondary / Outline:** White surface, 1px solid Slate-300 (`#CBD5E1`), Slate-700 (`#334155`) text. Hover: `#F8FAFC` background with Slate-400 border.
- **Semantic Destructive:** White surface with `#EF4444` border and text. Hover: `#FEF2F2` background.
- **Compact Table Actions:** 24px icon-only ghost buttons with 2px padding, activating a Slate-100 bounding square on hover.

### Badges & Status Chips
- **Format:** Upper-case, tracking `0.04em`, 20px total height, font size 11px, weight 600, 1px border.
- **Verified:** Background `#ECFDF5`, text `#065F46`, border `#A7F3D0`. Includes a 6px solid `#10B981` leading dot indicator.
- **Discrepancy:** Background `#FEF2F2`, text `#991B1B`, border `#FECACA`. Includes an alert warning glyph.
- **Pending / In-Review:** Background `#FFFBEB`, text `#92400E`, border `#FDE68A`.
- **Neutral / Draft:** Background `#F1F5F9`, text `#475569`, border `#CBD5E1`.

### Data Comparison & Table Rows
- **Table Headers:** Slate-100 (`#F1F5F9`) background, 32px height, 1px bottom border in Slate-200 (`#E2E8F0`), labels rendered in Slate-600 JetBrains Mono uppercase.
- **Data Rows:** Alternating hover state (`#F8FAFC`), 36px standard cell height. Active row border left: 3px solid `#2563EB`.
- **Diff Matrix (Source vs. Ground Truth):** Two-column nested cells. Source data displaying errors features a red strikethrough background (`#FEE2E2` text `#991B1B`), positioned directly adjacent to the verified correction in green (`#DCFCE7` text `#166534`).

### Input Fields & Controls
- **Standard Input:** 32px height, Slate-50 fill with 1px Slate-300 border. Focus: White fill, `#2563EB` border, zero outer glow, accompanied by a 1px inner stroke.
- **Discrepancy State:** Solid 1px `#EF4444` border with `#FEF2F2` background tint; displays a trailing alert trigger icon linking to the raw OCR source snippet.
- **Checkboxes:** 14px squared boxes with 2px radius. Unchecked: 1px Slate-300 border on white. Checked: `#2563EB` fill with a crisp white checkmark vector.

### Document Inspector Panel
- Integrated split-view container featuring a pinned zoom/rotate header toolbar in Slate-900, housing the original scanned PDF/TIFF. Bounding boxes are drawn directly over document fields: Emerald for automated extractions matching ground truth, Red for high-confidence OCR conflicts.