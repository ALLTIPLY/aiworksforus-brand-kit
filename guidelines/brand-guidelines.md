# aiworksforus Brand Guidelines

## Introduction

This document provides specific guidelines for implementing the aiworksforus brand identity across digital platforms. These guidelines ensure consistency and professionalism in all brand representations, following design standards comparable to modern AIaaS and SaaS platforms such as Stripe, Supabase, Vercel, Labelbox, Linear, and TwelveLabs.

## Logo

### Primary Logo

The aiworksforus logo consists of a logomark and wordmark that should be used according to these guidelines:

- **Light Backgrounds:** Use `logos/full-logos-for-light-backgrounds/aiworksforus_fulllogomark-02.svg`
- **Dark Backgrounds:** Use `logos/full-logos-for-dark-backgrounds/aiworksforus-full-logo-large-seasalt-01.svg`

### Logomark (Symbol Only)

When space is limited or for icon usage:
- Use `logos/aiworksforus-logomark-01.svg` or `logos/aiworksforus-logomark-large-01.png`

### Clear Space

Maintain a minimum clear space around the logo equal to the height of the "A" in the wordmark.

### Favicon and Web Clips

- Favicon: `logos/favicons/aiworksforus-favicon-01.svg`
- Web Clips: `logos/Webclips/aiworksforus-logo-webclipimage-dev-01.png`

### Improper Logo Usage

- Do not distort, rotate, or alter the proportions of the logo
- Do not change the logo colors
- Do not add effects such as shadows, gradients, or outlines
- Do not place the logo on busy backgrounds that reduce legibility
- Do not use the logo at sizes where details become illegible

## Color Palette

### Primary Colors

- **Vermilion** `#FF3B30`
  - RGB: 255, 59, 48
  - HSL: 3, 100%, 59%
  - Usage: Primary brand color, call-to-action buttons, highlights, important UI elements

- **Night** `#151517`
  - RGB: 21, 21, 23
  - HSL: 240, 5%, 9%
  - Usage: Text, backgrounds in dark mode, UI elements that need emphasis

### Secondary Colors

- **Platinum** `#D9DBE1`
  - RGB: 217, 219, 225
  - HSL: 225, 12%, 87%
  - Usage: Secondary UI elements, dividers, subtle backgrounds

- **White** `#FCFCFD`
  - RGB: 252, 252, 253
  - HSL: 240, 20%, 99%
  - Usage: Backgrounds in light mode, text on dark backgrounds

### Color Usage

- Use Vermilion sparingly for emphasis and key interactions
- Use Night for body text to ensure readability
- Use Platinum for subtle UI differentiation
- Use White for clean, minimalist backgrounds

## Typography

### Primary Font: Inter

Inter is the primary font for all aiworksforus digital products. It offers excellent readability across screen sizes and maintains a modern, professional appearance.

- **Headings:** Inter Bold/Semi-Bold (wght: 600-700)
- **Body Text:** Inter Regular (wght: 400)
- **UI Elements:** Inter Medium (wght: 500)
- **Captions/Small Text:** Inter Regular (wght: 400)

Font files: `fonts/Inter/Inter-VariableFont_opsz,wght.ttf` (use variable font when possible)

### Secondary Font: Roboto Mono

Roboto Mono should be used for code snippets, technical specifications, and where monospaced text improves readability.

- **Code Examples:** Roboto Mono Regular (wght: 400)
- **Technical Details:** Roboto Mono Light (wght: 300)

Font files: `fonts/Roboto_Mono/RobotoMono-VariableFont_wght.ttf`

### Typography Hierarchy

- **H1:** Inter Bold, 32px-40px (depending on viewport size)
- **H2:** Inter Semi-Bold, 24px-32px
- **H3:** Inter Semi-Bold, 20px-24px
- **H4:** Inter Medium, 18px-20px
- **Body:** Inter Regular, 16px
- **Small/Caption:** Inter Regular, 14px
- **Code/Technical:** Roboto Mono, 14px-16px

