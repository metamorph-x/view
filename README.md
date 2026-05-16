<p align="center">
  <img src="https://img.shields.io/badge/Metamorph--X-Engineering%20Evolution-00D2FF?style=for-the-badge&labelColor=0B0F19" alt="Metamorph-X Badge"/>
</p>

<h1 align="center">⚡ Metamorph-X</h1>

<p align="center">
  <strong>Engineering Evolution. Transforming Ideas.</strong><br>
  A premium, dark-themed single-page portfolio website for a forward-thinking tech collective.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Font_Awesome-528DD7?style=flat-square&logo=fontawesome&logoColor=white" alt="Font Awesome"/>
  <img src="https://img.shields.io/badge/Google_Fonts-4285F4?style=flat-square&logo=googlefonts&logoColor=white" alt="Google Fonts"/>
  <img src="https://img.shields.io/badge/Responsive-100%25-00D2FF?style=flat-square" alt="Responsive"/>
</p>

---

## 📖 Overview

**Metamorph-X** is an ultra-modern, high-end single-page portfolio website designed for a developer-centric tech collective. Built with pure HTML5, CSS3, and minimal vanilla JavaScript — no frameworks, no build tools, no dependencies beyond CDN-hosted fonts and icons.

The design follows a **Dark Cyber** aesthetic with glassmorphism effects, gradient accents, scroll-reveal animations, and premium hover interactions — all crafted to feel polished, professional, and production-ready.

---

## ✨ Features

### 🎨 Design & Visual
- **Dark Cyber Color Palette** — Deep tech dark (`#0B0F19`), electric neon cyan/blue (`#00D2FF` / `#0072FF`), crisp white headers, slate gray body text
- **Glassmorphism** — Semi-transparent card backgrounds with `backdrop-filter: blur(20px)` and subtle luminous borders
- **Gradient Text** — Key headings use a cyan-to-blue gradient via `background-clip: text`
- **CSS Grid Pattern Overlay** — Faint grid lines across the viewport for a developer-centric aesthetic
- **Radial Glow Orbs** — Decorative gradient orbs strategically placed behind sections for depth
- **Syntax-Highlighted Code Block** — A styled JSON/JS code block in the About section showcasing the team's philosophy

### ⚙️ Technical
- **Zero Build Tools** — Open `index.html` in any browser and it just works
- **100% Responsive** — Flawless rendering on mobile, tablet, and desktop (breakpoints at `1080px`, `900px`, `768px`, `600px`)
- **CSS Flexbox + Grid** — Modern layout system used throughout
- **CSS Custom Properties** — Centralized design tokens for colors, spacing, shadows, transitions, and radii
- **Intersection Observer API** — Lightweight scroll-reveal animations triggered as elements enter the viewport
- **Staggered Animation Delays** — Child elements within grids animate in sequence for a cascading reveal effect
- **Minimal JavaScript** (~40 lines) — Only used for mobile nav toggle, scroll reveal, and header shadow on scroll

### 🖱️ Interactions & Hover Effects
- **Navigation Links** — Subtle background highlight on hover
- **CTA Buttons** — Primary button with glow intensification + lift; outline button with border color shift + lift
- **Pillar Cards** — Vertical lift (`translateY(-8px)`), border glow, gradient top-bar reveal, icon scale-up
- **Team Cards** — Vertical lift, border glow, expanding gradient top-bar, avatar scale + glow, social links slide-in from below
- **Footer Social Icons** — Lift + color shift + border glow
- **About Feature Items** — Subtle background tint + icon glow on hover
- **Contact Link Cards** — Lift + border/background color transition

---

## 🏗️ Project Structure

```
metamorph-x/
├── index.html          # Main HTML document (all sections + inline JS)
├── style.css           # Complete stylesheet (1,200+ lines of organized CSS)
└── README.md           # Project documentation (this file)
```

No build process. No `node_modules`. No configuration files. Pure web fundamentals.

---

## 📑 Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Navbar** | Sticky glass-blur header with logo, navigation links, glowing CTA, and mobile hamburger menu with full-screen overlay |
| 2 | **Hero** | Full-viewport hero with animated pulse badge, two-line gradient headline, subtitle, dual CTA buttons, and 4-stat metrics strip |
| 3 | **About** | Two-column grid — left side: vision text + 3 feature items with icons; right side: syntax-highlighted code card + floating "Production Ready" badge |
| 4 | **Core Pillars** | 3-card responsive grid — Architectural Excellence, Community & Impact, AI & Innovation — with icons, descriptions, and tech tags |
| 5 | **Team** | 5-member responsive grid — gradient initial avatars, role tags, descriptions, and hover-reveal social links |
| 6 | **Contact** | Centered glass card with headline, dual CTAs, and 4 social platform link cards |
| 7 | **Footer** | Logo, 5 social icon links, copyright text, and "Back to top" link |

---

## 👥 Team Members

| Name | Role | Focus |
|------|------|-------|
| **Kaium Ahmed** | Project Lead | Product strategy, system design, cross-team alignment |
| **Moktadur Rahman** | Core Developer | API design, database optimization, cloud infrastructure |
| **Tofayel Ahmed** | Core Developer & QA | Full-stack development, testing, quality assurance |

