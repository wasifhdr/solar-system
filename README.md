# 🌌 Interactive 3D Solar System Replica

A production-ready, interactive 3D Solar System simulation built entirely using **Three.js** and **Astronomy Engine**. This application runs entirely in the browser from a single standalone file, mapping real-time astronomical positions onto a visually optimized, interactive 3D environment.

---

## 🚀 Features

- **Real-Time Data Integration:** Uses the mathematical algorithms of `astronomy-engine` to calculate the exact heliocentric positions of the planets for the current date and time.
- **Dynamic Control Mechanics:**
  - **Sync to Real Time:** Automatically fetches the exact current timestamp and snaps the celestial bodies to their true current positions in space.
  - **Real-Time Movement Toggle:** Swap between an accelerated visual simulation mode and a strict astronomical clock mode (where planets move at their actual, imperceptible physical speeds).
- **Interactive HUD & Raycasting:** Hovering over the Sun, planets, or moons highlights the celestial body with a responsive wireframe glow and displays contextual data metrics (diameter, orbit tracking, orbital period, and historical fun facts).
- **Zero Infrastructure Bottlenecks:** No external image assets, local Node servers, or API keys required. All planet surfaces use high-performance procedural canvas textures to completely bypass CORS or broken asset URL errors.
- **Cinematic Navigation:** Full spatial exploration via mouse tracking powered by `OrbitControls` (Left Click + Drag to rotate, Right Click + Drag to pan, Scroll to zoom).

---

## 🛠️ Tech Stack & Dependencies

- **Core Engine:** [Three.js (r128)](https://threejs.org/)
- **Camera Controls:** `OrbitControls.js`
- **Astronomical Calculations:** [Astronomy Engine](https://github.com/cosinekitty/astronomy) (Calculates high-precision coordinates locally via client-side processing)
- **UI Overlay:** Embedded HTML5, CSS3 Glassmorphism HUD

---

## 📦 Installation & Quick Start

Because this app is designed with a decentralized, single-file architecture, you do not need to install `npm` packages or configure local development servers.

1. Clone this repository or download the source code:
   ```bash
   git clone [https://github.com/wasif_hdr/solar-system.git](https://github.com/wasif_hdr/solar-system.git)
   ```
