---
name: Executive Dark Legal
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d2c5b1'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#9a8f7d'
  outline-variant: '#4e4637'
  surface-tint: '#efc05d'
  primary: '#efc05d'
  on-primary: '#402d00'
  primary-container: '#c69b3c'
  on-primary-container: '#4a3400'
  inverse-primary: '#7a5900'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#c5c7c8'
  on-tertiary: '#2e3132'
  tertiary-container: '#a0a2a3'
  on-tertiary-container: '#36393a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea1'
  primary-fixed-dim: '#efc05d'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5c4300'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#444748'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-md:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
This design system is engineered for a high-stakes legal environment where authority and precision are paramount. The aesthetic targets high-net-worth individuals and corporate entities requiring a "combative" yet sophisticated legal defense. 

The style utilizes a **Premium Dark Mode** approach, blending **Minimalism** with high-contrast **Corporate Modern** accents. The UI conveys power through expansive negative space, razor-sharp alignment, and the strategic use of metallic gold against deep obsidian surfaces to evoke an emotional response of absolute confidence, exclusivity, and unwavering professionalism.

## Colors
The palette is rooted in an "Onyx and Gold" theme to establish a sense of elite status. 

- **Primary (24-Karat Gold):** Reserved strictly for primary actions, critical iconography, and subtle structural accents. It must remain a focal point without being overused.
- **Background (Onyx Black):** The foundation of the interface, providing the ultimate contrast for readability and a sense of "infinite" depth.
- **Surface (Graphite Charcoal):** Used for cards and containers to provide subtle separation from the background without breaking the dark aesthetic.
- **Text Tiers:** Headlines use Pure White for maximum punch and authority. Body copy uses Platinum to reduce eye strain and establish a clear visual hierarchy.

## Typography
Montserrat is used exclusively to maintain a geometric, modern, and sturdy appearance. 

- **Display & Headlines:** Use Bold or Semi-Bold weights. Tracking (letter spacing) should be slightly tightened on larger sizes to create a "dense," authoritative look.
- **Body Text:** Use Regular weight in Platinum color. Ensure line heights are generous (1.5x+) to maintain readability against the dark background.
- **Labels:** Small labels and overlines should use Uppercase with increased letter spacing to emulate high-end editorial design.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to maintain a controlled, prestigious feel, transitioning to a fluid model on mobile.

- **Desktop:** 12-column grid with 24px gutters. Wide margins (64px+) are encouraged to emphasize the premium nature of the firm.
- **Rhythm:** A strict 8px baseline grid must be followed. Padding within cards should be generous (typically 32px or 40px) to prevent the UI from feeling "cramped" or "cheap."
- **Mobile:** 4-column grid with 20px margins. Headlines should scale down significantly to ensure no awkward wrapping occurs.

## Elevation & Depth
In this dark environment, depth is achieved through **Tonal Layers** rather than traditional shadows. 

- **Level 0 (Base):** Onyx Black (#0A0A0A) for the main application background.
- **Level 1 (Cards/Surface):** Graphite Charcoal (#1A1A1A).
- **Level 2 (Popovers/Modals):** A slightly lighter charcoal (#252525) with a very subtle 1px stroke in #333333 to define edges.
- **Accents:** Use 24-Karat Gold for thin borders (1px) on active states or high-priority CTA containers. Avoid heavy blurs; maintain crisp, hard edges for a "combative" and precise feel.

## Shapes
Following the requirement for "Round Four," the system utilizes a **Pill-shaped** approach for interactive elements. This softens the "combative" nature of the brand just enough to feel modern and accessible while maintaining professional elegance.

- **Buttons:** Fully pill-shaped (rounded-full).
- **Cards:** Large corner radius (rounded-xl / 24px-32px) to create a distinct, high-end container feel.
- **Inputs:** Matches the button radius for consistency across the form-heavy legal interface.

## Components
- **Buttons:** Primary buttons are solid Gold (#C69B3C) with Black text. Secondary buttons are outlined in Gold with Gold text. Hover states should involve a slight brightness increase of the gold.
- **Cards:** Graphite Charcoal background with no shadow. Use a 1px border of #252525 for subtle definition.
- **Input Fields:** Dark background (#0A0A0A) with a Platinum border. On focus, the border transitions to Gold. Labels remain White.
- **Iconography:** Use thick, geometric line icons in Gold. Avoid filled icons unless used for status indicators.
- **Status Indicators:** Use Gold for "Pending," White for "Neutral," and a deep muted Red for "Urgent/Action Required." 
- **Legal Tables:** High-density data should use Platinum text on alternating Onyx and Graphite rows to maintain structure without looking cluttered.