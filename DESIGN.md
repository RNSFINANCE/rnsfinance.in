---
name: RNS Finance Design System
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
  on-surface-variant: '#43474f'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#002507'
  on-tertiary: '#ffffff'
  tertiary-container: '#003d11'
  on-tertiary-container: '#36b24e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#83fc8e'
  tertiary-fixed-dim: '#66df75'
  on-tertiary-fixed: '#002106'
  on-tertiary-fixed-variant: '#00531a'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max-width: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style
The brand personality is rooted in institutional stability, precision, and unwavering security. Designed for a financial portal, the UI evokes a sense of "digital vault" reliability—calm, organized, and transparent.

The design style follows a **Corporate / Modern** aesthetic. It prioritizes clarity and functional hierarchy over decorative elements. By utilizing generous white space, structured grids, and a conservative color palette, the design system ensures that complex loan data remains accessible and stress-free for the user. Every interaction is designed to feel deliberate and secure, reinforcing the user's trust in the institution.

## Colors
The palette is dominated by **Deep Trust Blue**, used for primary actions, navigation, and headers to establish authority. **Clean White** serves as the primary canvas, ensuring maximum legibility and a sense of openness.

**Professional Gold** is reserved for high-value highlights, premium status indicators, and subtle accents that signify quality and attention to detail. **Success Green** is used strictly for positive status updates, such as approved applications or completed EMI payments. Neutral grays are utilized for secondary text and borders to maintain a low-friction visual hierarchy.

## Typography
This design system utilizes **Inter** for all typographic roles. Its systematic and utilitarian nature provides the precision required for financial data while maintaining a modern, approachable feel.

Headlines use tighter letter spacing and heavier weights to command attention and provide structure. Body text is optimized for readability with generous line heights, ensuring that long-form loan terms and disclosures are easily digestible. Label styles are used for data tags, table headers, and small metadata, often employing medium-to-semibold weights to maintain visibility at smaller scales.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop to ensure a consistent, structured viewing experience for data-heavy dashboards. On mobile devices, the system transitions to a fluid model with 16px side margins.

A strict 8px spacing scale governs all internal padding and margins. Dashboard layouts should utilize a 12-column grid for desktop, allowing for flexible arrangements of loan summary cards (4 columns), application forms (8 columns), and full-width data tables (12 columns). Horizontal white space is prioritized to prevent the interface from feeling "crowded," which can induce anxiety in financial contexts.

## Elevation & Depth
Visual hierarchy is established using **Tonal Layers** and **Ambient Shadows**. The background uses a very light neutral tint to allow white "containers" (cards and modules) to pop forward.

Shadows are used sparingly and are extremely diffused (e.g., Blur: 12px, Opacity: 4-6%, Y-Offset: 4px). This creates a subtle sense of elevation that suggests physical papers or files on a desk without being distracting. Interactive elements like buttons and active input fields receive a slightly more pronounced shadow upon hover to provide tactile feedback, reinforcing the security of the interaction.

## Shapes
The shape language is defined by **Rounded** corners, specifically an 8px (0.5rem) base radius. This specific curvature is "soft" enough to feel modern and user-friendly, yet "sharp" enough to maintain a professional, institutional aesthetic.

- **Standard Elements:** 8px (buttons, inputs, checkboxes).
- **Containers:** 16px (cards, modal windows, dashboard widgets).
- **Status Badges:** Fully rounded (pill-shaped) to distinguish them from interactive buttons.

## Components

### Buttons
Primary buttons utilize the Deep Trust Blue with white text, featuring 8px rounded corners. The secondary button uses a thin 1px border in the same blue. Action buttons for "Apply Now" or "Pay EMI" may utilize Gold accents to draw immediate attention.

### Input Fields
Fields are designed with a white background and a light gray border. On focus, the border transitions to Deep Trust Blue with a subtle outer glow. Labels are always positioned above the field for maximum clarity.

### Data Tables
EMI tracking and payment histories are housed in clean, borderless tables. Alternate rows utilize a subtle light gray fill. Headers are rendered in `label-md` using Deep Trust Blue to ensure the data columns are clearly defined.

### Status Badges
Status indicators (e.g., "Pending," "Approved," "Disbursed") use low-saturation background tints with high-saturation text for readability. For example, a "Success" badge uses a pale green background with Success Green text.

### Loan Summary Cards
Cards use 16px corner radii and subtle ambient shadows. They are used to highlight key metrics like "Total Outstanding," "Next Due Date," and "Current ROI," utilizing the Gold accent for the numerical figures.

### Contact Footer
Consistent footer modules must display the corporate address and contact details clearly, using `body-sm` typography to maintain a professional, non-intrusive presence.