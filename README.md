# 🍵 MORI Matcha Lab (森) — From Leaf to Ritual

> An interactive luxury digital experience and concept store celebrating the craft of stone-milled Japanese ceremonial matcha.

[![Vite](https://img.shields.io/badge/Vite-6.4.2-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-19.2.0-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🌿 Experience Overview

**MORI Matcha Lab** is a bespoke web experience exploring the tranquil, disciplined journey of single-origin tencha from harvest to the whisk. Designed with a restrained Japanese editorial sensibility, the experience balances high-resolution macro visual assets with live process telemetry, custom chapter sequencing, and a seamless concept checkout drawer.

### 🌟 Key Features

- **4-Part Interactive Narrative**:
  - **01 / The Leaf (Flash Steaming)**: 21-second steam duration, 90% humidity retention, halted oxidation.
  - **02 / The Stone (Slow Granite Milled)**: 30 g/h slow grinding rate yielding an ultra-fine 8 μm particle cloud.
  - **03 / The Ritual (Whisk The Moment)**: 78°C target temperature, 2-minute daily mindful preparation.
  - **04 / Your Matcha (Configurator)**: Interactive toggle between **Pure Ceremonial Bowl** and **Iced Matcha Latte**, updating live recipes, milk/water volumes, and telemetry in real-time.
- **Fluid Navigation & Gestures**:
  - Wheel scroll-snap navigation with intelligent throttling.
  - Keyboard arrow key navigation (`↑`, `↓`, `←`, `→`).
  - Mobile touch swipe gesture support.
  - Interactive chapter rail with direct jump controls and progress tracking.
- **Process Telemetry & Waveform Spectrum**:
  - Real-time animated audio-frequency bars visualizing the rhythm and craft of each phase.
  - Live metric gauges and data readouts.
- **Concept Store & Drawer Experience**:
  - Slide-over product drawer with interactive quantity selector (`-` / `+`).
  - Dynamic price calculation in Indian Rupee format (₹1,490 / 30g tin).
  - Bag state indicator in the header with animated feedback.
- **Story & Origins Modals**:
  - Dedicated popups detailing the philosophy (*"Less hurry. More green."*), provenance, and tea cultivation practices.

---

## 🎨 Design System & Aesthetics

- **Color Palette**:
  - Deep Botanical Moss: `#1a2218`
  - Muted Sage: `#65725e`
  - Natural Tencha Paper: `#f4f6f0`
  - Pure Ceramic Accent: `#ffffff`
- **Typography**: Clean humanist typography combined with wide-tracked micro-labels and editorial serif headlines.
- **Atmosphere**: Subtle crossfading image stacks, ambient vignette overlays, and soft glassmorphic backdrop filters.

---

## 📁 Project Structure

```
mori-matcha/
├── assets-source/            # High-resolution generated source artwork
│   ├── mori-grinder.png      # Granite mill render (source PNG)
│   └── mori-leaf.png         # Steamed tencha leaf render (source PNG)
├── reference/                # Target design reference frames
│   └── mori-reference.jpg    # Video frame capture reference
├── public/
│   └── assets/               # Production-optimized WebP assets
│       ├── grinder.webp
│       ├── latte.webp
│       └── leaf.webp
├── src/
│   ├── App.jsx               # Main interactive application & state engine
│   ├── main.jsx              # React 19 entry point
│   └── styles.css            # Scoped editorial design system & styling
├── worker/
│   └── index.js              # Serverless worker handler
├── scripts/
│   └── prepare-sites-build.mjs # Build preparation script
├── tests/
│   └── sites-worker.test.mjs # Integration test suite
├── index.html                # Main HTML entry with SEO meta tags
├── package.json
└── vite.config.mjs           # Vite build configuration
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18.0.0 or higher recommended)
- npm or pnpm / yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/rajeshkanna-s/mori-matcha.git

# Navigate into the project folder
cd mori-matcha

# Install dependencies
npm install
```

### Development Server

Run the development server locally:

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Production Build

Create an optimized production bundle:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## 🛠 Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Bundler / Dev Server**: [Vite 6](https://vitejs.dev/)
- **Iconography**: [@phosphor-icons/react](https://phosphoricons.com/)
- **Styling**: Vanilla CSS (CSS Grid, Flexbox, Keyframe Animations, Backdrop Filter)

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
