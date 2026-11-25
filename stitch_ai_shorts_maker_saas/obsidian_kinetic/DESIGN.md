---
name: Obsidian Kinetic
colors:
  surface: '#0f131b'
  surface-dim: '#0f131b'
  surface-bright: '#353941'
  surface-container-lowest: '#0a0e15'
  surface-container-low: '#181c23'
  surface-container: '#1c2027'
  surface-container-high: '#262a32'
  surface-container-highest: '#31353d'
  on-surface: '#dfe2ed'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dfe2ed'
  inverse-on-surface: '#2d3038'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#00b2d0'
  on-tertiary-container: '#003f4b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#0f131b'
  on-background: '#dfe2ed'
  surface-variant: '#31353d'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
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
    lineHeight: 16px
  code-metric:
    fontFamily: JetBrains Mono
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.02em
  code-timestamp:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-throughput creative engineering, built specifically for creators, video editors, and social growth teams transforming horizontal long-form footage into algorithmic vertical shorts (9:16). 

The emotional tone balances surgical video editor utility with the dynamic energy of viral distribution. Visual motifs draw heavily from **Cyber-Glassmorphism** layered over deep obsidian voids: frosted surfaces, subtle edge luminescence, precise structural borders, and electric neon accents. The interface prioritizes rendering speed, high-density timeline manipulation, metric visibility, and immediate AI state differentiation.

## Colors

The palette relies on absolute dark-mode discipline to keep video preview feeds, timeline audio waveforms, and heatmaps high in contrast.

- **Obsidian Neutrals:** 
  - Base canvas: `#090D14`
  - Layer 1 (Navigation & sidebars): `#0D131F`
  - Layer 2 (Cards, modals, panels): `#141C2E`
  - Surface highlight & borders: `rgba(255, 255, 255, 0.08)`
- **Virality Emerald (`#10B981` / `#059669`):** Primary driver for generation triggers, virality score readouts, conversion actions, success states, and exported video highlights.
- **Cyber Violet (`#8B5CF6` / `#A855F7` / `#7C3AED`):** Signals AI processing engines, transcription tracking, face-tracking bounding boxes, and automated clipping nodes.
- **Cyber Cyan (`#06B6D4`):** Tertiary indicator for audio waveform peaks, caption synchronization, and multi-platform sync tags (TikTok, YouTube Shorts, Reels).

## Typography

The typographic hierarchy establishes clear structural separation between creative storytelling, operational UI, and precise temporal telemetry:

- **Display & Headlines (`Plus Jakarta Sans`):** Provides a geometric, modern posture with tight tracking for hero statistics, clip batch titles, and modal headers.
- **Body & Controls (`Inter`):** Handles variable-length video transcriptions, setting labels, tooltip explanations, and interface metadata without distracting from video canvas assets.
- **Telemetry & Data (`JetBrains Mono`):** Applied to timestamps (`00:14:22.08`), viral predict scores (`98.4%`), aspect ratio presets (`9:16`, `1:1`), render bitrates, and AI token limits. Text using `label-caps` is styled uppercase with wide tracking for clear scannability across dense control grids.

## Layout & Spacing

The layout model uses a multi-tier fixed-and-fluid hybrid architecture:

- **Canvas & Workspace:** The main studio workspace utilizes a dynamic 3-column split view (Source & Script / 9:16 Realtime Player Canvas / Timeline & Virality Inspector). On desktop, side panels maintain fixed widths (340px-420px) while the video viewport expands dynamically.
- **Grid Architecture:** Secondary views (dashboard, batch manager, export library) conform to a 12-column responsive fluid grid with `1rem` gutters on small viewports and `1.5rem` gutters on screens above 1440px.
- **Breakpoints:**
  - *Mobile (<768px):* Single-column vertical stack. Video preview pins to top; clipping tools and tabs shift to bottom sheets. Canvas margins collapse to `margin`.
  - *Tablet (768px - 1199px):* Dual-panel view. Video canvas left, segmented clip cards right.
  - *Desktop (≥1200px):* Full triple-panel studio layout with permanent transport bar and timeline deck.

