---
name: Academic Luminary
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
  on-surface-variant: '#4a4455'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#7b7487'
  outline-variant: '#ccc3d8'
  surface-tint: '#732ee4'
  primary: '#630ed4'
  on-primary: '#ffffff'
  primary-container: '#7c3aed'
  on-primary-container: '#ede0ff'
  inverse-primary: '#d2bbff'
  secondary: '#6b38d4'
  on-secondary: '#ffffff'
  secondary-container: '#8455ef'
  on-secondary-container: '#fffbff'
  tertiary: '#4f4d5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#676577'
  on-tertiary-container: '#e7e4f8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#eaddff'
  primary-fixed-dim: '#d2bbff'
  on-primary-fixed: '#25005a'
  on-primary-fixed-variant: '#5a00c6'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#e4e0f5'
  tertiary-fixed-dim: '#c7c4d8'
  on-tertiary-fixed: '#1b1a29'
  on-tertiary-fixed-variant: '#464555'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.035em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: '1.15'
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: '1.35'
    letterSpacing: -0.02em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.65'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.01em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 0.8125rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  label-badge:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.02em
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
  margin: 4rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system targets an early-career software engineer and computer science university student presenting technical work to engineering recruiters, researchers, and tech founders. The brand personality balances academic rigor with refined, contemporary software craft. The visual tone must inspire confidence, intellectual clarity, and precision without coming across as sterile or template-driven.

The aesthetic philosophy is **Hyper-Minimalist Neo-Editorial**:
- **Pure Whitespace**: Layouts leverage intentional negative space to give complex technical projects room to breathe.
- **Micro-Refinement**: Subtle lavender chromatic atmospheric washes create dimension without visual noise.
- **Academic Seriousness meets Modern SaaS**: Clear type hierarchies, structured project logs, and monospaced micro-labels evoke high craftsmanship.

## Colors

The palette revolves around pristine light surfaces modulated with ethereal violet-lavender tints and sharp slate ink tones:

- **Primary (`#7C3AED`)**: The anchor violet. Used strictly for interactive calls to action, high-priority links, and focused active states.
- **Secondary (`#8B5CF6`)**: Soft vivid purple for badges, skill tags, and accent borders.
- **Tertiary (`#EDE9FE`)**: Delicate lavender wash for tag backgrounds, selected container fills, and hover highlights.
- **Neutral (`#0F172A`)**: Deep ink slate, avoiding harsh `#000000` to maintain an elegant editorial look while guaranteeing peak WCAG AAA contrast against light grounds.
- **Canvas & Surface System**:
  - Base canvas: `#FFFFFF` (pure stark white)
  - Surface-container low: `#FAF9FE` (subtle off-white with micro-violet undertone)
  - Surface-container subtle: `#F5F3FF` (warm lavender tint for code blocks and inset sections)
  - Secondary text / Muted ink: `#475569` (slate 600) for summaries, meta tags, and timestamps.

## Typography

The typographic balance combines geometric charisma, utilitarian readability, and technical precision:

- **Display & Headlines (`Plus Jakarta Sans`)**: Delivers crisp geometric authority with humanistic curvature. Tight negative tracking creates dense, confident headings for project titles and page statements.
- **Body (`Inter`)**: Chosen for its neutral, highly legible glyph construction. Set at relaxed line heights (1.6x) to facilitate scanning through research abstracts, technical architecture explanations, and experience narratives.
- **Code & Micro-Labels (`JetBrains Mono`)**: Employed for commit hashes, tech stack lists, paper DOI references, and terminal snippets.

## Layout & Spacing

The portfolio is structured around a centralized, constrained fluid grid designed to maximize visual focus without sprawling on ultra-wide screens:

- **Layout Structure**: 
  - Max container width: `1120px` for optimal reading length and card proportions.
  - 12-column desktop grid with `1.5rem` gutters.
  - 4-column mobile grid with `1rem` gutters.
- **Section Margins**: Ample vertical separation (`space-2xl` to `5rem`) between core sections (Hero, Featured Projects, Research & Publications, Education, Contact).
- **Responsive Adaptations**:
  - **Desktop (>1024px)**: Asymmetrical two-column layouts for project showcases (visual preview on one side, technical specs and GitHub links on the other).
  - **Tablet (640px - 1023px)**: Fluid single-column with side-by-side metric chips. Outer margins compress to `2rem`.
  - **Mobile (<640px)**: Strict vertical stack; gutters compress to `1rem`; margins drop to `1.25rem`.

