---
name: Luxury Estate Narrative
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#4c4546'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dcdddd'
  on-secondary-container: '#5f6161'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1c1c'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e4e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  stack-lg: 4rem
  stack-md: 2rem
  stack-sm: 1rem
---

## Brand & Style
The brand personality is rooted in "Exclusivity through Simplicity." This design system targets high-net-worth individuals seeking architectural distinction and seamless experiences. The aesthetic is **Minimalist with Tactile Softness**, combining the clinical precision of modern architecture with warm, organic shapes. 

The UI should evoke a sense of calm, spatial abundance, and refined taste. By utilizing heavy white space and generous curves, the interface feels less like a digital tool and more like an editorial gallery.

## Colors
The palette is intentionally monochromatic to allow property photography to serve as the primary visual driver. 
- **Core Background:** Pure White (#FFFFFF) provides a high-end, gallery-like foundation.
- **Action & Contrast:** Pure Black (#000000) is reserved for primary actions, headings, and critical iconography.
- **Surface Tiers:** Soft Grey (#F5F5F5) is used for secondary container backgrounds to define structure without adding visual noise.
- **Muted Accents:** Mid-tone greys are used for metadata and secondary labels to maintain a clear hierarchy.

## Typography
The typography strategy pairings high-contrast editorial serifs with functional geometric sans-serifs.
- **Headlines:** Use Playfair Display for all major headings. It introduces a "Humanist" touch to the digital space, echoing luxury print media.
- **Body & Interface:** Use Montserrat for legibility and a modern, technical feel.
- **Stylistic Note:** Headlines should use tighter letter spacing to feel "locked," while uppercase labels should be tracked out for a premium, architectural look.

## Layout & Spacing
The design system employs a **Fixed Grid** philosophy for desktop to maintain the integrity of white space, transitioning to a fluid model for mobile devices.

- **Desktop:** 12-column grid with a 1440px max-width. Wide 80px outer margins create a "frame" effect around the content.
- **Rhythm:** Spacing follows a 4px baseline, but large-scale components should favor "Stack-LG" (64px) gaps to ensure the layout feels uncrowded.
- **Alignment:** Content is often center-aligned or offset to create an asymmetrical, architectural flow that guides the eye through property features.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Subtle Blurs** rather than traditional shadows.
- **Level 0 (Base):** White background.
- **Level 1 (Cards):** Soft Grey (#F5F5F5) surfaces with no border.
- **Overlays:** Glassmorphism is used for search bars and image captions. Use a high-density backdrop blur (20px-30px) with a 60% white or black opacity to ensure readability while maintaining a sense of transparency.
- **Shadows:** If used, they must be "Ambient"—extremely diffused (40px+ blur), low opacity (5%), and strictly neutral.

## Shapes
The shape language is characterized by **Generous Radii**. This softens the high-contrast black/white palette.
- **Containers & Images:** Use `rounded-xl` (1.5rem / 24px) to create a friendly, contemporary silhouette for property galleries and cards.
- **Interactive Elements:** Buttons and input fields use `rounded-lg` (1rem / 16px) for a "soft-touch" feel.
- **Chips/Badges:** Use pill-shaped rounding to distinguish them from functional buttons.

## Components
- **Primary Buttons:** Solid black background, white text, `rounded-lg`. Hover states should involve a slight scale up or a shift to a very dark grey.
- **Secondary Buttons:** Outlined with a 1px soft-grey border, or ghost-style with an arrow icon (→) to denote "View Details."
- **Property Cards:** Full-bleed images at the top with `rounded-xl` corners. Information is stacked below with generous padding (24px) inside the container.
- **Input Fields:** Large, 16px-padding fields with a soft grey background and subtle 1px border on focus.
- **Chips:** Lightweight borders (1px) with `Montserrat Label-sm` text, used for filtering property types (e.g., "Architecture," "House").
- **Navigation:** Minimalist top-bar with center-aligned links. The "Contact" button is the only high-contrast element in the header.