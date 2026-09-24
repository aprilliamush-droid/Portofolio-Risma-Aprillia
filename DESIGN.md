---
name: Berry Core Web Retro
colors:
  surface: '#fff8f6'
  surface-dim: '#ffcfc4'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ed'
  surface-container: '#ffe9e4'
  surface-container-high: '#ffe2db'
  surface-container-highest: '#ffdad2'
  on-surface: '#331109'
  on-surface-variant: '#59413f'
  inverse-surface: '#4d251b'
  inverse-on-surface: '#ffede9'
  outline: '#8c706e'
  outline-variant: '#e0bfbc'
  surface-tint: '#ae2f30'
  primary: '#9b2125'
  on-primary: '#ffffff'
  primary-container: '#bd3a3a'
  on-primary-container: '#ffe4e1'
  inverse-primary: '#ffb3ae'
  secondary: '#566503'
  on-secondary: '#ffffff'
  secondary-container: '#daec81'
  on-secondary-container: '#5c6b0b'
  tertiary: '#674e00'
  on-tertiary: '#ffffff'
  tertiary-container: '#846500'
  on-tertiary-container: '#ffe8b8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ae'
  on-primary-fixed: '#410004'
  on-primary-fixed-variant: '#8c151c'
  secondary-fixed: '#daec81'
  secondary-fixed-dim: '#becf69'
  on-secondary-fixed: '#181e00'
  on-secondary-fixed-variant: '#404c00'
  tertiary-fixed: '#ffdf98'
  tertiary-fixed-dim: '#f0c043'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4300'
  background: '#fff8f6'
  on-background: '#331109'
  surface-variant: '#ffdad2'
typography:
  headline-xl:
    fontFamily: Rubik
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: 0.02em
  headline-xl-mobile:
    fontFamily: Rubik
    fontSize: 26px
    fontWeight: '800'
    lineHeight: 32px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Rubik
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-lg-mobile:
    fontFamily: Rubik
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-md:
    fontFamily: Rubik
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 26px
  headline-sm:
    fontFamily: Rubik
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Comfortaa
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 24px
  body-md:
    fontFamily: Comfortaa
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
  body-sm:
    fontFamily: Comfortaa
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 17px
  label-lg:
    fontFamily: Rubik
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Rubik
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Rubik
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.375rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
  space-3xl: 3rem
  gutter-chrome: 0.5rem
  padding-window: 1.25rem
---

## Brand & Style

This design system channels early-2000s personal fan-page web culture, Japanese web aesthetics, and Carrd-style layout art. It evokes cozy nostalgia, tactile playfulness, and artisanal webcraft.

Targeted at niche creators, personal portfolios, zine-style publications, and boutique community spaces, the visual language rejects sterile corporate tech in favor of charming physical metaphors: browser chrome frames, polka-dot gutters, candy-tinted pinstripes, lo-fi address bars, and rounded bookmark badges.

### Core Tenets
- **Browser-in-Browser Framing:** Layouts sit nestled inside distinct vintage window frames with structural chrome bars, navigation arrows, and chunky faux URL bars.
- **Graphic Pattern Richness:** Surfaces embrace subtle repeated motifs (fine vertical pinstripes, soft polka dots, gingham accents, and spiral doodle dividers).
- **Tactile Toylike Outlines:** Every card, button, and frame is locked together with warm, deep chocolate brown outlines rather than harsh digital blacks or generic shadows.
- **Whimsical Typographic Play:** Combinations of friendly geometric grotesque lettering mixed with bouncy, rounded weights and decorative ASCII/unicode glyphs (★, ✦, ⚝, ๑).

## Colors

The palette is derived directly from nostalgic snack packaging, retro browser graphics, and cozy picnic palettes. It uses an analog, earthy harmony grounded by chocolate-cocoa outlines and warm buttery creams.

### Color Tokens & Usage
- **Primary (`#BD3A3A` - Strawberry/Apple Red):** Hero title bars, active section tabs, emphasized badges, and pinstriped focal panels. Accompanied by a deeper shade (`#942525`) for active pressed states and striped contrast.
- **Secondary (`#A2B350` - Olive-Lime Green):** Chrome topbars, dotted footer banners, playful accent tabs, and secondary notification strips. Paired with a soft moss undertone (`#BDCD6C`) for polka dots.
- **Tertiary (`#F4C447` - Custard / Mustard Gold):** Squoval icon buttons, search address bar backgrounds, highlighted keyword chips, star bookmark tags, and unselected tab headers.
- **Neutral Core (`#50281E` - Earthy Dark Cocoa):** Replaces black across all borders, line art, primary text, and glyphs to keep the interface warm, vintage, and cohesive.
- **Background / Canvas (`#FDF5DE` - Buttery Cream):** The base desktop and page background. Elevated content layers use an ivory eggshell (`#FFFDF7`).
- **Accent Kraft (`#CF9457` - Biscuit Toast):** Used for running tickers, breadcrumb bands, and secondary metadata ribbons.

## Typography

Typography balances structural clarity with playful softness:
- **Headline & Labels (Rubik):** Provides geometric stability with softened corners, giving browser chrome headers, tickers, and button icons an inviting yet crisp arcade look. Headers often feature slight text-stroke treatments (1px `#50281E`) or drop highlights in ivory.
- **Body & Content (Comfortaa):** Delivers distinct rounded letterforms reminiscent of late-90s/early-2000s personal site typography. It feels conversational, handcrafted, and distinctly zine-inspired.
- **Styling Rules:**
  - Marquee bars and ticker strips use all-caps with generous letter-spacing, interspersed with unicode symbols like `★` and `๑`.
  - Content titles inside cards may use small colored highlight boxes beneath individual words.
  - Body text utilizes italicized variations for emphasized personal notes and diary fragments.

