# Marcus Vane — Founder & Venture Portfolio

A bespoke, high-performance executive portfolio designed with an editorial brutalist and fluid luxury aesthetic. Built for bold founders, technologists, and investors who demand cinematic presentation and flawless motion design.

---

## ✨ Features

- **Cinematic Hero with Transparent Alpha Video**: Features an isolated, alpha-channel VP9 WebM video (`Man_1_no_bg.webm`) layered directly in front of oversized condensed typography, creating depth without solid rectangular video borders.
- **Organic Liquid SVG Distortion**: Custom SVG `feDisplacementMap` and `feTurbulence` filters with spring-physics ripple animations responding dynamically to hover and touch gestures.
- **Editorial Brutalism Aesthetic**: Deep dark obsidian palette (`#08080a`), high-contrast fiery accent (`#ff3b1d`), refined serif headings, and ultra-condensed display typography.
- **Selected Ventures & Case Studies**: Grid and list showcases for portfolio companies, track records, metrics, and venture investments.
- **Operating Principles & Marquee**: Infinite kinetic ticker communicating philosophy, culture, and core beliefs.
- **Inertial Smooth Scrolling**: Powered by [Lenis](https://lenis.darkroom.engineering/) for 60fps momentum-based navigation.
- **Responsive & Accessible**: Strict semantic HTML5, ARIA labels, responsive typography, and mobile-optimized layouts.

---

## 🛠 Tech Stack

- **Runtime & Bundler**: [Vite](https://vitejs.dev/) with Hot Module Replacement (HMR)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Languages**: TypeScript / Modern JavaScript (ES6+), HTML5, CSS3
- **Media & Effects**: WebM VP9 with Alpha channel, SVG Filters, HTML5 Canvas fallback

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (v18 or higher) and `npm` installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/marcus-vane-portfolio.git
   cd marcus-vane-portfolio
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the local development server:
   ```bash
   npm run dev
   ```
   Open your browser and navigate to `http://localhost:3000`.

### Production Build

To build the static production bundle:
```bash
npm run build
```

To preview the production build locally:
```bash
npm run preview
```

---

## 📂 Project Structure

```
.
├── index.html              # Main HTML entry point and interactive scripts
├── package.json            # Project dependencies and npm scripts
├── public/
│   └── assets/
│       └── aistudio/
│           ├── Man_1_no_bg.webm       # Transparent background VP9 hero video
│           ├── Man_1_poster.webp      # Transparent poster preview image
│           └── ...                    # Additional media assets
├── src/                    # Source code, styles, and components
└── tsconfig.json           # TypeScript configuration
```

---

## 📬 Contact

- **Email**: [dxhieu97@gmail.com](mailto:dxhieu97@gmail.com)
- **Website**: [marcusvane.com](https://marcusvane.com)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
