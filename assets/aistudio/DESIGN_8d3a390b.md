---
name: Mint Pulse Productivity
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
  on-surface-variant: '#3c4a42'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#1b6b51'
  on-secondary: '#ffffff'
  secondary-container: '#a6f2d1'
  on-secondary-container: '#237157'
  tertiary: '#006c4b'
  on-tertiary: '#ffffff'
  tertiary-container: '#00b982'
  on-tertiary-container: '#00422c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#a6f2d1'
  secondary-fixed-dim: '#8bd6b6'
  on-secondary-fixed: '#002116'
  on-secondary-fixed-variant: '#00513b'
  tertiary-fixed: '#68fcbf'
  tertiary-fixed-dim: '#45dfa4'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
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
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
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
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers a fresh, calm, and focused productivity experience tailored for modern knowledge workers, founders, and teams seeking structured clarity without cognitive overload. Drawing inspiration from clean Scandinavian minimalism paired with crisp, organic micro-glassmorphism, the visual character feels energized yet tranquil.

The personality balances high-utility structure with an approachable, restorative tone. Tactile routine cues, airy negative space, rounded pill containers, and clean visual timetables transform chaotic daily planning into an intuitive, rhythmic flow. The aesthetic avoids cold, sterile corporate styling in favor of luminous mint gradients, crystalline card surfaces, and subtle ambient emerald glow.

## Colors

The color palette centers around crisp, revitalizing emerald and mint tones supported by deep slate for razor-sharp legibility and an airy canvas of soft neutrals.

- **Primary (`#10B981`)**: The vibrant mint anchor for primary actions, active timeline markers, progress rings, and key state transitions.
- **Secondary (`#065F46`)**: A rich, grounded forest emerald used for high-contrast accents, strong headline highlights, and critical emphasis.
- **Tertiary (`#34D399`)**: A vivid light mint designed for hover states, glowing data visualizers, routine completion milestones, and subtle backlights.
- **Neutral Surface & Text (`#0F172A` / `#F8FAFC`)**: Text employs deep slate `#0F172A` for high visual ergonomics, paired with secondary labels in `#64748B`. The canvas rests on `#F8FAFC`, with soft tinted card backings in `#ECFDF5`.
- **Status Accents**: Routine categories and focus blocks leverage intentional contextual accents: soft amber (`#F59E0B`) for midday transitions, sky blue (`#3B82F6`) for deep focus blocks, and rose coral (`#F43F5E`) for urgent time blocks.

## Typography

The typographic hierarchy pairs **Plus Jakarta Sans** for expressive, geometric headers and pill labels with **Inter** for neutral, utilitarian body copy and data density.

- **Headlines & Display**: Plus Jakarta Sans delivers structural confidence with soft geometry. Generous negative letter-spacing on larger sizes tightens rhythm and creates an authoritative tech-forward impression.
- **Body & Data Tables**: Inter delivers uncompromised optical legibility across dense timetable lists, task descriptions, and focus schedules.
- **Labels & Badges**: Small metadata tags, weekday pill selectors, and status indicators leverage uppercase Plus Jakarta Sans with deliberate letter-spacing (`0.08em`) to guarantee immediate visual classification at small scales.

## Layout & Spacing

The layout is built upon a 12-column fluid responsive grid anchored by generous exterior margins and disciplined spacing multiples based on an 8pt system:

- **Desktop (1024px+)**: Max container width of 1240px centered with `margin: 2.5rem` and `gutter: 1.5rem`. Layout supports asynchronous side-by-side routines, preview cards, and multi-column workflow views.
- **Tablet (768px - 1023px)**: 8-column layout with 2rem margins and 1.25rem gutters. Secondary productivity sidebars shift into progressive collapsible panels.
- **Mobile (< 768px)**: 4-column layout with 1.25rem outer canvas padding. Hero devices, schedule blocks, and goal containers collapse into single-column vertical stacks.
- **Internal Component Rhythm**: Use `space-xs` and `space-sm` for tag and chip interiors, `space-md` for row gaps and form clusters, and `space-lg` to `space-xl` for sectional separation within cards.

