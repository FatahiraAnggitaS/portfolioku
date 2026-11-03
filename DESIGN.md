---
name: Nocturne Engineer
colors:
  surface: "#131317"
  surface-dim: "#131317"
  surface-bright: "#39393d"
  surface-container-lowest: "#0e0e12"
  surface-container-low: "#1b1b1f"
  surface-container: "#1f1f23"
  surface-container-high: "#2a292e"
  surface-container-highest: "#353439"
  on-surface: "#e4e1e7"
  on-surface-variant: "#cbc3d7"
  inverse-surface: "#e4e1e7"
  inverse-on-surface: "#303034"
  outline: "#958ea0"
  outline-variant: "#494454"
  surface-tint: "#d0bcff"
  primary: "#d0bcff"
  on-primary: "#3c0091"
  primary-container: "#a078ff"
  on-primary-container: "#340080"
  inverse-primary: "#6d3bd7"
  secondary: "#ffb0cd"
  on-secondary: "#640039"
  secondary-container: "#aa0266"
  on-secondary-container: "#ffbad3"
  tertiary: "#adc6ff"
  on-tertiary: "#002e6a"
  tertiary-container: "#4d8eff"
  on-tertiary-container: "#00285d"
  error: "#ffb4ab"
  on-error: "#690005"
  error-container: "#93000a"
  on-error-container: "#ffdad6"
  primary-fixed: "#e9ddff"
  primary-fixed-dim: "#d0bcff"
  on-primary-fixed: "#23005c"
  on-primary-fixed-variant: "#5516be"
  secondary-fixed: "#ffd9e4"
  secondary-fixed-dim: "#ffb0cd"
  on-secondary-fixed: "#3e0022"
  on-secondary-fixed-variant: "#8c0053"
  tertiary-fixed: "#d8e2ff"
  tertiary-fixed-dim: "#adc6ff"
  on-tertiary-fixed: "#001a42"
  on-tertiary-fixed-variant: "#004395"
  background: "#131317"
  on-background: "#e4e1e7"
  surface-variant: "#353439"
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: "700"
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: "700"
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: "600"
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: "600"
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: "600"
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: "600"
    lineHeight: 26px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: "400"
    lineHeight: 30px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: "400"
    lineHeight: 24px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: "400"
    lineHeight: 20px
    letterSpacing: 0em
  code-inline:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: "400"
    lineHeight: 18px
    letterSpacing: -0.01em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: "500"
    lineHeight: 14px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: "500"
    lineHeight: 20px
    letterSpacing: -0.005em
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
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6.5rem
---

## Brand & Style

This design system expresses the voice of an intentional, forward-thinking junior engineer: rigorous, understated, and technically sharp without relying on bloated theatrics. The emotional core is quiet confidence. It avoids the neon overload of stereotypical "hacker" portfolios and steers clear of dense, widget-cluttered dashboard aesthetics. Instead, it positions the developer as a craft-focused software builder who understands clarity, systems thinking, and production polish.

The visual direction merges **Minimalism** with restrained **Glassmorphism & Luminous Accents**. The architecture prioritizes deep negative space, clean typographic cadence, razor-thin structural borders, and targeted spectral luminosity (violet to magenta to azure). Luminescence is never ornamental noise; it serves as a contextual beacon guiding focus to interactive surfaces, system state transitions, and primary project narratives.

## Colors

The palette establishes an obsidian base with fine chromatic shifts rather than flat monochrome grays:

- **Canvas & Backgrounds**:
  - `bg-base`: `#0B0B0F` — The void. The deepest canvas floor.
  - `bg-surface-sunken`: `#12111A` — Inset sections, code block backgrounds, and muted structural wells.
  - `bg-surface`: `#181622` — Default card containers and panel elevations with a delicate violet cast.
  - `bg-surface-raised`: `#1E1B2E` — Hovered containers, dropdowns, and flyout overlays.

