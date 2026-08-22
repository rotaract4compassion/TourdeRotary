---
name: Athletic Editorial
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
  on-surface-variant: '#424750'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#737781'
  outline-variant: '#c2c6d2'
  surface-tint: '#2b5fa1'
  primary: '#00305f'
  on-primary: '#ffffff'
  primary-container: '#004687'
  on-primary-container: '#87b6fe'
  inverse-primary: '#a7c8ff'
  secondary: '#825500'
  on-secondary: '#ffffff'
  secondary-container: '#feae23'
  on-secondary-container: '#6b4500'
  tertiary: '#650025'
  on-tertiary: '#ffffff'
  tertiary-container: '#8f0037'
  on-tertiary-container: '#ff95a8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3b'
  on-primary-fixed-variant: '#014788'
  secondary-fixed: '#ffddb3'
  secondary-fixed-dim: '#ffb950'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#624000'
  tertiary-fixed: '#ffd9de'
  tertiary-fixed-dim: '#ffb2be'
  on-tertiary-fixed: '#400014'
  on-tertiary-fixed-variant: '#900038'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-hero:
    fontFamily: Anton
    fontSize: 96px
    fontWeight: '400'
    lineHeight: 90%
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 100%
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 100%
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 120%
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 160%
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 150%
  label-ui:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 100%
    letterSpacing: 0.05em
  data-metric:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 100%
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  diagonal-offset: 12deg
---

## Brand & Style

The design system is a fusion of elite performance and coastal vitality. It balances the precision of professional cycling editorial with the warmth of the Dar es Salaam golden hour. The personality is premium yet grassroots, evoking a sense of communal achievement and athletic rigor.

The aesthetic utilizes **High-Contrast / Bold** layouts characterized by:
- **Asymmetric Composition:** Breaking the standard grid with diagonal content flows and overlapping elements.
- **Large-Scale Media:** Edge-to-edge photography and video of the Tanzanian coastline and active participants.
- **Dynamic Graphics:** Integrating the Wave Pattern (IMAGE_5) as a structural background element or a transitional mask between sections.
- **Performance Editorial:** Utilizing heavy, condensed typography that feels fast and impactful, reminiscent of high-end sports journalism.

## Colors

The palette is built on high-contrast relationships to ensure visibility in both outdoor sun and high-end digital environments.

- **Royal Navy (Primary):** Used for deep backgrounds, heavy headers, and primary UI containers to establish stability and prestige.
- **Gold (Action/Premium):** Reserved for primary calls to action (CTAs), registration highlights, and winner/leaderboard status.
- **Cranberry Pink (Charity):** Represents the Rotaract and "Pink Ribbon" cause; used for fundraising indicators and social impact sections.
- **White (Canvas):** The primary background color to maintain a clean, airy feel that allows photography to breathe.
- **Black (Detail):** Used for maximum-legibility body text and grounding architectural details.

## Typography

Typography is a tool for impact. Display faces utilize **Anton** for an aggressive, athletic feel, while **Hanken Grotesk** provides a clean, modern contrast for information-dense areas.

- **Editorial Headers:** Use Anton with tight leading. Headlines should often be italicized or rotated on a 5-degree axis to suggest motion.
- **UI & Dashboard:** Use Hanken Grotesk for its readability and wide range of weights.
- **Technical Metrics:** Use JetBrains Mono for race times, distances, and technical data to provide a "stopwatch" precision aesthetic.
- **Contrast:** Large display text should frequently overlap high-contrast image boundaries (white text on dark areas of a photo).

## Layout & Spacing

This design system rejects the standard "centered container." It uses a **Fluid Asymmetric Grid** to create a sense of velocity.

- **Diagonal Flow:** Sections are separated by diagonal clips (12-degree angle) rather than horizontal lines, mirroring the energy of the cycling route.
- **Broken Grid:** Images and text blocks should partially overlap. A 12-column grid is used, but content frequently spans odd numbers (e.g., a 7-column image offset by a 4-column text block).
- **Responsive Behavior:** 
  - **Desktop:** Large white space margins (64px) with staggered vertical positioning.
  - **Tablet:** Content collapses to 8 columns; overlaps are simplified to stacked layers.
  - **Mobile:** Single column flow, but maintaining the diagonal section dividers and the use of the wave pattern to provide depth.

## Elevation & Depth

Depth is achieved through **Hard Layering** rather than soft shadows.

- **Stacking:** Use z-index layering where text blocks sit on top of images with high-contrast background fills (e.g., White text on a Royal Navy block that sits over a photo).
- **Cut-outs:** The Rotary Gear (IMAGE_1) can be used as a large-scale, low-opacity background watermark (10% opacity) or as a hard-edged mask for imagery.
- **Borders:** Instead of shadows, use 1px or 2px solid borders in Gold or Black to define active states or high-priority data containers.
- **Parallax:** Utilize slight parallax on the Wave Pattern (IMAGE_5) during scrolling to create a sense of moving through water.

## Shapes

The shape language is **Sharp (0)**. 

To maintain the high-performance athletic aesthetic, all buttons, containers, and image masks utilize 90-degree corners. The only curves present in the design should come from the brand assets: the Rotary Gear (IMAGE_1) and the Wave Pattern (IMAGE_5). This contrast between rigid UI structure and fluid organic brand elements creates a sophisticated, modern tension.

## Components

### Buttons
- **Primary:** Solid Gold background, Black uppercase Anton text. Sharp corners. Hover state: Shift to Royal Navy with White text.
- **Secondary:** Transparent with 2px Royal Navy border. Bold Hanken Grotesk text.
- **Charity CTA:** Solid Cranberry Pink background with White text.

### Cards & Containers
- **Avoid Box-Stacking:** Do not use cards with shadows. Instead, use background color blocks (Royal Navy or Off-White) that extend to one edge of the screen, creating an intentional asymmetric look.
- **Image Containers:** Use the diagonal clip-path on the bottom or top edge of large images to maintain the "route" aesthetic.

### Navigation
- **Header:** Sticky, high-contrast. Use the Rotary Wordmark (IMAGE_2) on the left. Navigation links in JetBrains Mono.
- **Mobile Menu:** Full-screen Royal Navy overlay with large Anton typography for navigation links.

### Input Fields
- **Style:** Underline only (2px Black or Navy) rather than a full box. Labels in JetBrains Mono positioned above the line.

### Data Visualization
- **Race Stats:** Large Anton numbers. Use Gold for "Personal Best" and Cranberry Pink for "Impact/Donation" metrics.