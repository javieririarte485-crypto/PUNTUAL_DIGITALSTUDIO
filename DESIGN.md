---
name: Ethos Marble & Metal
colors:
  surface: '#fff8f6'
  surface-dim: '#eed5cc'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ec'
  surface-container: '#ffe9e2'
  surface-container-high: '#fce3da'
  surface-container-highest: '#f6ddd4'
  on-surface: '#261913'
  on-surface-variant: '#52433f'
  inverse-surface: '#3c2d27'
  inverse-on-surface: '#ffede7'
  outline: '#85736e'
  outline-variant: '#d7c2bc'
  surface-tint: '#88503d'
  primary: '#854d3b'
  on-primary: '#ffffff'
  primary-container: '#a26551'
  on-primary-container: '#fffbff'
  inverse-primary: '#feb59d'
  secondary: '#605e5c'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2df'
  on-secondary-container: '#666462'
  tertiary: '#68594a'
  on-tertiary: '#ffffff'
  tertiary-container: '#827261'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#feb59d'
  on-primary-fixed: '#360f03'
  on-primary-fixed-variant: '#6c3927'
  secondary-fixed: '#e5e2df'
  secondary-fixed-dim: '#c9c6c3'
  on-secondary-fixed: '#1c1b1a'
  on-secondary-fixed-variant: '#484745'
  tertiary-fixed: '#f4dfcb'
  tertiary-fixed-dim: '#d7c3b0'
  on-tertiary-fixed: '#241a0e'
  on-tertiary-fixed-variant: '#524436'
  background: '#fff8f6'
  on-background: '#261913'
  surface-variant: '#f6ddd4'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
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
    letterSpacing: 0em
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  section-gap: 120px
---

## Brand & Style

The design system is rooted in the intersection of organic luxury and digital precision. It caters to high-end clients seeking a digital studio that balances timeless elegance with technological mastery. The brand personality is poised, authoritative, and meticulously crafted.

We employ a **Modern Minimalist** style with **Tonal Layering**. By utilizing expansive white space (the "marble" canvas) and precision-engineered accents (the "copper" details), the interface evokes the feeling of a high-end physical gallery. The visual narrative focuses on "Architectural Tech"—where every element feels structural, intentional, and premium.

## Colors

The palette is derived from natural materials—polished stone and metallic ores.

- **Primary (Copper/Rose Gold):** Use for key calls-to-action, active states, and decorative structural lines. It represents the "spark" of digital innovation.
- **Secondary (Marble White):** The primary background color. It is not a pure white, but a warm, stony neutral that reduces eye strain and adds depth.
- **Tertiary (Warm Sand):** Used for subtle backgrounds, dividers, and disabled states to maintain the warm, organic feel.
- **Neutral (Deep Espresso):** Replaces pure black for all typography and heavy borders to ensure the high-contrast look remains sophisticated rather than harsh.

## Typography

The typography strategy pairs the geometric strength of **Montserrat** with the technical refinement of **Manrope**.

Headlines should utilize wide tracking and bold weights to command attention, mirroring the chiseled look of the studio's logo. **Manrope** is selected for body text due to its modern proportions and exceptional legibility in data-dense layouts. For a "Digital Studio" feel, use `label-md` for navigation and small headers, always in uppercase with generous letter spacing (5%) to evoke a sense of curated architectural labeling.

## Layout & Spacing

This design system uses a **Fixed Grid** philosophy on desktop to maintain a sense of "framed" art, and a fluid approach for mobile. 

- **The Studio Layout:** We utilize a 12-column grid with exceptionally wide gutters (32px) to prevent the UI from feeling cluttered. 
- **Generous Breathing Room:** Vertical rhythm is driven by the `section-gap` of 120px, ensuring that each service or portfolio piece feels like its own exhibit.
- **Mobile Reflow:** On mobile, margins shrink to 24px, and the grid collapses to 4 columns. Typography scales down specifically for `headline-lg` to ensure balance.

## Elevation & Depth

To mimic the logo's appearance on a marble slab, we avoid heavy, dark shadows. Instead, we use:

1.  **Tonal Depth:** Different shades of the "Marble" palette (Secondary and Tertiary) to distinguish between the background and elevated cards.
2.  **Inset Accents:** Use 1px internal borders in the Primary color (Copper) to simulate "inlaid" metal.
3.  **Soft Ambient Shadows:** For floating elements like modals or dropdowns, use highly diffused shadows: `0 12px 48px rgba(61, 46, 40, 0.08)`. The shadow color should always be a tint of the Deep Espresso neutral, never pure black.

## Shapes

The shape language is **Soft (0.25rem)**. This provides a subtle nod to modern tech while maintaining the sharp, professional edges associated with luxury architectural design. 

- **Primary Buttons:** Use the standard `rounded` (4px) for a crisp, professional look.
- **Images/Cards:** Use `rounded-lg` (8px) to provide a soft container for studio work.
- **Decorative Elements:** Lines and dividers should be thin (1px) and terminate in sharp points, reflecting the precision of digital craftsmanship.

## Components

- **Buttons:** Primary buttons feature a solid Copper fill with White text. Hover states should transition to a slightly deeper copper with a subtle 1px "metal" glow (outer shadow in the primary color).
- **Input Fields:** Use a "Minimal Frame" style—only a bottom border in Tertiary color, which transitions to a full Copper border on focus. This keeps the forms feeling like elegant stationary.
- **Cards:** Cards should have no visible border or a very faint 1px border in Tertiary. Use a soft background color change (Secondary to Tertiary) on hover to indicate interactivity.
- **Chips/Tags:** Small, all-caps text using `label-md` inside a container with a 1px Copper border. 
- **Dividers:** Instead of simple gray lines, use horizontal rules in the Primary Copper color at 0.5px thickness to create "golden threads" throughout the UI.
- **Lists:** Use custom bullet points that are small Copper diamonds (rotated squares) to maintain the geometric studio aesthetic.