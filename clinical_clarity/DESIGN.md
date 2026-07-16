---
name: Clinical Clarity
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#424752'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#727784'
  outline-variant: '#c2c6d4'
  surface-tint: '#115cb9'
  primary: '#003f87'
  on-primary: '#ffffff'
  primary-container: '#0056b3'
  on-primary-container: '#bbd0ff'
  inverse-primary: '#acc7ff'
  secondary: '#006e25'
  on-secondary: '#ffffff'
  secondary-container: '#80f98b'
  on-secondary-container: '#007327'
  tertiary: '#004954'
  on-tertiary: '#ffffff'
  tertiary-container: '#006270'
  on-tertiary-container: '#6ddff7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#acc7ff'
  on-primary-fixed: '#001a40'
  on-primary-fixed-variant: '#004491'
  secondary-fixed: '#83fc8e'
  secondary-fixed-dim: '#66df75'
  on-secondary-fixed: '#002106'
  on-secondary-fixed-variant: '#00531a'
  tertiary-fixed: '#a4eeff'
  tertiary-fixed-dim: '#62d6ed'
  on-tertiary-fixed: '#001f25'
  on-tertiary-fixed-variant: '#004e5a'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered for the pharmaceutical industry, prioritizing precision, reliability, and sterile efficiency. The brand personality is clinical and authoritative, yet accessible to healthcare professionals and procurement officers. 

The aesthetic is rooted in **Modern Professionalism** with a heavy influence from **Minimalism**. It utilizes expansive whitespace to reduce cognitive load when navigating complex medical data. The interface evokes a sense of "cleanroom" sterility through high-contrast typography and a restrained use of color, ensuring that critical drug information and safety warnings remain the focal point. Subtle depth is used not for decoration, but to establish a clear functional hierarchy.

## Colors

The palette is anchored by "Clinical Blue" and "Vitality Green" to communicate trust and health.

- **Primary (Medical Blue):** Used for primary actions, navigational cues, and brand-level elements. It signifies authority and stability.
- **Secondary (Health Green):** Reserved for positive status indicators, safety certifications, and "in-stock" messaging.
- **Neutral (Soft Grays & White):** The "Clean White" base is essential for the clinical feel. Soft grays are used to differentiate content zones without introducing visual noise.
- **Surface Tiers:** Use `#FFFFFF` for the primary work surface and `#F8F9FA` for background scaffolding and subtle section breaks.

## Typography

This design system utilizes **Inter** for its exceptional legibility in data-dense environments. 

- **Scale:** A modular scale ensures that pharmaceutical names (High Importance) are clearly distinguished from dosage instructions and chemical compositions.
- **Hierarchy:** Use `600` weight for headlines to provide a sturdy anchor for the eye. `label-sm` is used for metadata like SKU numbers or batch IDs, often paired with a slightly increased letter spacing for readability at small sizes.
- **Readability:** Body text maintains a 1.6 line-height to prevent "eye-jump" when reading long clinical descriptions or side-effect lists.

## Layout & Spacing

The system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

- **Rhythm:** An 8px linear scale governs all padding and margin decisions. 
- **Density:** To maintain the "Medical Clean" look, avoid high-density layouts. Use `lg` (48px) and `xl` (80px) vertical spacing to separate major content blocks like "Drug Interactions" and "Manufacturer Details."
- **Alignment:** Content is strictly aligned to the left to mirror medical charts and documentation styles, facilitating rapid scanning.

## Elevation & Depth

Elevation is used sparingly to signify "interactive" versus "informative" layers.

- **Surface Levels:** The background is the lowest level. Content cards sit one level above. 
- **Ambient Shadows:** Shadows must be extremely soft and diffused (e.g., `blur: 20px, opacity: 0.04, color: #000000`). This creates a "lifted paper" effect rather than a heavy material shadow.
- **Tonal Layering:** Use subtle 1px borders in `#DEE2E6` instead of shadows for secondary elements like search inputs and filter sidebars to maintain a flat, clinical aesthetic.

## Shapes

The design system uses **Soft** roundedness. 

- **Radius:** A standard 4px (`0.25rem`) radius is applied to buttons and inputs. This provides a modern touch without appearing "bubbly" or unprofessional.
- **Product Cards:** Use a slightly larger radius (8px) for containers to create a distinct framing for product imagery.
- **Context:** Sharp corners (0px) are reserved for data tables and utility bars to emphasize precision and structural integrity.

## Components

### Search & Navigation
- **Command Search:** A prominent, full-width search bar with a light gray fill and a search icon. It should include "Type-ahead" results for drug names and therapeutic classes.
- **Filter Chips:** Used for sorting by "Dosage Form" or "Prescription Type." Use a neutral stroke that fills with the Primary color upon selection.

### Product & Info
- **Product Cards:** A white surface with an 8px radius and a very soft shadow. Include a clear image, bold headline for the drug name, and a "Health Green" label for availability.
- **Medical Info Badges:** Small, high-contrast pills (e.g., "Schedule II," "Refrigerated") used to highlight critical handling requirements.

### Actions
- **Primary Button:** Solid Medical Blue with white text. Minimalistic with no gradients.
- **Secondary/Ghost Button:** Transparent background with a 1px Blue border for "View Details" or "Download Monograph" actions.

### Data Inputs
- **Input Fields:** Clean, outlined boxes that turn Blue on focus. Error states must use a clear "Safety Red" with an accompanying icon for accessibility.