## Elevation & Depth

Visual hierarchy uses a hybrid of tonal separation, fine-line borders, and micro-diffused ambient violet shadows:

- **Surface Layers**:
  - Layer 0 (Canvas): Pure White (`#FFFFFF`).
  - Layer 1 (Card & Containers): `#FFFFFF` on top of faint borders (`rgba(15, 23, 42, 0.06)`).
  - Layer 2 (Elevated & Active): Inset surfaces or callouts shift into `#FAF9FE` or `#F5F3FF`.
- **Shadow Philosophy**:
  - Shadows must remain soft, low-contrast, and slightly tinted with violet:
    - *Default Card Shadow*: `0 2px 8px -2px rgba(15, 23, 42, 0.04), 0 8px 24px -4px rgba(124, 58, 237, 0.04)`
    - *Interactive Hover*: `0 12px 32px -6px rgba(124, 58, 237, 0.1), 0 4px 12px -2px rgba(15, 23, 42, 0.03)`
- **Border Treatment**: Ghost borders (`1px solid #EDE9FE` or `1px solid rgba(15, 23, 42, 0.06)`) ground all floating panels to maintain razor-sharp editorial definition.

## Shapes

The shape system adopts a cohesive, approachable geometric roundedness:

- **Standard Containers & Cards**: `rounded-lg` (1rem / 16px) produces clean, friendly framing for projects, paper summaries, and experience timeline nodes.
- **Interactive Elements (Buttons, Inputs)**: `rounded-md` (0.5rem / 8px) ensures buttons feel structured and intentional rather than toy-like.
- **Pill Badges & Meta Tags**: Full radius (`9999px`) reserved for technology pills, status indicators (e.g., "Available for Summer 2025"), and category tags.

## Components

### Buttons
- **Primary**: Solid `#7C3AED` background, `#FFFFFF` text, `rounded-md` (0.5rem). Subtle hover lift with background transition to `#6D28D9` and a low lavender glow.
- **Secondary / Ghost**: Pure `#FFFFFF` background, `1px solid #EDE9FE` border, `#0F172A` text. Hover shifts background to `#FAF9FE` and border to `#8B5CF6`.
- **Icon / External Link**: Minimalist monochrome icon buttons with `#475569` fill that transition to `#7C3AED` on hover.

### Chips & Badges
- **Tech Stack Badges**: Pill-shaped (`rounded-full`), padded with `0.25rem 0.75rem`, set in `label-badge`. Background is `#F5F3FF`, border is `1px solid #EDE9FE`, text is `#7C3AED`.
- **Status Indicator**: Compact chip featuring a pulsating green or lavender micro-dot (`6px`) signaling availability for employment or research collaboration.

### Project & Research Cards
- **Base Style**: Pure white surface, 16px (`rounded-lg`) corner radius, surrounded by a 1px border of `#EDE9FE`.
- **Interaction**: On pointer hover, the border darkens to `#C4B5FD` with a subtle translate-y (`-2px`) and soft lavender shadow bloom.
- **Header**: Contains project metadata, live demo links, repository badges, and academic publication tags.

### Input Fields & Contact Elements
- **Text Inputs & Textareas**: `#FAF9FE` background, `1px solid rgba(15, 23, 42, 0.08)` border, padded with `0.75rem 1rem`. Focus state features a crisp 1px ring of `#7C3AED` and a pure white background.

### Code & Architecture Snippets
- **Blocks**: Background `#F5F3FF` with a fine border `#EDE9FE`. Typography uses `label-code` in `#0F172A`, paired with soft violet comment highlights.
- **Inline Code**: Background `rgba(139, 92, 246, 0.08)` with `#7C3AED` ink and a 4px corner radius.

### Timeline & Experience Node
- **Style**: Vertical connecting line in `1px solid #EDE9FE`. Nodes represented by 8px circular points styled with a solid `#7C3AED` center and a 4px `#EDE9FE` aura.