### Line Heights

- Headings: 1.2 to 1.3
- Body text: 1.5 to 1.6
- Code blocks: 1.4 to 1.5

## Layout & Spacing

### Grid System

Implement an 8-point grid system (with 4-point for minor adjustments) for all layouts:
- Padding and margins should be multiples of 8 (e.g., 8px, 16px, 24px, 32px, 40px)
- For fine adjustments, use multiples of 4px

### Container Widths

- Maximum content width: 1200px
- Default padding for containers:
  - Desktop: 32px
  - Tablet: 24px
  - Mobile: 16px

### Responsive Breakpoints

- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px
- Large Desktop: > 1440px

## UI Components

### Buttons

- **Primary Button:** Vermilion background with White text
- **Secondary Button:** Transparent with Vermilion border and Vermilion text
- **Tertiary Button:** No border, Vermilion text
- **Disabled Button:** Platinum background with low opacity text

Button sizes:
- Large: 48px height, 16px padding, 16px font
- Medium: 40px height, 16px padding, 14px font
- Small: 32px height, 12px padding, 14px font

Button corners should have a slight rounding (4-8px radius).

### Form Elements

- Input fields should have consistent height (40px)
- Form field labels: Inter Medium, 14px
- Light border (1px) in Platinum
- Focus state should include Vermilion highlight

### Cards & Containers

- Use subtle shadows (box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05))
- Corner radius: 8px
- Padding: 24px
- Background: White for light mode, Night for dark mode

## Imagery & Illustrations

### Style Guidelines

- Use clean, minimal illustrations that complement the brand
- Maintain consistent line weights and color usage
- Favor geometric shapes and abstract representations of AI concepts
- For photography, use high-quality, well-lit images with neutral backgrounds

## Web Animation & Interaction

### Transitions

- Default transition duration: 200-300ms
- Easing: ease-in-out or cubic-bezier(0.4, 0, 0.2, 1)
- Apply transitions to hover/active states for buttons and interactive elements

### Hover States

- Buttons: Slight darkening (10%) of background color
- Links: Underline or opacity change
- Cards: Subtle elevation change (increased shadow)

## Development Standards

### Code Quality

- Follow semantic HTML practices
- Implement responsive design using mobile-first approach
- Ensure all interactive elements are keyboard accessible
- Meet WCAG 2.1 AA standards for accessibility

### Performance Considerations

- Optimize images and assets for web
- Implement proper caching strategies
- Minimize JavaScript bundle sizes
- Prioritize Core Web Vitals metrics (LCP, FID, CLS)

## Brand Voice & Tone

- **Professional yet approachable:** Technical but not intimidating
- **Clear and concise:** Avoid jargon when possible, explain complex concepts simply
- **Helpful and solution-oriented:** Focus on how AI solves problems
- **Forward-thinking:** Emphasize innovation and possibilities

## Social Media & Marketing

### Social Media Icons

Use brand colors for social platform icons with consistent sizing:
- Large: 40px × 40px
- Medium: 32px × 32px
- Small: 24px × 24px

### Open Graph Images

For social sharing:
- Use `brand-assets/aiworksforus-og-image-001.png` as a template
- Maintain 1200 × 630px dimensions for optimal sharing

## Implementation Notes for AI Models

When implementing the aiworksforus brand for web products:

1. Start with a clean, minimalist layout that prioritizes white space
2. Implement the color system with Vermilion as accent color, not dominant
3. Follow typography hierarchy strictly to maintain professional appearance
4. Ensure all interactive elements have proper states (hover, focus, active)
5. Maintain consistency in spacing using the 8-point grid system
6. Optimize for all devices following responsive breakpoints
7. Ensure dark mode implementation respects color guidelines
8. Apply subtle animations for state changes and loading states
9. Maintain visual consistency between website and web application

By following these guidelines, AI models building aiworksforus digital products will create a cohesive, modern experience consistent with premium AI and SaaS platforms in the industry. 