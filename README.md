# 🏋️ IronFit Gym – Modern Fitness Landing Page

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive Design](https://img.shields.io/badge/Responsive-Mobile--First-success?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![Zero JS Required](https://img.shields.io/badge/Zero--JS-Core_Interactions-orange?style=for-the-badge)](#-pure-css-features)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-6.5.0-538DD5?style=for-the-badge&logo=fontawesome&logoColor=white)](https://fontawesome.com/)

**IronFit Gym** is a sleek, modern, and high-performance landing page crafted for modern fitness clubs, gyms, and personal trainers. Built with semantic HTML5 and vanilla CSS3, it offers an engaging dark-mode aesthetic with vibrant crimson accents, smooth animations, and a fully responsive layout across all device viewports.

---

## 📸 Preview & Highlights

- **Aesthetic**: Premium dark theme (`#0b0b0b`) complemented by energetic crimson highlights (`#e63946`).
- **Typography**: Clean, geometric sans-serif typeface powered by [Google Fonts (Inter)](https://fonts.google.com/specimen/Inter).
- **Navigation**: Fixed glassmorphism navbar with `backdrop-filter: blur(12px)` and animated hover indicators.
- **Interactivity**: 100% pure CSS interactive components (mobile navigation toggle, FAQ accordion, hover cards).

---

## ✨ Key Features & Sections

| Section | Description | Key Elements |
| :--- | :--- | :--- |
| **🧭 Fixed Header & Nav** | Responsive navigation bar with brand logo, smooth-scroll menu anchors, and a "Join Now" CTA button. | Glassmorphism backdrop, animated link underline, sticky positioning. |
| **⚡ Hero Section** | High-impact headline, primary & outline CTAs, gym statistics, and featured hero imagery. | Centered content, 3-column stat layout on desktop, gradient button styling. |
| **🏢 About IronFit** | Brand backstory, facility value proposition, and key perk checklist. | 2-column layout (image left, text right), feature icons with hover effects. |
| **🔥 Classes & Services** | Dynamic service cards showcasing Cardio Blast, Strength & Power, HIIT Express, Aqua Fit, and Cycle Rhythm. | 3-column responsive grid, hover lift animations, accent card borders. |
| **⭐ Why Choose Us** | Feature highlights covering progress tracking apps, certified coaches, flexible scheduling, and community support. | Icon + text layout, subtle hover glows, clean typography. |
| **💬 Testimonials** | Real member reviews with 5-star ratings, testimonials, and styled member portrait avatars with glowing hover rings. | 3-column testimonial grid, circular avatars, star rating display. |
| **💳 Membership Pricing** | Tiered pricing cards (**Basic** `$39/mo`, **Pro (Featured)** `$69/mo`, **Elite** `$99/mo`) detailing tier benefits. | Featured "Most Popular" card styling, consistent pricing table layout. |
| **❓ Interactive FAQ** | Accordion FAQ answering common questions about gym hours, trial passes, trainers, and cancellation policy. | Native HTML5 `<details>/<summary>`, custom chevrons, smooth reveal transitions. |
| **📬 Contact & Location** | Gym address, phone, email, operating schedule, and an integrated inquiry submission form. | Stacked 2-column form, field labels with placeholder support. |
| **⚓ Footer** | Social media channels (Facebook, Instagram, YouTube, TikTok, Twitter), quick navigation links, legal links, and copyright notices. | 4-column grid layout, social icon links, bottom footer bar. |

---

## 🎨 Design System & Color Palette

IronFit utilizes CSS Custom Properties (`:root` variables) for modular theming and maintainability:

```css
:root {
  /* Surface Colors */
  --color-bg-primary: #0b0b0b;
  --color-bg-secondary: #111111;
  --color-bg-card: #161616;
  --color-bg-nav: rgba(11, 11, 11, 0.92);
  --color-bg-popular: #1a1012;

  /* Accent & Status */
  --color-accent: #e63946;
  --color-accent-hover: #c62836;
  --color-star: #f5c518;

  /* Text Colors */
  --color-text-primary: #f0f0f0;
  --color-text-secondary: #aaaaaa;
  --color-text-muted: #888888;
  --color-text-body: #bbbbbb;

  /* Layout & Radii */
  --container-max: 1200px;
  --radius-card: 20px;
  --radius-btn: 50px;
}
```

---

## 💡 Pure CSS & Semantic Highlights

- **Zero-JS Mobile Hamburger Menu**: Powered by the [CSS Checkbox Hack](https://css-tricks.com/the-checkbox-hack/) (`#menu-toggle:checked ~ .nav-links`), providing smooth slide/fade mobile drawer navigation with zero external script dependencies.
- **Native Accordion FAQ**: Implemented using semantic HTML5 `<details>` and `<summary>` tags, fully styled with custom expand/collapse chevrons and smooth reveal transitions.
- **Micro-Interactions**: Hover elevations (`translateY`), button glow shadows (`--shadow-accent`), and responsive card grids using CSS Grid `repeat(auto-fit, minmax(...))`.
- **Form Usability**: Optimized contact input fields with `16px` font sizing on mobile screens to prevent automatic zoom on iOS Safari.

---

## 📁 File Structure

```
IronFit/
│
├── assets/
│   ├── css/
│   │   └── style.css            # Core stylesheet, animations, and responsive media queries
│   │
│   └── images/
│       ├── hero-image.jpg       # Main hero banner image
│       ├── about-image.jpg      # Facility and training overview photo
│       ├── member1.jpg          # Testimonial avatar (Michael R.)
│       ├── member2.jpg          # Testimonial avatar (Sarah K.)
│       └── member3.jpg          # Testimonial avatar (James L.)
│
├── index.html                   # Semantic HTML5 landing page
└── README.md                    # Project documentation
```

---

## 🚀 Quick Start / How to Run

Because IronFit is built with standard web technologies without build steps or bundlers, you can run it immediately in any browser:

### Option 1: Direct File Open
1. Clone or download this repository to your local machine.
2. Double-click [index.html](index.html) or right-click and choose **Open with > Chrome / Firefox / Edge / Safari**.

### Option 2: Live Server (VS Code Extension)
1. Open the `IronFit` directory in VS Code.
2. Right-click [index.html](index.html) and select **"Open with Live Server"**.
3. The page will launch automatically at `http://127.0.0.1:5500/index.html`.

### Option 3: Python Local HTTP Server
Run the following command in the project root:
```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

---

## 📱 Responsive Breakpoints

IronFit is engineered with a responsive layout strategy catering to all screen categories:

| Breakpoint | Target Device | Layout Adjustments |
| :--- | :--- | :--- |
| **`> 992px`** | Desktop / Laptops | 2-column Hero & About, full horizontal navigation, multi-column grids. |
| **`≤ 992px`** | Tablets & Small Laptops | Adjusted font scaling, stacked hero/about containers, optimized card paddings. |
| **`≤ 768px`** | Tablets & Large Handhelds | Mobile drawer menu toggled via hamburger icon, single/dual column grids, stacked contact form. |
| **`≤ 480px`** | Mobile Phones | Full-width touch-friendly CTA buttons, single-column vertical flow, compact stats grid. |

---

## 🛠️ Built With

- **Markup**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- **Styling**: [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) (Flexbox, Grid, Custom Properties, Animations)
- **Icons**: [Font Awesome 6.5.0](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css)
- **Typography**: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)

---

## 👨‍💻 Developer

**Haitham Abu Draz**

[![GitHub](https://img.shields.io/badge/GitHub-HaithamAbuDraz-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HaithamAbuDraz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-haithamabudraz-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haithamabudraz/)

- **GitHub**: [@HaithamAbuDraz](https://github.com/HaithamAbuDraz)
- **LinkedIn**: [Haitham Abu Draz](https://www.linkedin.com/in/haithamabudraz/)

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for full details.

Copyright (c) 2026 **Haitham Abu Draz**.

