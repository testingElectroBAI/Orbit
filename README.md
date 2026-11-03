# 🪐 ORBIT — Universe Explorer

> **Open sky, no telescope needed.** An interactive, real-time 3D atlas of the Solar System and deep sky built with Three.js and a vibrant Neo-Brutalist design language. Explore 25 celestial bodies, procedural textures, orbital mechanics, and deep space phenomena.

---

## 🌟 Overview

**ORBIT** brings the cosmos to life with a bold, tactile, and scientifically inspired interface. Fly from Mercury to the event horizon of a supermassive black hole with smooth 3D camera controls, procedural planetary textures, and real astronomical metrics.

- **Zero Build Tools Required:** Pure single-file architecture running vanilla HTML5, CSS3, and JavaScript with Three.js.
- **Neo-Brutalist Aesthetic:** High-contrast retro-futuristic UI, bold typography (`Space Grotesk`, `IBM Plex Mono`, `Inter`), responsive layout, and dark/light themes.
- **Scientifically Grounded:** Uses NASA Planetary Fact Sheet data and JPL approximate mean longitudes for orbital simulations spanning 1800–2050.

---

## ✨ Features

### 🌌 1. Real-Time 3D Engine & Orbit Simulation
- **Three.js WebGL Engine:** Dynamic scene rendering with real-time camera tracking, target locking, and smooth lerped motion.
- **Solar System Simulation:** Accurate relative orbits and speeds for the Sun, planets, moons, and dwarf planets.
- **Atmospheric & Ring Shaders:** Multi-layer atmospheric glows, procedural clouds, and detailed planetary ring systems (e.g., Saturn with Cassini Division).

### 🪐 2. 25 Solar System Bodies
- **The Central Star:** The Sun (G2V type star).
- **8 Terrestrial & Jovian Planets:** Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune.
- **9 Major Moons:** Moon (Earth), Io, Europa, Ganymede, Callisto (Jupiter), Titan, Enceladus (Saturn), Triton (Neptune), Phobos (Mars).
- **5 Dwarf Planets:** Pluto, Ceres, Eris, Haumea, Makemake.

### 🔭 3. Deep Space Field
Explore deep sky objects outside our solar system rendered as procedural volumetric particle clouds:
- **Galaxies:** Andromeda (M31), Whirlpool (M51), Sombrero (M104).
- **Nebulae:** Orion Nebula (M42), Crab Nebula (M1), Pillars of Creation.
- **Black Holes:** Sagittarius A* (Milky Way supermassive black hole with relativistic accretion disc simulation), M87*, Cygnus X-1.
- **Star Clusters:** Pleiades (M45), Omega Centauri, Hercules Cluster (M13).

### 🎨 4. Procedural Canvas Textures
- Algorithmic, seed-based surface generation for every planet and moon.
- Realistic surface details including gas giant weather bands, storm spots, polar ice caps, cratering, and continents without large image asset downloads.

### 🔍 5. Search, Missions & Daily Discovery
- **Instant Search:** Quick-jump search autocomplete across all solar and deep-sky objects.
- **Daily Cosmic Discovery:** Dynamic daily featured celestial body and random discovery roll.
- **Missions & Objectives:** Progress tracking as you inspect targets, visit deep-space objects, and explore the cosmos.
- **Interactive Dossiers:** Deep-dive modal dossiers packed with physical stats (diameters, distances, orbital periods, atmospheres).

### 🌓 6. Dark / Light Mode
- Seamless theme toggle with animated transitions and persistent user preference saved to `localStorage`.

---

## 🎮 Controls & Shortcuts

| Action | Control |
|---|---|
| **Rotate Camera** | Click & drag (Canvas) |
| **Pan Camera** | <kbd>Shift</kbd> + Click & drag |
| **Zoom In / Out** | Mouse wheel, pinch gesture, or <kbd>+</kbd> / <kbd>-</kbd> keys |
| **Switch Target** | <kbd>◀</kbd> / <kbd>▶</kbd> Arrow keys or target chips |
| **Reset View** | Camera Toolbar **Reset** button |
| **Fullscreen** | **Fullscreen** button or <kbd>Esc</kbd> to exit |
| **Close Modals** | <kbd>Esc</kbd> or click overlay |

---

## 🚀 Getting Started

No build step, package manager, or server setup is required.

### Option A: Run Directly in Browser
1. Clone this repository:
   ```bash
   git clone https://github.com/testingElectroBAI/Orbit.git
   ```
2. Open `index.html` directly in any modern web browser (Chrome, Firefox, Safari, Edge, Brave).

### Option B: Local Development Server
Serve using Python, Node, or VS Code Live Server:

```bash
# Using Python 3
python -m http.server 8000

# Using npx serve
npx serve .
```
Then visit `http://localhost:8000`.

---

## 🛠️ Tech Stack

- **Markup & Layout:** Semantic HTML5
- **Styling:** CSS3 (Custom properties, CSS Grid, Neo-Brutalist components, fluid clamp typography)
- **3D Graphics:** [Three.js](https://threejs.org/) (r128 CDN)
- **Typography:** Space Grotesk, IBM Plex Mono, Inter (Google Fonts)
- **Data:** NASA Planetary Fact Sheet & JPL Ephemeris

---

## 📚 Credits & Data Sources

- **Planetary Figures:** [NASA Planetary Fact Sheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/)
- **Deep Space Coordinates & Imagery Insights:** NASA, ESA, and ESO public archives
- **Ephemeris Calculations:** Approximate mean orbital longitudes (1800–2050)
- **Textures:** Custom procedural 2D canvas generation

---

## Online Experience

just vist [orbit25.vercel.app](https://orbit25.vercel.app)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — feel free to explore, learn, and build upon it!