- **Borders & Rules**:
  - `border-subtle`: `#27233D` — Standard structural division, table rules, and default card perimeters.
  - `border-strong`: `#2D2A42` — Active boundaries, inputs, and resting interactive controls.
  - `border-highlight`: `rgba(139, 92, 246, 0.4)` — Dynamic violet edge bloom on focus and active states.

- **Typographic Hierarchy**:
  - `text-primary`: `#F8FAFC` — Crisp off-white ensuring WCAG AAA legibility against deep backdrops.
  - `text-secondary`: `#94A3B8` — Slate tone for descriptions, subheadings, and metadata.
  - `text-tertiary`: `#64748B` — Structural labels, timestamps, and de-emphasized markers.

- **Accents & Linear Spectral Transitions**:
  - Violet (`#8B5CF6`), Magenta (`#EC4899`), and Blue (`#3B82F6`) form an accent tri-color progression (`linear-gradient(135deg, #8B5CF6 0%, #EC4899 50%, #3B82F6 100%)`).
  - Restrict full gradient saturation strictly to display headline highlights, primary call-to-actions, active pill tabs, and sub-surface radial glows (`rgba(139, 92, 246, 0.08)`).

## Typography

The typographic engine uses **Plus Jakarta Sans** for structural headers, instilling a modern, clean, geometric cadence with tight letter-spacing. **Inter** handles narrative and reading flows with unmatched legibility and neutral tone. **JetBrains Mono** supplies precise data notation, tech-stack tags, and commit hashes, grounding the design in an authentic developer domain.

- **Headline Treatment**: Reserve gradient mask fills solely for high-impact title words (e.g., `display-hero` and `headline-lg`); avoid gradient spans longer than three consecutive words to preserve rapid scanning.
- **Reading Measure**: Constrain prose paragraphs to `65ch` max-width.
- **Micro-labels**: Always uppercase `label-caps` when referencing status tags, year markers, and system metrics.

## Layout & Spacing

The layout is an editorial, non-dashboard system built on an anchored single-column core that splits gracefully into asymmetrical spans:

- **Canvas Architecture**: Centered reading chassis with a strict desktop maximum width of `1120px` for main content and `760px` for long-form case studies.
- **Grid Layout**: 12-column responsive layout on desktop with `1.5rem` (`24px`) gutters; 4 columns on mobile with `1rem` (`16px`) gutters.
- **Vertical Rhythm**: Generous vertical negative space prevents visual overcrowding:
  - Inter-section transitions require `space-3xl` (`104px`).
  - Subsection blocks use `space-2xl` (`64px`).
  - Card interiors employ `space-lg` (`24px`) padding.
- **Reflow Logic**:
  - **Mobile (< 640px)**: Columns stack linearly. Horizontal margins contract to `margin-mobile` (`20px`).
  - **Tablet (640px – 1024px)**: 2-column project grids; sticky sub-navigation collapses to an understated top floating dock.
  - **Desktop (> 1024px)**: Asymmetrical layout balancing high-level overview anchors with project cards and timeline metrics.

## Elevation & Depth

Visual hierarchy operates through chromatic surface layering, translucent glass planes, and targeted diffuse glow, avoiding sharp drop shadows:

- **Level 0 (Canvas)**: Solid `#0B0B0F`. No blur, no elevation.
- **Level 1 (Resting Cards & Modules)**: Background `#181622` set to `92%` opacity, paired with `backdrop-filter: blur(12px)` and a `1px` border using `#27233D`.
- **Level 2 (Hovered Cards & Actionables)**: Background shifts to `#1E1B2E`. The border lightens to `#2D2A42` alongside an outer atmospheric bloom: `box-shadow: 0 10px 30px -10px rgba(139, 92, 246, 0.12)`.
- **Level 3 (Modals, Command Palettes, Floating Bars)**: Background `#181622` at `95%` opacity, with `backdrop-filter: blur(20px)`, an outline border of `rgba(139, 92, 246, 0.25)`, and a deep, dual-stage drop shadow: `0 20px 40px -15px rgba(0, 0, 0, 0.7), 0 0 50px -10px rgba(139, 92, 246, 0.15)`.
- **Atmospheric Underglow**: Primary case-study showcases may feature a pinned pseudo-element carrying a radial blur: `width: 320px`, `height: 320px`, `background: radial-gradient(circle, rgba(139, 92, 246, 0.15) 0%, rgba(236, 72, 153, 0.05) 50%, transparent 70%)`, `filter: blur(60px)`, positioned under top-level project titles.

