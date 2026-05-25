---
name: Lumina Cinematic
colors:
  surface: '#101415'
  surface-dim: '#101415'
  surface-bright: '#363a3b'
  surface-container-lowest: '#0b0f10'
  surface-container-low: '#191c1e'
  surface-container: '#1d2022'
  surface-container-high: '#272a2c'
  surface-container-highest: '#323537'
  on-surface: '#e0e3e5'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#e0e3e5'
  inverse-on-surface: '#2d3133'
  outline: '#909097'
  outline-variant: '#45464d'
  surface-tint: '#bec6e0'
  primary: '#bec6e0'
  on-primary: '#283044'
  primary-container: '#0f172a'
  on-primary-container: '#798098'
  inverse-primary: '#565e74'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#bdc2ff'
  on-tertiary: '#131e8c'
  tertiary-container: '#00055c'
  on-tertiary-container: '#6c77e1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#e0e0ff'
  tertiary-fixed-dim: '#bdc2ff'
  on-tertiary-fixed: '#000767'
  on-tertiary-fixed-variant: '#2f3aa3'
  background: '#101415'
  on-background: '#e0e3e5'
  surface-variant: '#323537'
typography:
  display-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Be Vietnam Pro
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Be Vietnam Pro
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Be Vietnam Pro
    fontSize: 30px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 2rem
  section-padding: 8rem
  stack-sm: 0.5rem
  stack-md: 1.5rem
  stack-lg: 3rem
---

## Brand & Style
The brand personality is that of a visionary architect—calm, precise, and deeply creative. It moves away from the aggressive "hacker" tropes of AI and instead leans into a **Modern Cinematic** aesthetic that feels like a premium digital gallery. 

The design system utilizes **Glassmorphism** and **Minimalism** to create a sense of infinite depth and breathability. Surfaces should feel like polished obsidian or translucent sapphire, prioritizing high-quality whitespace and intentional motion. The emotional response is one of awe-inspired tranquility, positioning the founder as a sophisticated bridge between raw technology and high-end creative output.

## Colors
This design system operates on a deep, layered dark mode. It avoids pure black (#000) in favor of a **Soft Dark Navy** base to maintain a cinematic, non-stark atmosphere.

- **Base:** The foundation is a rich `#020617`, providing a canvas for depth.
- **Accents:** **Electric Blue** (`#38BDF8`) is used sparingly for high-action interactive elements. A **Soft Sky Blue** glow is applied to background orbs to create atmospheric depth.
- **Tonal Gradients:** Utilize subtle linear gradients (e.g., `primary` to `tertiary`) to suggest the fluid nature of AI.
- **Transparency:** Glass layers use a white or light blue stroke at 10-15% opacity to define edges without adding visual weight.

## Typography
The system uses **Be Vietnam Pro** (as a high-quality alternative to Poppins) to achieve a modern, soft, and clean aesthetic. The type scale is dramatic, emphasizing a cinematic hierarchy.

- **Headlines:** Use tight letter-spacing on larger sizes to create a "logo-like" feel for headers.
- **Body:** Generous line heights (1.6) ensure readability against dark, translucent backgrounds.
- **Labels:** Use uppercase tracking for metadata and categories to provide a professional, structured contrast to the soft headline curves.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to maintain cinematic composition, transitioning to a fluid model on mobile.

- **Whitespace:** Use aggressive vertical spacing (`section-padding`) to allow each project or thought to "breathe."
- **Grid:** A 12-column grid with wide 32px gutters. Content is often centered or offset to create a dynamic, non-standard editorial feel.
- **Safe Zones:** Ensure a minimum 24px side margin on mobile devices. Large display type should reflow to the mobile-specific tokens to prevent horizontal scrolling.

## Elevation & Depth
Depth is created through **Glassmorphism** and **Ambient Glows** rather than traditional drop shadows.

- **Glass Layers:** Containers use a background blur (20px - 40px) with a semi-transparent fill (`rgba(255, 255, 255, 0.03)`).
- **Surface Tiers:**
    - *Tier 1 (Base):* The deep navy background.
    - *Tier 2 (Cards):* Subtly lighter navy with 1px glass borders.
    - *Tier 3 (Modals/Popovers):* Higher transparency, more intense blur, and a soft outer glow in sky blue.
- **Atmosphere:** Use large, low-opacity radial gradients (200px - 600px) behind glass cards to simulate "light leaks" from the AI's core.

## Shapes
Shapes are consistently **Rounded**, reflecting the "playful yet premium" requirement. 

- **Primary Radius:** 0.5rem for standard inputs and small cards.
- **Large Radius:** 1.5rem for main portfolio project containers and featured sections.
- **Interaction:** On hover, shapes may subtly expand or increase their corner radius to feel "squishy" and responsive. Avoid sharp 90-degree angles entirely.

## Components
- **Buttons:** Primary buttons use a solid Electric Blue to Sky Blue gradient. Secondary buttons are "ghost" glass with a 1px border. All buttons should have a 0.2s transition on hover, increasing the background glow intensity.
- **Cards:** Portfolio cards feature a subtle internal border-top light (0.5px white at 20% opacity) to catch the "light" from above, enhancing the 3D glass effect.
- **Chips/Badges:** Small, pill-shaped tags with a low-opacity background tint matching the category color (e.g., Lavender for 'Design', Blue for 'Code').
- **Input Fields:** Minimalist glass fields with a soft sky blue focus ring. Labels should sit above the field in `label-caps` style.
- **Progress Indicators:** Use thin, glowing lines for scroll progress or image carousels to maintain the high-tech, cinematic feel.
- **Glass Cursor:** Consider a custom trailing cursor that acts as a localized "lens," slightly blurring or magnifying the elements it passes over.