# 🌌 Interactive 3D Solar System Replica

A production-ready, interactive 3D Solar System simulation built entirely using **Three.js** and **Astronomy Engine**. This application runs entirely in the browser from a single standalone file, mapping real-time astronomical positions onto a visually optimized, interactive 3D environment.

---

## 🚀 Features

* **Real-Time Data Integration:** Uses the mathematical algorithms of `astronomy-engine` to calculate the exact heliocentric positions of the planets for the current date and time.
* **High-Fidelity Procedural Earth:** * **GLSL Shaders:** Earth is rendered using custom shader materials featuring procedural noise for continents, oceans, and polar ice.
  * **Day/Night Cycle & City Lights:** Calculates the sun's directional vector to dynamically reveal glowing city lights on the dark side of the planet.
  * **Atmosphere & Flight Trails:** Features independent, transparent moving cloud layers and animated flight trails/low-orbit satellites across the surface.
* **Dynamic Control Mechanics:**
  * **Sync to Real Time:** Automatically fetches the exact current timestamp and snaps the celestial bodies to their true current positions in space.
  * **Real-Time Movement Toggle:** Swap between an accelerated visual simulation mode and a strict astronomical clock mode.
  * **Click-to-Zoom:** Clicking on Earth triggers a cinematic, mathematically lerped camera transition into a close-orbit view, with a "Reset View" UI toggle to return to the heliocentric overview.
* **Interactive HUD & Raycasting:** Hovering over the Sun, planets, or moons highlights the celestial body with a responsive wireframe glow and displays contextual data metrics.
* **Zero Infrastructure Bottlenecks:** No external image assets, local Node servers, or API keys required. All planet surfaces use high-performance procedural canvas textures and GLSL shaders to completely bypass CORS or broken asset URL errors.
* **Cinematic Navigation:** Full spatial exploration via mouse tracking powered by `OrbitControls`.

---

## 🛠️ Tech Stack & Dependencies

* **Core Engine:** [Three.js (r128)](https://threejs.org/)
* **Shaders:** Custom GLSL (Vertex and Fragment shaders for procedural generation)
* **Camera Controls:** `OrbitControls.js`
* **Astronomical Calculations:** [Astronomy Engine](https://github.com/cosinekitty/astronomy) 
* **UI Overlay:** Embedded HTML5, CSS3 Glassmorphism HUD

---

## 📦 Installation & Quick Start

Because this app is designed with a decentralized, single-file architecture, you do not need to install `npm` packages or configure local development servers.

1. Clone this repository or download the source code:
   ```bash
   git clone [https://github.com/wasif_hdr/solar-system.git](https://github.com/wasif_hdr/solar-system.git)