## Shapes

The roundedness language applies **Level 2 (Rounded)**:

- Standard input fields, buttons, interactive tags, and tech badges sit at `0.5rem` (`8px`).
- Card containers, content modules, and visual media frames scale to `1rem` (`16px`, `rounded-lg`).
- Dialogs, full-width overlays, and showcase hero frames sit at `1.5rem` (`24px`, `rounded-xl`).
- Micro status indicators and navigational pill bars use fully rounded geometry (`9999px`) to create clear tactile affordances against structural rectangular cards.

## Components

### Buttons

- **Primary Button**: Base fill set to the tri-color gradient (`linear-gradient(135deg, #8B5CF6, #EC4899, #3B82F6)`). Text is crisp `#F8FAFC` (`label-md`). Hover elevates visual brightness by `10%` and projects a `0 0 20px rgba(139, 92, 246, 0.35)` glow. Active state scales element to `0.98`.
- **Secondary / Ghost Button**: Background `#181622`, border `1px solid #27233D`, text `#F8FAFC`. On hover, the border transitions to `rgba(139, 92, 246, 0.5)` with background advancing to `#1E1B2E`.

### Project Cards

- Enclosed containers with `rounded-lg` curves, padded with `space-lg`.
- Built with a `#181622` base and a `1px` border of `#27233D`.
- Hover triggers a smooth `200ms ease-out` transition: the border sharpens to `#2D2A42`, the top-edge displays a micro linear-gradient highlight border (`1px` height), and the subtle purple drop bloom activates.
- Clean typography hierarchy within: Title (`headline-sm`), description (`body-md`, `#94A3B8`), and a trailing stack row of tech badges.

### Chips & Tech Badges

- Built with `JetBrains Mono` at `code-inline` sizing.
- Inactive / Reference Chips: Surface `#12111A`, border `1px solid #27233D`, text `#94A3B8`.
- Active / Filter Chips: Surface `rgba(139, 92, 246, 0.12)`, border `1px solid #8B5CF6`, text `#F8FAFC`.

### Form Controls & Input Fields

- Background `#12111A`, border `1px solid #27233D`, text `#F8FAFC`, placeholder `#64748B`.
- Roundedness `0.5rem`, padding `0.75rem 1rem`.
- Focus ring: Removes default browser outlines; applies `border-color: #8B5CF6` and `box-shadow: 0 0 0 3px rgba(139, 92, 246, 0.15)`.

### Checkboxes & Toggle Radios

- Size `18px × 18px`, surface `#12111A`, border `1px solid #27233D`.
- Selected state fills with `#8B5CF6` displaying an off-white checkmark icon.

### Experience & Timeline Lists

- Clean sequential timeline connected by a continuous `1px` rule using `#27233D`.
- Date nodes are tagged with an outer `#181622` circular pill containing an inner `#8B5CF6` live dot (`6px × 6px`).
- Roles and descriptions use relaxed spacing (`space-sm` gap between title and body) without box containment to maintain a calm, scannable resume flow.

### Code Snippets & Terminal Blocks

- Container background `#12111A`, border `1px solid #27233D`, internal padding `space-md`.
- Top header carries three subtle window control dots (`#27233D`) and active branch/file metadata (`label-caps`, `#64748B`).
- Content rendered in `JetBrains Mono` (`code-inline`) with high contrast syntax coloring over slate values.