## Elevation & Depth

Visual hierarchy combines stacked tonal layers, glassmorphism, and airy ambient shadows:

- **Base Canvas**: Neutral matte `#F8FAFC`.
- **Card Surfaces**: Pure white `#FFFFFF` or semi-opaque `#FFFFFF` at 85% opacity with an active `backdrop-filter: blur(16px)` when overlaid on device previews or landing page gradients.
- **Tinted Highlights**: Highlighted cards and focus active blocks utilize `#ECFDF5` at 60-100% opacity with a refined border (`1px solid rgba(16, 185, 129, 0.15)`).
- **Shadow Philosophy**:
  - *Resting Card*: `0 4px 20px -2px rgba(15, 23, 42, 0.04), 0 1px 3px rgba(15, 23, 42, 0.02)`.
  - *Elevated / Floating Dock*: `0 20px 40px -8px rgba(16, 185, 129, 0.12), 0 8px 16px -4px rgba(15, 23, 42, 0.06)`.
  - *Interactive Hover*: Subtle translation (-2px) with an expanded ambient mint shadow tint.
- **Separators & Outlines**: Clean, low-contrast ghost borders (`1px solid #E2E8F0`) keep tables, weekday switchers, and time block rows legible without visual weight.

## Shapes

The shape system embraces warm, rounded clarity:

- Standard structural elements (cards, form panels, schedule tables) use `0.5rem` to `1rem` corner rounding.
- High-level preview enclosures and device mock containers leverage extra-large rounded containers (`rounded-xl` at 1.5rem) to reinforce modern hardware contours.
- Interactive interactive tags, day-of-week selectors, task status capsules, and quick-add buttons strictly use full pill geometry (`rounded-full` / 9999px) to convey tactile comfort.

## Components

### Buttons & Interactive Badges
- **Primary Button**: Solid `#10B981` background with white text, 0.5rem corner rounding (or full pill for CTAs), generous horizontal padding (`1.5rem`), bold weight, and a subtle glowing shadow (`0 4px 14px rgba(16, 185, 129, 0.35)`).
- **Secondary / Ghost Button**: White surface with a `1px solid #E2E8F0` border, slate `#0F172A` text, shifting to `#ECFDF5` and `#10B981` border on hover.
- **Pill Badges & Day Selectors**: Circular or oblong pills (`h-8`, `px-3`). Inactive states feature `#F1F5F9` surfaces with `#64748B` text. Active or current states leverage `#10B981` with white text, or soft salmon `#F87171` for urgent alerts.

### Cards & Container Panels
- **Feature & Planner Cards**: Pristine white or glassmorphic `#FFFFFF` base enclosed in a faint `1px solid #E2E8F0` border. Outer radius at `1.25rem`. Header areas feature uppercase status pills (e.g., `DAILY SYNC`) in soft rose or mint tints.

### Timetable & Productivity Visual Cues
- **Focus Blocks**: Structured row items with fixed time columns (`08:00`, `09:30`), colored category indicator capsules (e.g., coral for kick-off, deep cobalt for deep work, amber for lunch, emerald for wrap-up), task descriptor typography, and right-aligned completion targets.
- **Checkboxes & Habit Radios**: Circular outline rings (`border-2 border-slate-300`, `w-5 h-5`) that fill with `#10B981` and a clean white checkmark upon completion.
- **Numbered Goal Items**: Circular sequence pills (`1`, `2`, `3`) filled with salmon `#FDA4AF` or mint `#A7F3D0` accompanied by single-line task inputs and terminal check indicators.

### Inputs & Date Header Fields
- Subtle bottom-line or pill-framed input containers with transparent backings, smooth transitions to `#10B981` focus rings, and soft placeholder styling in `#94A3B8`.