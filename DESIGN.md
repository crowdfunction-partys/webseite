---
name: Impact Ethos
colors:
  surface: '#fcf8f8'
  surface-dim: '#ddd9d9'
  surface-bright: '#fcf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c8'
  surface-tint: '#5d5f5f'
  primary: '#5d5f5f'
  on-primary: '#ffffff'
  primary-container: '#ffffff'
  on-primary-container: '#747676'
  inverse-primary: '#c6c6c7'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e2'
  on-secondary-container: '#646464'
  tertiary: '#5d5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffffff'
  on-tertiary-container: '#747676'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
  impact-red: '#cc0000'
  gray-dark: '#1A1A1A'
  gray-light: '#F2F2F2'
typography:
  display-xl:
    fontFamily: Bebas Neue
    fontSize: 120px
    fontWeight: '700'
    lineHeight: 110px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 48px
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is built on a foundation of **Raw Minimalism** and **Brutalist** influences, designed to capture the energy of nightlife while maintaining the serious mission of humanitarian aid. The target audience is young, socially conscious, and culture-driven.

The aesthetic prioritizes a "loud" visual hierarchy where high-impact typography does the heavy lifting. By stripping away decorative fluff and relying on stark contrasts—pure whites against deep blacks—the UI feels like an event poster or an underground zine. Graphic elements are used as structural anchors, while a vibrant red accent provides an urgent call to action. The mood is unapologetically bold, direct, and community-centric.

## Colors

The palette is stark and intentional. **Primary White** acts as the canvas, providing a clean, "startup" feel that ensures maximum legibility. **Secondary Black** is used for heavy-weight typography and primary structural elements, creating a grounded, professional atmosphere.

**Impact Red (#cc0000)** is the sole chromatic accent, reserved strictly for calls to action, urgent impact metrics, and highlights. This color should be used sparingly but boldly to guide the eye toward conversion points like "Partner werden" or "Spenden." Neutral grays are utilized only for subtle borders or background shifts to maintain the high-contrast ethos without sacrificing functional depth.

## Typography

The typography system is a study in contrast. **Bebas Neue** serves as the voice of the brand—loud, authoritative, and always in uppercase. It should be used for all major headlines and impact statements. For maximum effect, use the `display-xl` role for hero sections, allowing the text to break across lines or bleed slightly toward the edges.

**DM Sans** provides a neutral, highly readable counterpoint for body copy and descriptions. It brings the "startup" professionalism to the "party" aesthetic. Use `label-bold` for navigation items and small UI metadata to maintain a structured, modern feel.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop to maintain the clean, minimalist look inspired by editorial design. A 12-column system is used with generous gutters (24px) to ensure the content feels airy and intentional.

On mobile, the layout shifts to a single-column fluid model with tight 20px margins, prioritizing the "Mobile First" philosophy for the target event-going audience. Section vertical spacing (`section-gap`) is aggressive at 120px on desktop to allow the high-impact typography and black-and-white imagery room to breathe. Components should use an 8px base grid for internal padding and alignment.

## Elevation & Depth

This design system avoids traditional shadows and gradients in favor of **Bold Borders** and **Tonal Layers**. Depth is communicated through the physical stacking of elements and high-contrast color blocks.

- **Borders:** Use solid 1px or 2px black borders for cards and input fields.
- **Overlays:** Images should utilize black-and-white treatments with occasional red-tinted overlays or halftone patterns to mimic event posters.
- **Flat Depth:** Interactive elements do not lift; instead, they "invert" on hover (e.g., a white button with black text becomes a black button with white text).

## Shapes

The shape language is strictly **Sharp (0px roundedness)**. This reinforces the Brutalist and minimalist startup aesthetic. Every button, image container, and input field must have crisp 90-degree corners. This creates a sense of precision, seriousness, and modern edge that differentiates the brand from softer, more traditional non-profit designs.

## Components

### Buttons
Primary buttons are solid black with white Bebas Neue text, always uppercase. Secondary buttons use a 2px black border with no fill. The "Impact" button variant is solid Red with white text, used only for the primary CTA (e.g., "PARTNER WERDEN").

### Cards
Cards are defined by 1px black outlines and zero border radius. They should feature a large typography-led header and a clear separation between image and text areas.

### Imagery
Images must be treated with a high-contrast black-and-white filter. To integrate the "Impact" mission, use red graphic elements (arrows, underlines, or stickers) as overlays on photos to highlight community moments or specific donor data.

### Input Fields
Inputs are minimalist: a 1px bottom border only, with label text in `label-bold` DM Sans. Focused states switch the bottom border to Impact Red.

### Progress Bars (Impact Tracking)
To show donation goals, use a thick black bar with a red fill. No rounded corners. The percentage or amount should be placed above the bar in Bebas Neue.