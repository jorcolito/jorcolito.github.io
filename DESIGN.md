---
name: Botanical Wellness System
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
  on-surface-variant: '#434842'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#737871'
  outline-variant: '#c3c8c0'
  surface-tint: '#4f644f'
  primary: '#435844'
  on-primary: '#ffffff'
  primary-container: '#5b705b'
  on-primary-container: '#dbf3d8'
  inverse-primary: '#b6cdb4'
  secondary: '#566342'
  on-secondary: '#ffffff'
  secondary-container: '#d7e5bb'
  on-secondary-container: '#5a6745'
  tertiary: '#704a22'
  on-tertiary: '#ffffff'
  tertiary-container: '#8b6238'
  on-tertiary-container: '#ffe8d5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e9cf'
  primary-fixed-dim: '#b6cdb4'
  on-primary-fixed: '#0d1f10'
  on-primary-fixed-variant: '#384c39'
  secondary-fixed: '#dae8be'
  secondary-fixed-dim: '#becca3'
  on-secondary-fixed: '#141f05'
  on-secondary-fixed-variant: '#3f4b2c'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#f0bd8b'
  on-tertiary-fixed: '#2c1600'
  on-tertiary-fixed-variant: '#623f18'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  caption:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 80px
---

## Brand & Style

The design system is rooted in the philosophy of "Quiet Vitality." It aims to evoke a sense of calm reliability and organic growth, moving away from the aggressive, high-contrast aesthetics often found in the sports nutrition market. The target audience seeks clarity and professional guidance in their wellness journey, requiring an interface that feels like a premium apothecary rather than a discount warehouse.

The visual style is **Minimalist-Organic**. It prioritizes high-quality photography and vast amounts of white space to allow products to breathe. The interaction model is intentional and gentle, utilizing soft transitions and subtle depth to guide the user through their health choices without pressure. It emphasizes transparency and trust through refined typography and a meticulously balanced natural palette.

## Colors

The color strategy uses a low-saturation approach to maintain a relaxing atmosphere. 

- **Primary (Sage Deep):** Used for key actions, primary headings, and brand icons. It provides enough contrast for accessibility while remaining rooted in nature.
- **Secondary (Moss/Mint):** Used for subtle backgrounds, tags, and secondary button states to differentiate product categories without visual noise.
- **Backgrounds (Cream/Beige):** Replaces harsh pure whites with "Cream Base" to reduce eye strain and create a premium, paper-like feel. 
- **Accents (Earth Clay):** Reserved for highlights like "In Stock" indicators or subtle price accents, providing a warm contrast to the cooler greens.

## Typography

This system employs a classic pairing of a literary serif and a technical sans-serif to balance "Traditional Wisdom" with "Scientific Rigor."

- **Headlines:** Use **Newsreader**. The variable weights and elegant serifs communicate authority and a premium, editorial feel. Use Medium (500) weight for most headings to maintain softness.
- **Body & UI:** Use **Manrope**. Its modern, geometric construction ensures high legibility for ingredient lists and dosage instructions. 
- **Letter Spacing:** Headlines use slightly tighter tracking to feel cohesive, while labels use slightly increased tracking for clarity at smaller sizes.

## Layout & Spacing

The layout utilizes a **Fixed Grid** model for desktop to preserve the editorial composition, transitioning to a flexible fluid model for mobile devices.

- **Desktop:** 12-column grid with 24px gutters. Content is centered within a 1280px container to prevent line lengths from becoming unreadable on ultra-wide monitors.
- **Rhythm:** An 8px base unit drives all spacing. Vertical "Section Gaps" are intentionally large (80px+) to ensure the "Helpful, Not Aggressive" brand personality is felt through whitespace.
- **Mobile:** 4-column grid with 20px side margins. Cards and imagery should typically span full width or 2 columns to maintain photographic impact.

## Elevation & Depth

Depth in this design system is achieved through **Ambient Shadows** and **Tonal Layering** rather than heavy borders.

- **Shadows:** Use extremely soft, diffused shadows with a slight tint of the Primary color (Sage) to prevent them from looking "dirty" or grey. Blur radii should be high (20px-40px) with very low opacity (5-8%).
- **Tonal Layers:** Elevation is often communicated by placing a white card on a "Cream Base" background. This creates a natural hierarchy without needing physical shadows for every element.
- **Backdrop Blurs:** For navigation overlays and modals, use a light backdrop blur (8px) with a semi-transparent cream tint to maintain the sense of place and tranquility.

## Shapes

The shape language is consistently **Rounded**, avoiding sharp corners that feel clinical or aggressive. 

- **Cards & Primary Containers:** Use `rounded-lg` (16px/1rem) to create a friendly, approachable frame for product photography.
- **Buttons & Inputs:** Use `rounded` (8px/0.5rem) to provide a distinct, clickable appearance while remaining cohesive with the card language.
- **Product Tags/Badges:** Use a full pill-shape (`rounded-xl`) to distinguish them from functional UI buttons.

## Components

- **Buttons:** Primary buttons use a solid Sage Deep fill with white text. Secondary buttons use an Earth Clay outline or a subtle Mint fill. Avoid "Heavy" hover states; instead, use a slight shift in saturation or a subtle lift in shadow.
- **Cards:** Product cards feature a fixed-aspect ratio image (4:5) with a soft background tint. Text is left-aligned with ample padding (24px) to avoid a cramped feel.
- **Input Fields:** Use "Beige Accent" as the background fill for inputs rather than a border, creating a softer, more integrated look. The focus state uses a 2px Sage Deep border.
- **Chips & Tags:** Small, pill-shaped elements for attributes like "Organic," "Vegan," or "Lab Tested." Use low-contrast colors (e.g., Moss text on a Mint background).
- **Steppers & Progress:** For the checkout or health quizzes, use thin, elegant lines and soft-filled circles to track progress, maintaining the "Relaxing" brand pillar.
- **Photography:** All product images should be shot in natural light with soft shadows, often featuring "lifestyle" elements like raw ingredients or ceramic textures to reinforce the earthy brand identity.