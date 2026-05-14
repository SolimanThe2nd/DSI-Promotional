# DSI-Technology: Brand Identity & Web Design Guidelines v1.0
**For Front-End Developers and UI/UX Designers**

This document serves as the foundational design system for DSI-Technology (Data, Science, and Innovation). It provides the necessary specifications to build out our promotional website and initial digital assets, ensuring a consistent, authoritative, and forward-looking brand presence.

---

## 1. Brand Core & Persona
DSI-Technology is positioned at the intersection of complex digital transformation and business model innovation. Our clients are large organizations undergoing systemic shifts through AI and cloud integration. 

* **Tone of Voice:** Authoritative, visionary, precise, and strategic. We do not use tech jargon for the sake of it; we focus on measurable performance, seamless service enablement, and clear strategic objectives.
* **Visual Vibe:** Institutional trust meets cutting-edge agility. The design must feel secure enough for high-stakes enterprise or public-sector operations, yet modern enough to signal true innovation.

---

## 2. Color Palette (The "Enterprise Innovator")
This palette bridges the gap between secure data handling (Navy/Slate) and disruptive technology (Cyan/Violet).

### Primary Colors (The 60% - Backgrounds & Base)
* **Crisp White:** `#FFFFFF` (Primary background for maximum readability of complex data)
* **Light Slate:** `#F8FAFC` (Secondary background to separate content blocks softly)

### Secondary Colors (The 30% - Structure & Typography)
* **Deep Navy:** `#0A192F` (Primary text, headers, footers, and navigation bars. Conveys stability and deep structural expertise.)
* **Graphite:** `#334155` (Secondary text, subtitles, and less critical UI borders.)

### Accent Colors (The 10% - Interaction & Highlighting)
* **Electric Cyan:** `#00E5FF` (Primary Action Color. Used for 'Get Started' buttons, active links, and highlighting key performance indicators.)
* **Midnight Violet:** `#4C1D95` (Secondary Accent. Used sparingly for hover states or gradient transitions in hero sections to represent AI integration.)

---

## 3. Typography System
To maintain readability across dense technical reports and promotional copy, we use a clean, geometric sans-serif pairing.

* **Primary Font (Headings):** `Inter` or `Montserrat`
    * *Usage:* H1, H2, H3, and button text.
    * *Weight:* Semi-Bold (600) to Bold (700). Letter-spacing slightly tightened (-0.02em) for a sleek tech feel.
* **Secondary Font (Body):** `Roboto` or `Open Sans`
    * *Usage:* Paragraphs, lists, data tables, and captions.
    * *Weight:* Regular (400) for standard body, Medium (500) for emphasis.
    * *Line Height:* 1.6 for optimal readability on screens.

---

## 4. UI Component Guidelines

### Buttons & Call-to-Actions (CTAs)
* **Shape:** Sharp edges with a very subtle border radius (e.g., `border-radius: 4px;`). Avoid fully pill-shaped (rounded) buttons; a slightly squared look feels more precise and engineered.
* **Primary Button:** Electric Cyan background (`#00E5FF`), Deep Navy text (`#0A192F`). No borders.
* **Secondary Button:** Transparent background, 2px Deep Navy (`#0A192F`) border, Deep Navy text.

### Cards & Containers
* **Style:** Flat design with subtle drop shadows (`box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);`) on hover to indicate interactivity.
* **Borders:** 1px solid Light Slate (`#E2E8F0`).

### Data Visualization
* All charts, graphs, and dashboard previews must use the brand palette. Do not use default charting library colors.
* Avoid 3D charts or heavy gradients. Stick to flat, clean lines and area graphs to represent data and science.

---

## 5. Imagery & Photography Direction
* **Subject Matter:** Focus on high-level enterprise architecture, abstract data nodes, cloud server environments, and professional teams engaged in strategic planning. 
* **Lighting:** Crisp, cool lighting. Avoid warm/yellow-tinted stock photos.
* **Treatment:** When overlaying text on images, use a Deep Navy (`#0A192F`) overlay at 60-70% opacity to ensure the text remains accessible and readable.

---

## 6. CSS Variables (Developer Quick-Start)
Copy and paste this into your global stylesheet:

```css
:root {
  /* Brand Colors */
  --color-primary-bg: #FFFFFF;
  --color-secondary-bg: #F8FAFC;
  --color-text-main: #0A192F;
  --color-text-muted: #334155;
  --color-accent-cyan: #00E5FF;
  --color-accent-violet: #4C1D95;

  /* Typography */
  --font-heading: 'Inter', sans-serif;
  --font-body: 'Roboto', sans-serif;

  /* UI Variables */
  --radius-sm: 4px;
  --radius-md: 8px;
  --shadow-subtle: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
  --shadow-hover: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
}
```