<!--
| **Shahriar Ahmed** | UI/UX & Frontend | Interface design, pixel-perfect implementation, user experience |
| **Toybur Rahman** | Operations & Deployment | CI/CD pipelines, cloud deployments, production reliability |
--->

---

## 🎨 Design Tokens

The entire design system is managed through CSS custom properties defined in `:root`:

```css
/* Colors */
--bg-primary:       #0B0F19       /* Deep dark background         */
--bg-secondary:     #101624       /* Alternate section background  */
--bg-card:          rgba(16, 22, 36, 0.65)  /* Glass card fill   */
--accent-cyan:      #00D2FF       /* Primary accent color          */
--accent-blue:      #0072FF       /* Secondary accent color        */
--white:            #FFFFFF       /* Headlines                     */
--text-primary:     #E2E8F0       /* Body text                     */
--text-secondary:   #94A3B8       /* Subdued text                  */
--text-muted:       #64748B       /* Muted/caption text            */

/* Typography */
--font-body:        'Inter', sans-serif
/* Code blocks:     'JetBrains Mono', monospace */

/* Transitions */
--transition-fast:  0.2s cubic-bezier(0.4, 0, 0.2, 1)
--transition-base:  0.35s cubic-bezier(0.4, 0, 0.2, 1)
--transition-slow:  0.5s cubic-bezier(0.4, 0, 0.2, 1)

/* Border Radii */
--radius-sm: 8px  |  --radius-md: 14px  |  --radius-lg: 20px  |  --radius-xl: 28px
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Target | Key Changes |
|------------|--------|-------------|
| `≤ 1080px` | Small desktop / large tablet | Team grid → 3 columns |
| `≤ 900px` | Tablet | Pillars grid → 2 columns; About section → single column (stacked) |
| `≤ 768px` | Small tablet / large phone | Mobile nav hamburger visible; Team grid → 2 columns; Reduced section padding |
| `≤ 600px` | Mobile | Pillars → single column; Team → single column; CTA buttons → full-width stacked |

---

## 🚀 Getting Started

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/metamorph-x/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   ```bash
   # Simply open the file — no server required
   open index.html
   
   # Or use any local server
   npx serve .
   python -m http.server 8000
   php -S localhost:8000
   ```

3. **That's it.** No installation, no build step, no configuration.

### VS Code Live Preview

If you're using VS Code, install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension and click **"Go Live"** in the status bar for hot-reloading during development.

---

## 🛠️ Customization Guide

### Changing Colors
Update the CSS custom properties in `:root` at the top of `style.css`. All colors, gradients, borders, and glows reference these variables — change once, update everywhere.

### Changing Typography
Replace the Google Fonts `<link>` tag in `index.html` and update `--font-body` in `style.css`.

### Adding Team Members
Duplicate any `.team-card` block in the Team section of `index.html`. Update the initials in `.team-avatar`, the name, role tag, and description. The CSS grid will automatically accommodate additional members.

### Modifying Sections
Each section is clearly commented in both `index.html` and `style.css` with section headers for easy navigation.

---

## 🧰 External Dependencies (CDN)

| Resource | Version | Purpose |
|----------|---------|---------|
| [Google Fonts — Inter](https://fonts.google.com/specimen/Inter) | Variable | Primary body typography |
| [Google Fonts — JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) | Variable | Code block typography |
| [Font Awesome](https://fontawesome.com/) | 6.5.1 | Icon library (solid, brands) |

All resources are loaded via CDN — no local font files or icon sprites required.

---

## 📄 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full (with `-webkit-` prefixes for `backdrop-filter`) |
| Edge | ✅ Full |
| Opera | ✅ Full |
| Mobile Safari (iOS) | ✅ Full |
| Chrome Mobile (Android) | ✅ Full |

> **Note:** `backdrop-filter` (glassmorphism) gracefully degrades in older browsers — cards will render with a solid semi-transparent background instead.

---

## 📐 Architecture Decisions

- **No CSS frameworks** — Every style is purpose-written for maximum control and zero bloat
- **No JavaScript frameworks** — Vanilla JS with Intersection Observer for scroll animations keeps the bundle at near-zero
- **CSS Custom Properties over Sass** — Native browser support, no compilation needed, runtime-modifiable
- **Semantic HTML5** — Proper use of `<header>`, `<main>`, `<section>`, `<nav>`, `<footer>` for accessibility and SEO
- **Progressive Enhancement** — The page is fully readable and navigable without JavaScript; animations are purely additive

---

## 📊 Performance

- **0 build dependencies**
- **2 files** total (HTML + CSS)
- **~40 lines** of JavaScript
- **No images** — all visuals are CSS-generated (gradients, borders, shadows, patterns)
- **Font preconnect** hints for faster Google Fonts loading
- **Hardware-accelerated animations** — using `transform` and `opacity` for 60fps transitions

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  <br>
  <strong>Built with precision by the Metamorph-X Collective</strong><br>
  <sub>Engineering Evolution. Transforming Ideas.</sub>
  <br><br>
  <img src="https://img.shields.io/badge/Made_with-❤️_&_Code-0B0F19?style=for-the-badge&labelColor=0B0F19&color=00D2FF" alt="Made with Love & Code"/>
</p>
