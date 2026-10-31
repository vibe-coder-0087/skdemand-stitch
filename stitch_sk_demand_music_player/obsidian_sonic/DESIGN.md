---
name: Obsidian Sonic
colors:
  surface: '#131316'
  surface-dim: '#131316'
  surface-bright: '#39393c'
  surface-container-lowest: '#0e0e11'
  surface-container-low: '#1b1b1e'
  surface-container: '#1f1f22'
  surface-container-high: '#2a2a2d'
  surface-container-highest: '#353438'
  on-surface: '#e4e1e6'
  on-surface-variant: '#cfc2d6'
  inverse-surface: '#e4e1e6'
  inverse-on-surface: '#303033'
  outline: '#988d9f'
  outline-variant: '#4d4354'
  surface-tint: '#ddb7ff'
  primary: '#ddb7ff'
  on-primary: '#490080'
  primary-container: '#b76dff'
  on-primary-container: '#400071'
  inverse-primary: '#842bd2'
  secondary: '#d2bbff'
  on-secondary: '#3f008e'
  secondary-container: '#6001d1'
  on-secondary-container: '#c9aeff'
  tertiary: '#dcb8ff'
  on-tertiary: '#480081'
  tertiary-container: '#b56eff'
  on-tertiary-container: '#3f0072'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#ddb7ff'
  on-primary-fixed: '#2c0051'
  on-primary-fixed-variant: '#6900b3'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#efdbff'
  tertiary-fixed-dim: '#dcb8ff'
  on-tertiary-fixed: '#2c0051'
  on-tertiary-fixed-variant: '#6700b5'
  background: '#131316'
  on-background: '#e4e1e6'
  surface-variant: '#353438'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
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
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system manifests an elite, nocturnal acoustic experience engineered for modern Android flagship hardware. Inspired by the sleek efficiency of industry-leading streaming platforms yet elevated by a hypnotic, neon-infused underground atmosphere, the system combines deep, battery-conserving AMOLED blacks with visceral, hyper-saturated electric violet illumination.

Targeting discerning audiophiles, digital natives, and high-frequency music consumers, the aesthetic evokes late-night studio sessions, sonic precision, and immediate sensory gratification. The stylistic direction synthesizes **Modern Android Material 3 fluid architecture** with **Luminous Dark Glassmorphism**: rich translucent obsidian tiers, soft neon atmospheric backdrops, tactile pill geometries, and tactile edge glows that make audio interaction feel alive and fluid under the thumb.

## Colors
The color architecture leverages strict contrast containment against pure and near-pure dark grounds, safeguarding battery consumption while projecting neon elements forward in space.

### Palette Mechanics
- **Base Canvas (`#080808`):** True AMOLED ground reserved for full-bleed viewport roots, player backdrops, and bottom navigation canvases.
- **Surface Elevation 1 (`#121212`):** Primary base container layer for lists, sheet backdrops, and navigation bars.
- **Surface Elevation 2 / Cards (`#18181B`):** Deep obsidian card foundations providing crisp separation from base tiers.
- **Surface Tint / Spotlight (`#1E1B2E`):** Chromatically tinted obsidian used for active media tiles, highlighted queues, and playback cards.
- **Primary Energy (`#A855F7`):** Electric Violet used for active scrubbers, key CTAs, player play/pause actions, and brand badges.
- **Secondary Core (`#7C3AED`):** Deep neon purple for gradient transitions, interactive chip states, and pressed button depth.
- **Tertiary Accent (`#8A2BE2`):** Atmospheric violet for glow ambient drop-shadows, radial visualizer bursts, and high-fidelity equalizer bars.
- **Typography Scale:** Pure White (`#FFFFFF`) for track titles and primary indicators ensuring AAA contrast; Muted Zinc (`#A1A1AA`) for secondary artist metadata, timestamps, and inactive iconography; Dark Zinc (`#52525B`) for disabled states and subtle borders.

## Typography
The system enforces a dual-type hierarchy pairing the geometric warmth and modern swagger of Plus Jakarta Sans for titles and dynamic metadata with the clinical, pixel-perfect legibility of Inter for continuous track data and system controls.

### Implementation Rules
- Track titles and release headers must employ `headline-md` or `headline-lg` with tight tracking (-0.02em) to command focus against album artwork.
- Timestamps, duration indicators, and audio bitrate tags exclusively use `label-md` or `label-sm` with tabular numerical alignment to prevent jitter during real-time playback.
- Sub-labels (e.g., artist names, album credits) leverage `body-md` in muted zinc (`#A1A1AA`) to establish crisp typographic layering below pure white headings.

## Layout & Spacing
The layout architecture utilizes an Android-first fluid container rhythm governed by an 8dp/4dp strict incremental grid system. Content spans seamlessly across device dimensions while maintaining consistent touch-target ergonomics.

### Layout Mechanics
- **Mobile Handsets (<600dp):** Single-column fluid stream with `margin-mobile` (16px), 12px gutters, and bottom-anchored persistent player controls (64px mini-player height + safe area insets).
- **Foldables & Tablets (600dp - 1024dp):** Two-pane adaptive layout featuring a fixed navigation rail (72px), sticky left-hand contextual queue/library, and fluid right-hand browsing pane.
- **Large Displays (>1024dp):** Three-tier layout consisting of persistent navigation, centered multi-column browse grid (2 to 6 columns), and permanent right-rail "Now Playing & Lyrics" panel.
- Dynamic bottom padding must systematically append 96px above Android system gesture navigation bars to accommodate the persistent playback dock.