## Layout & Spacing

Layouts adhere to an explicit "Window Canvas" containment model:

- **Desktop & Tablet:** Content is staged inside a centralized, retro browser window frame (max-width `780px` or `960px`) centered on an infinite patterned buttery background (`#FDF5DE` with diamond or checkered lattice rules).
- **Window Anatomy:**
  1. **Main Frame:** Bounded by a continuous 2.5px to 3px solid `#50281E` border with a `16px` corner radius.
  2. **Top App Bar (Olive-lime):** Contains window controls, breadcrumb title, and squoval action buttons.
  3. **Marquee Ticker Band (Kraft/Toast):** Slim divider strip for meta announcements.
  4. **Browser Sub-Chrome (Strawberry & Gold):** Housing navigation arrows, star bookmark, and address input bar.
  5. **Column Grid Deck:** Multi-column split (e.g., 3-column tab deck) where columns have their own tab headers resting directly atop bordered container boxes.
  6. **Footer Bar:** Bottom status band with icon links and decorative doodle spacers.
- **Mobile Adaptation (<640px):**
  - The outer frame expands to full-width with a safe margin of `0.5rem`.
  - Multi-column tab decks collapse into vertically stacked accordion panels or horizontal swipeable tab cards.
  - Desktop address chrome simplifies to a sticky mini-navigation strip.

## Elevation & Depth

This design system avoids soft gaussian blurs and modern directional dropshadows. Instead, depth is established through physical print and early desktop graphic techniques:

- **Chunky Offset Hard Shadows:** Primary containers and interactive pill tabs employ a hard, non-blurred offset shadow: `box-shadow: 2px 3px 0px #50281E`.
- **Inlaid Text & Inset Bevels:** Input fields, address bars, and sub-window panels feature subtle inset highlights (`inset 0 1px 2px rgba(80, 40, 30, 0.15)`), giving the sensation of physical pressed plastic or debossed cardstock.
- **Surface Pattern Hierarchy:**
  - *Tier 0 (Viewport Background):* Diagonally crossed cream diamond lattice (`#F3E8C4` over `#FDF5DE`).
  - *Tier 1 (Outer Window Enclosure):* Thick double-line chocolate border with white/cream inner padding.
  - *Tier 2 (Chrome Headers):* Textured fill (fine vertical stripes in red `#BD3A3A` on `#B03030`, or polka-dots in `#BDCD6C` over `#A2B350`).
  - *Tier 3 (Floating Tabs & Badges):* Solid tertiary custard yellow (`#F4C447`) with crisp perimeter strokes.

## Shapes

The shape system blends retro squovals with friendly rounded geometries:
- **Default Elements:** 8px (`roundedness: 2`) border radius across buttons, input boxes, and inner frame cards.
- **Outer Window:** 14px to 16px radius for window shells, mimicking handheld CRT monitors or nostalgic web widgets.
- **Tabs & Badges:** Rounded top corners (`8px 8px 0px 0px`) for tabs docked to panels, and full pill radius (`9999px`) for floating tags, pills, and bookmark badges.
- **Borders:** Consistent `2.5px` stroke in chocolate brown (`#50281E`) across all perimeter edges, ensuring unified illustrative weight.

## Components

### Buttons
- **Window Nav Squovals:** Square buttons (`34px x 34px`) with `6px` rounded corners, custard yellow background (`#F4C447`), 2px `#50281E` border, and hard `1.5px 1.5px 0px #50281E` shadow. Centered icon in cocoa. On hover: shifts 1px down-right with shadow reducing to `0.5px`.
- **Tab Buttons:** Docked flush atop content cards.
  - *Active Tab:* Rich strawberry red (`#BD3A3A`), cream text, white inner edge, 2px border on top and sides, seamlessly merging into the panel below.
  - *Inactive Tab:* Custard yellow (`#F4C447`) or warm beige (`#E7C598`) with cocoa text.

### Address Bar / Search Input
- Rounded rectangle (`8px` radius) with ivory/cream fill (`#FFFDF7`), `2px` solid chocolate border, and subtle inner shadow.
- Left-aligned monospace/Comfortaa placeholder text, right-aligned brown magnifying glass icon.

### Cards & Content Panels
- **Striped Card:** Background filled with alternating 2px vertical stripes of strawberry red (`#BD3A3A` and `#AD3131`), 2px cocoa border. Contains warm cream text (`#FFF9EB`) with yellow boxed title highlights.
- **Dotted Card:** Olive-lime background (`#A2B350`) layered with a pattern of 3px soft dots spaced by 12px. Used for featured media and profile imagery.
- **Dashed Divider:** Card sub-sections are separated by 2px dashed cocoa or cream lines.

### Chips & Badges
- **Star Bookmark Badge:** Custard yellow squoval or pill badge featuring a solid chocolate five-point star (`★`) accompanied by title text in Rubik bold.
- **Keyword Highlights:** Inline rectangular tags with butter-yellow fill (`#F9DA73`) and cocoa text sitting directly beneath key phrases in body copy.

### Form Inputs & Checkboxes
- **Checkboxes:** 18px square with 4px border radius, 2px cocoa border, and creamy yellow background. Active state displays a hand-drawn cocoa checkmark or star glyph.
- **Text Areas:** Cream background (`#FFFDF7`), solid chocolate border, with a tiny retro scrollbar colored in olive-lime and butter yellow.

### Decorative Elements & Separators
- **Spiral Loop Divider:** Custom SVG horizontal separator depicting connected loops (like spiral notebook binding or curly telephone cords) rendered in cream or cocoa.
- **Clover / Star Ribbons:** Small horizontal repeating clusters of four-leaf clovers, stars, and decorative glyphs used above card images.