## Elevation & Depth

Visual hierarchy uses physical-depth glassmorphism coupled with neon boundary luminescence rather than traditional dropped shadows:

- **Surface Tiers:**
  - *Base:* `#090D14` (non-interactive backdrop).
  - *Panel Glass:* `#0D131F` at 85% opacity with `backdrop-filter: blur(16px)` and a `1px` border of `rgba(255, 255, 255, 0.06)`.
  - *Floating Modals & Dropdowns:* `#141C2E` at 95% opacity with `backdrop-filter: blur(24px)` and edge highlights of `rgba(255, 255, 255, 0.12)`.
- **Luminescent Accent Halos:**
  - *AI Processing Elevation:* Elements running active extraction algorithms display an ambient glow: `box-shadow: 0 0 24px -4px rgba(139, 92, 246, 0.35)`.
  - *High-Virality Elevation:* Clips scoring above 90% virality receive an ambient success border: `box-shadow: 0 0 20px -2px rgba(16, 185, 129, 0.3)`.

## Shapes

The interface employs a unified `0.5rem` (`rounded-md`) standard for primary interactive components, striking a clean technical balance between sharp code editors and soft consumer mobile apps.

- **Standard Elements (0.5rem):** Buttons, input fields, dropdown triggers, clip segments on the timeline, metric badges.
- **Card Containers (1rem):** 9:16 video cards, export queue blocks, inspector panels.
- **Pill Surfaces:** Status tags, active waveform scrubbing handles, and social destination selectors (TikTok, Shorts, Reels) leverage fully-rounded pill shapes (`rounded-full`) to differentiate global tags from structural controls.

## Components

### Buttons
- **Primary ("Generate Shorts"):** Solid emerald fill (`#10B981`), dark text (`#090D14`), `font-weight: 600`. Hover state triggers brightness expansion (`#34D399`) and subtle emerald glow.
- **AI Action ("Auto-Crop / Smart Caption"):** Deep violet gradient fill (`linear-gradient(135deg, #7C3AED, #8B5CF6)`), crisp white text, luminous purple border.
- **Secondary / Ghost:** Transparent background, `1px` border of `rgba(255, 255, 255, 0.12)`, text `#F3F4F6`. Hover introduces background `#141C2E`.

### Cards & 9:16 Video Previews
- **Video Card:** Aspect-locked container framed by `rgba(255, 255, 255, 0.08)`. Features an overlay badge carrying the virality score in the top-right corner.
- **Clip Segment Card:** Displays time range via `JetBrains Mono`, generated viral hook headline, and instant platform export triggers. Hover state transitions border to `rgba(16, 185, 129, 0.4)`.

### Chips & Badges
- **Virality Score Chip:** Obsidian surface (`#0D131F`), vibrant emerald text (`#10B981`), `1px` border of `rgba(16, 185, 129, 0.3)`. Shows numerical score alongside a lightning or flame icon.
- **Platform Selector Chip:** Multi-select pill toggle with embedded platform icons (TikTok, Reels, Shorts). Inactive states sit muted at 50% opacity; active states illuminate with platform-specific or violet bounding rings.

### Timeline & Playhead Controls
- **Scrubber Deck:** Dark slate track with highlighted segments marking viral sections. Inactive segments are dimmed; AI-recommended hooks glow with emerald-purple dual gradients.
- **Playhead Marker:** Emerald needle line with active timestamp badge hovering above in `JetBrains Mono`.

### Input Fields & Controls
- **URL & Prompt Inputs:** Obsidian base (`#0D131F`) with inset border `rgba(255, 255, 255, 0.1)`. Focus states smoothly shift border to `#8B5CF6` with a `0 0 0 1px #8B5CF6` focus ring.
- **Toggles & Checkboxes:** Emerald-filled active state with high-contrast indicator dot.