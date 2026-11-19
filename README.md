# Techfest IIT Bombay 2026 — Cyborg & Aetherial Renaissance Edition

A futuristic, single-file responsive landing page built for **Techfest IIT Bombay 2026**, themed around the **Cyborg & Aetherial Renaissance**. Designed with zero build-step complexity—drop `index.html` into VS Code, open it directly in a browser or via Live Server, and deploy to GitHub Pages, Vercel, or Netlify in seconds.

> **Live Demo:** `[Add your GitHub Pages / Vercel / Netlify URL here]`

---

## Key Features

- **Single-File Architecture (`index.html`):** Self-contained HTML5 with embedded CSS and vanilla JavaScript—no bundler or external local asset paths required.
- **Full-Viewport 3D Neural Wave Terrain:** Ambient Three.js wireframe horizon wave and volumetric particle field that responds to scroll depth and cursor movement.
- **Interactive 3D Cyber-Core (GLSL + Three.js):** Custom GLSL quantum plasma core, 12 articulated iris blades, dual helical energy ribbons, 120 instanced orbital nodes, click shockwaves, `Explode Core` & `Overdrive` modes, and a clearly commented placeholder for dropping in a Spline 3D `<iframe>`.
- **Multi-Layered Parallax & 3D Scroll Reveals:** Smooth `requestAnimationFrame` depth parallax, staggered 3D perspective card reveals, and animated metric count-ups.
- **Glitch Headline & Live Countdown:** Chromatic glitch typography paired with a live `tabular-nums` countdown to **December 16, 2026**.
- **Interactive Event Showcase:** Filterable event grid (`All`, `Tech`, `AI`, `Combat`) with mouse-driven 3D tilt hover physics and track pre-selection.
- **Scroll-Synced Timeline & Tech Specs:** Vertical renaissance roadmap featuring a scroll-reactive cyan-to-purple progress beam alongside arena hardware specifications.
- **Smart `localStorage` Holographic Cyber-Pass:** Modal registration form (`Name`, `Email`, `College`, `Track`) that persists data in browser `localStorage`, generates a unique Pass ID and deterministic QR-style cyber matrix badge on a 3D tiltable holographic foil card, supports `Print VIP Pass`, and includes a `Reset / Logout` flow.
- **Responsive & Accessible:** Sticky glassmorphic navigation with mobile drawer, keyboard-accessible FAQ accordion, `focus-visible` states, and `prefers-reduced-motion` support.

---

## Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Structure** | Semantic HTML5 (Single-file portable layout) |
| **Styling** | Embedded CSS3 (Grid, Flexbox, Glassmorphism, `@media print`) |
| **Typography** | Google Fonts — `Orbitron` (Display) & `Poppins` (Body) |
| **3D Graphics** | Three.js (`r147` CDN) + Procedural 2D Canvas Fallback |
| **Interactivity** | Vanilla ES6+ JavaScript (`IntersectionObserver`, `requestAnimationFrame`, `localStorage`) |

---

## Quick Start

1. Clone or download this repository.
2. Open the project folder in **VS Code**.
3. Open `index.html` directly in your browser or launch via the **Live Server** extension (`Go Live`).
4. To swap in a Spline scene, search for `SPLINE 3D PLACEHOLDER` inside `index.html` and paste your Spline embed `<iframe>`.

---

## License

Built for educational and showcase purposes for **Techfest IIT Bombay 2026**.
