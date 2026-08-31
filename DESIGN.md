---
name: Artisanal Heritage
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#4e4639'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#7f7667'
  outline-variant: '#d1c5b4'
  surface-tint: '#775a19'
  primary: '#775a19'
  on-primary: '#ffffff'
  primary-container: '#c5a059'
  on-primary-container: '#4e3700'
  inverse-primary: '#e9c176'
  secondary: '#934b19'
  on-secondary: '#ffffff'
  secondary-container: '#ffa26a'
  on-secondary-container: '#783603'
  tertiary: '#5f5e5d'
  on-tertiary: '#ffffff'
  tertiary-container: '#a7a5a3'
  on-tertiary-container: '#3b3b3a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4201'
  secondary-fixed: '#ffdbc9'
  secondary-fixed-dim: '#ffb68c'
  on-secondary-fixed: '#321200'
  on-secondary-fixed-variant: '#753401'
  tertiary-fixed: '#e4e2e0'
  tertiary-fixed-dim: '#c8c6c4'
  on-tertiary-fixed: '#1b1c1b'
  on-tertiary-fixed-variant: '#474745'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 120px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
---

## Brand & Style
The design system is built on a "Heritage Modern" aesthetic—a sophisticated blend of classical architectural proportions and contemporary editorial minimalism. The target audience is high-net-worth homeowners seeking quality, craftsmanship, and a seamless integration of old-world charm with modern living.

The style leverages **Minimalism** with **Tactile** influences. It prioritizes generous whitespace to mirror the openness of a renovated home, using high-quality photography as the primary window into the brand's expertise. The emotional response should be one of quiet confidence, warmth, and unshakeable trust. Transitions should be slow and deliberate, evoking the pace of careful craftsmanship rather than digital urgency.

## Colors
The palette is grounded in an "Earth and Ore" philosophy. 
- **Primary (Gold - #C5A059):** Used sparingly for high-value calls to action and decorative accents that denote quality.
- **Secondary (Oxide - #8B4513):** Provides a grounding, organic warmth, used for interactive states and secondary highlighting.
- **Tertiary (Charcoal - #2C2C2B):** The primary color for text and structural borders, offering more warmth than a pure black.
- **Neutral (Warm White - #F9F7F2):** The foundation of the UI, creating a soft, paper-like background that feels more premium and residential than stark white.

## Typography
The typography pairing establishes a clear hierarchy between inspiration and information. 
- **Headlines:** `EB Garamond` provides a literary, historical weight. Use "Optical Sizing" where available to maintain elegance at large scales.
- **Body & Labels:** `Hanken Grotesk` offers a clean, contemporary contrast. Its high legibility ensures that technical details and remodeling processes are easily understood.
- **Styling Note:** Always use `label-caps` for small identifiers like service categories or section eyebrows to maintain a professional, architectural feel.

## Layout & Spacing
The layout follows a **Fixed Grid** system for desktop, centered within the viewport to create a "gallery" feel. 
- **Grid:** 12-column grid with 24px gutters. Elements should often span 6 or 8 columns to leave intentional "empty" columns on either side, enhancing the premium aesthetic.
- **Vertical Rhythm:** A generous 120px gap between major sections (e.g., Hero to Services) prevents the UI from feeling crowded.
- **Mobile:** Transition to a single-column fluid layout with 20px side margins. Large display type should scale down to 40px to remain readable on small devices.

## Elevation & Depth
This design system avoids heavy shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**. 
- **Surfaces:** Use subtle shifts in background color (e.g., from #F9F7F2 to #F0EDE5) to define content areas.
- **Borders:** Use thin (1px) borders in #2C2C2B at 10% opacity for cards and input fields.
- **Depth:** When depth is required (e.g., a floating navigation bar), use a "Soft Ambient Shadow": `0px 4px 20px rgba(44, 44, 43, 0.05)`. The goal is to make elements appear as if they are resting on a surface rather than hovering high above it.

## Shapes
In line with architectural precision, the shape language uses a **Soft (0.25rem)** roundedness. This prevents the UI from feeling too "tech-like" (which uses larger radii) or too "aggressive" (which uses sharp corners). 
- **Standard elements:** 4px radius.
- **Large containers/Cards:** 8px (rounded-lg) to subtly soften the framing of photography.
- **Buttons:** Rectangular with a 4px radius, maintaining a sturdy, foundational appearance.

## Components
- **Buttons:** Primary buttons use a solid Gold (#C5A059) background with white text. Secondary buttons use a Charcoal (#2C2C2B) outline with a hover state that fills the background.
- **Cards:** Service cards should be image-dominant. Typography should sit on the neutral background below the image or in a clean overlay with a 10% Charcoal tint.
- **Accordions:** Used for FAQs; use thin horizontal lines (Charcoal at 10% opacity) to separate items. The expand/collapse icon should be a simple '+' or '-' in the Primary Gold.
- **Testimonials:** Feature a 5-star rating system using the Primary Gold color. The quote should be set in `headline-md` Garamond to give the client's voice an authoritative, elegant feel.
- **Contact Form:** Use "Floating Label" inputs to keep the form clean. Use the Secondary Oxide (#8B4513) for focus states to provide a warm, tactile indicator of interaction.
- **Image Frames:** All photography should have a slight 1px inset border in a light grey to give the photos a "framed" gallery appearance.