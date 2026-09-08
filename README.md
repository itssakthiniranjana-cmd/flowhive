# Flowhive - Digital Agency & Creative Services Web Platform

A replica of the **Misiom** Digital Agency & Creative Services template in **Light Mode**. Flowhive is designed for high-performance creative studios, branding agencies, and digital product consultancies.

---

## ✨ Features & Design Highlights

- **Pure Light Mode Theme**: Clean, high-contrast light theme with warm golden amber accents (`#ffa501`), crisp typography, and subtle off-white backgrounds (`#f1f3f5`).
- **Typography**: Powered by Google Fonts **Instrument Sans** (`400..700` weight range).
- **Smooth Animations & Micro-Interactions**:
  - **GSAP Suite**: `ScrollTrigger`, `SplitText`, `ScrollSmoother`, `ScrollToPlugin`, and `CustomEase` for fluid timeline-based motion.
  - **AOS (Animate On Scroll)**: Entrance animations for cards, badges, and section headers.
  - **Three.js & Hover Distortion**: WebGL-powered interactive image distortion effects.
  - **Owl Carousel**: Responsive sliders for hero showcases, client testimonials, and partner logos.
  - **Interactive Counters & Progress Bars**: Animated statistics counters and milestone numbers.
- **Complete Multi-Page Architecture**: 25 pre-built HTML5 pages covering every agency workflow.

---

## 📁 Page Structure

| Category | Pages Included |
| :--- | :--- |
| **Homepages** | [`index.html`](file:///Users/sakthinir/Flowhive/index.html) (Homepage 01 - Hero & Agency Layout)<br>[`index-2.html`](file:///Users/sakthinir/Flowhive/index-2.html) (Homepage 02 - Creative Studio Layout) |
| **About** | [`about.html`](file:///Users/sakthinir/Flowhive/about.html) (Company story, values, impact & stats) |
| **Services** | [`services.html`](file:///Users/sakthinir/Flowhive/services.html) (Services grid & capabilities)<br>[`service-d-web-development.html`](file:///Users/sakthinir/Flowhive/service-d-web-development.html) (Web Development)<br>[`service-d-visual-design-solutions.html`](file:///Users/sakthinir/Flowhive/service-d-visual-design-solutions.html) (Visual Design Solutions)<br>[`service-d-brand-identity-design.html`](file:///Users/sakthinir/Flowhive/service-d-brand-identity-design.html) (Brand Identity Design)<br>[`service-d-digital-brand-strategy.html`](file:///Users/sakthinir/Flowhive/service-d-digital-brand-strategy.html) (Digital Brand Strategy) |
| **Portfolio** | [`portfolio.html`](file:///Users/sakthinir/Flowhive/portfolio.html) (Portfolio Grid 01)<br>[`portfolio-2.html`](file:///Users/sakthinir/Flowhive/portfolio-2.html) (Portfolio Grid 02)<br>[`portfolio-details.html`](file:///Users/sakthinir/Flowhive/portfolio-details.html) (Case Study & Project Detail) |
| **Team** | [`team.html`](file:///Users/sakthinir/Flowhive/team.html) (Team members & bios)<br>[`team-details.html`](file:///Users/sakthinir/Flowhive/team-details.html) (Individual member profile) |
| **Pricing & FAQ** | [`packages.html`](file:///Users/sakthinir/Flowhive/packages.html) (Pricing tables & tiers)<br>[`faq.html`](file:///Users/sakthinir/Flowhive/faq.html) (Accordion FAQs) |
| **Blog** | [`blog.html`](file:///Users/sakthinir/Flowhive/blog.html) (Blog Grid)<br>[`blog-classic.html`](file:///Users/sakthinir/Flowhive/blog-classic.html) (Blog Classic)<br>[`blog-details.html`](file:///Users/sakthinir/Flowhive/blog-details.html) (Blog Article & Comments) |
| **E-Commerce** | [`products.html`](file:///Users/sakthinir/Flowhive/products.html) (Product Catalog)<br>[`product-details.html`](file:///Users/sakthinir/Flowhive/product-details.html) (Product Detail)<br>[`cart.html`](file:///Users/sakthinir/Flowhive/cart.html) (Shopping Cart)<br>[`checkout.html`](file:///Users/sakthinir/Flowhive/checkout.html) (Checkout Page) |
| **Utilities** | [`contact.html`](file:///Users/sakthinir/Flowhive/contact.html) (Contact Form & Map)<br>[`login.html`](file:///Users/sakthinir/Flowhive/login.html) (Authentication)<br>[`404.html`](file:///Users/sakthinir/Flowhive/404.html) (Error Page) |

---

## 🎨 Color Palette

| Token | Hex Value | Usage |
| :--- | :--- | :--- |
| `--misiom-base` | `#ffa501` | Primary Brand Amber Accent, CTA Highlights, Hover Borders |
| `--misiom-black` | `#18191c` | Primary Headings, High-Contrast Text |
| `--misiom-text` | `#797b81` | Body Text & Paragraphs |
| `--misiom-white` | `#ffffff` | Background & Clean Surface Cards |
| `--misiom-white2` | `#f1f3f5` | Subtle Section Backgrounds & Form Inputs |
| `--misiom-border-color` | `#e1e2e7` | Card Borders & Dividers |

---

## 🚀 Running Locally

You can run Flowhive with any static file server:

### Using Python:
```bash
python3 -m http.server 3000
```
Then navigate to [http://localhost:3000](http://localhost:3000).

### Using Node.js (npx serve / live-server):
```bash
npx serve . -p 3000
```

---

## 📦 Directory Structure

```
Flowhive/
├── index.html                 # Main Homepage
├── index-2.html               # Secondary Homepage
├── about.html                 # About Us
├── services.html              # Services Catalog
├── service-d-*.html           # Individual Service Detail Pages
├── portfolio.html             # Portfolio Grid
├── portfolio-details.html     # Portfolio Single Project
├── team.html                  # Team Directory
├── packages.html              # Pricing Plans
├── faq.html                   # FAQ Page
├── blog*.html                 # Blog & Articles
├── contact.html               # Contact & Inquiry
├── products.html              # Shop / Digital Assets
├── assets/
│   ├── css/                   # Main & responsive stylesheets
│   ├── js/                    # Core interactivity & custom scripts
│   ├── vendors/               # GSAP, Bootstrap, Owl Carousel, AOS, Icons
│   └── images/                # HD imagery, SVG icons, background shapes
└── README.md
```