## Elevation & Depth
Depth is constructed through optical transparency, chromatic surface illumination, and backplane glows rather than traditional opaque drop shadows.

### Elevation Hierarchy
1. **Tier 0 (Root `#080808`):** True-black background devoid of blur or shadows.
2. **Tier 1 (Surface Glass `#121212` with 80% opacity):** Utilized for headers, app bars, and floating docks with `backdrop-filter: blur(20px)`.
3. **Tier 2 (Cards `#18181B`):** Raised content surfaces featuring a hairline stroke (`1px solid rgba(255, 255, 255, 0.06)`).
4. **Tier 3 (Active Focus `#1E1B2E`):** Interactive media items surrounded by a neon violet ambient perimeter glow (`box-shadow: 0 0 24px -4px rgba(168, 85, 247, 0.25)`).
5. **Floating Audio Bar / Bottom Sheet:** Overlays Tier 2 and Tier 3 using `backdrop-filter: blur(24px)` with an upper perimeter highlight (`border-top: 1px solid rgba(168, 85, 247, 0.3)`) and an upward bloom (`box-shadow: 0 -10px 40px rgba(124, 58, 237, 0.15)`).

## Shapes
The design language adopts expressive Material 3 fluid curves. The base geometry utilizes `roundedness: 2` (0.5rem base radius) escalating up to `rounded-2xl` (1rem to 1.5rem) on album tiles and containers, contrasted with full pill structures for interactive controllers.

### Shape Assignment
- **Interactive Badges & Chips:** Full pill radius (`rounded-full` / 9999px) for genre tags, category filters, and quick toggles.
- **Album Art & Media Cards:** Smooth 16px to 24px (`rounded-2xl`) corners to evoke physical, tactile playback hardware.
- **Playback Controls & Floating Docks:** Full-pill framing for the master play/pause trigger, scrub handles, and the bottom floating mini-player container.
- **Sheets & Modal Drawers:** Top-only rounded corners at 28px (`rounded-t-3xl`) for queue trays and track options.

## Components

### Buttons & Interactive Triggers
- **Master Playback Button:** Centered circular or pill trigger filled with vibrant primary violet (`#A855F7`), featuring a pure white high-contrast glyph. On press, scales to `0.94` with a high-intensity neon back-glow (`0 0 20px #8A2BE2`).
- **Secondary Action Buttons (Shuffle, Repeat, Like):** Borderless, 48x48dp minimum touch targets. Default state in muted zinc (`#A1A1AA`); active states switch to `#A855F7` accompanied by a subtle localized glow dot beneath the glyph.
- **Outlined Buttons:** Translucent obsidian fill (`rgba(24, 24, 27, 0.6)`) framed by a 1px border (`rgba(168, 85, 247, 0.4)`), shifting to pure white text on hover or tap.

### Chips & Filter Pills
- Rendered with continuous pill curvature (`rounded-full`), 32dp height, and horizontal padding of 16px.
- Unselected chips feature a subtle background (`#18181B`) with muted text (`#A1A1AA`).
- Selected chips activate with a rich gradient background from `#7C3AED` to `#A855F7` and pure white text (`#FFFFFF`).

### Audio Track List Items
- 56dp height layout on mobile.
- Left slot: 40x40dp album art with 8dp rounded corners, or track index number (tabular font).
- Middle slot: Two-line vertical stack with track title in `#FFFFFF` (`body-md`, semibold) over artist name in `#A1A1AA` (`body-sm`).
- Right slot: Duration stamp and contextual three-dot overflow button.
- Active playing state: Track title shifts to `#A855F7` accompanied by a micro animated 3-bar equalizer glyph.

### Cards & Media Carousels
- Multi-tier obsidian card (`#18181B`) with 16dp rounded corners (`rounded-2xl`) and 12dp internal padding.
- Displays full-bleed aspect-ratio 1:1 artwork topped with a subtle inner top-edge highlight.
- Hover or focused card state elevates via a gentle 1px border transition to `rgba(168, 85, 247, 0.45)` and ambient purple shadow.

### Input Fields & Search Bars
- Pill-shaped container (`rounded-full`) backed by `#18181B` and a subtle 1px border in `#27272A`.
- Left-aligned search icon in `#A1A1AA` shifting to `#A855F7` upon input focus.
- Placeholder text in `#71717A`; user text in `#FFFFFF`. Focus triggers an outer glow ring: `0 0 0 2px rgba(168, 85, 247, 0.3)`.

### Audio Scrubbers & Progress Bars
- Linear slider consisting of a 4dp tall inactive track in `#27272A`.
- Active elapsed track filled with a horizontal gradient from `#7C3AED` to `#A855F7`.
- Scrub handle: 12dp circular thumb in `#FFFFFF` with a 2px ring in `#A855F7`, expanding to 16dp during active drag.

### Checkboxes & Switch Toggles
- Material 3 fluid switch architecture: 52x32dp track in `#27272A`, sliding to `#A855F7` when checked.
- Thumb is pure white `#FFFFFF`, expanding slightly during drag transitions.