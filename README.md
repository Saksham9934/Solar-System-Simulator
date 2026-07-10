<div align="center">

# 🌌 Solar System Simulator

### 🚀 A Realistic Interactive 3D Solar System built with HTML5, CSS3, JavaScript & Three.js

<p align="center">

<img src="https://img.shields.io/badge/Three.js-WebGL-black?style=for-the-badge&logo=threedotjs"/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>

<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>

<img src="https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript"/>

<img src="https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Performance-60FPS-blue?style=for-the-badge"/>

<img src="https://img.shields.io/badge/NASA-Inspired-red?style=for-the-badge"/>

</p>

### 🌍 Explore the Solar System in Stunning 3D

**Live Demo:** [(https://solar-system-simulator-five.vercel.app/)]
</div>

---

# 📖 Overview

**Solar System Simulator** is a modern, interactive, NASA-inspired 3D web application built using **Three.js**, **HTML5**, **CSS3**, and **Vanilla JavaScript**. It recreates our Solar System with realistic planets, orbital motion, dynamic lighting, asteroid belts, cinematic camera transitions, and immersive visual effects.

Designed for both learning and exploration, the simulator combines scientific inspiration with high-performance WebGL rendering to provide a smooth and engaging experience across desktop and mobile devices.

---

# ✨ Features

## ☀️ Solar System

- ☀️ Realistic Sun with Point Light
- 🌎 All 8 Planets
- 🌙 Earth's Moon
- 💍 Saturn Rings
- ☄️ Optional Comets
- 🪨 Asteroid Belt
- 🌌 Milky Way Galaxy
- ✨ Thousands of Animated Stars
- 🌠 Nebula Background

---

## 🪐 Planet Simulation

Each planet includes:

- Self Rotation
- Revolution Around Sun
- Realistic Scaling
- Accurate Orbital Speed
- Planet Labels
- Hover Glow Effect
- Click Interaction
- Smooth Camera Zoom

---

## 🎬 Visual Effects

- Bloom Effect
- Lens Flare
- Dynamic Shadows
- Reflections
- HDR Lighting
- Space Environment
- Particle Effects
- Orbit Paths
- Atmospheric Glow

---

## 🎮 Camera Controls

- Rotate
- Zoom
- Pan
- Cinematic Planet Focus
- Reset Camera
- Smooth Transitions

Powered by **OrbitControls**

---

## 📋 Information Panel

Clicking any planet displays:

- Planet Name
- Diameter
- Distance from Sun
- Number of Moons
- Length of Day
- Length of Year
- Average Temperature
- Interesting Facts

---

## ⚙️ Interactive Controls

- ▶️ Play Animation
- ⏸ Pause Animation
- ⚡ Speed Slider
- 🌍 Toggle Labels
- 🛰 Toggle Orbit Lines
- 🌙 Dark / Space Mode
- 🔄 Reset Camera
- ⛶ Fullscreen Mode

---

# 🛠 Tech Stack

| Category | Technology |
|-----------|------------|
| Structure | HTML5 |
| Styling | CSS3 |
| Programming | JavaScript (ES6) |
| 3D Engine | Three.js |
| Controls | OrbitControls |
| Rendering | WebGL |
| Animations | requestAnimationFrame |
| Effects | Bloom, Lens Flare |
| Assets | NASA Planet Textures |

---

# 🌌 Included Celestial Objects

| Object | Status |
|----------|--------|
| ☀️ Sun | ✅ |
| Mercury | ✅ |
| Venus | ✅ |
| Earth | ✅ |
| Moon | ✅ |
| Mars | ✅ |
| Asteroid Belt | ✅ |
| Jupiter | ✅ |
| Saturn + Rings | ✅ |
| Uranus | ✅ |
| Neptune | ✅ |
| Comets | ✅ Optional |

---

# 📂 Project Structure

```text
Solar-System-Simulator/

│── index.html
│── style.css
│── script.js

│── textures/
│     ├── sun.jpg
│     ├── mercury.jpg
│     ├── venus.jpg
│     ├── earth.jpg
│     ├── moon.jpg
│     ├── mars.jpg
│     ├── jupiter.jpg
│     ├── saturn.jpg
│     ├── uranus.jpg
│     ├── neptune.jpg
│     └── stars.jpg

│── assets/
│     ├── icons/
│     ├── fonts/
│     └── screenshots/

└── README.md
```

---

# 🖼 System Architecture

```text
                    User
                      │
                      ▼
                index.html
                      │
       ┌──────────────┼──────────────┐
       ▼              ▼              ▼
   style.css      script.js      textures/
                      │
          ┌───────────┼────────────┐
          ▼           ▼            ▼
     Three.js   OrbitControls   EffectComposer
          │
          ▼
     WebGL Renderer
          │
          ▼
   Solar System Scene
```

---

# 🌍 Planet Information

| Planet | Moon | Rings | Orbit | Rotation |
|---------|------|--------|---------|-----------|
| Mercury | ❌ | ❌ | ✅ | ✅ |
| Venus | ❌ | ❌ | ✅ | ✅ |
| Earth | ✅ | ❌ | ✅ | ✅ |
| Mars | ❌ | ❌ | ✅ | ✅ |
| Jupiter | Many | ❌ | ✅ | ✅ |
| Saturn | Many | ✅ | ✅ | ✅ |
| Uranus | Many | ❌ | ✅ | ✅ |
| Neptune | Many | ❌ | ✅ | ✅ |

---

# 🚀 Installation

Clone Repository

```bash
git clone https://github.com/Saksham9934/Solar-System-Simulator.git
```

Move into Project

```bash
cd Solar-System-Simulator
```

Run

Simply open

```text
index.html
```

or

```bash
npx serve .
```

---

# ⚡ Performance Optimizations

- Adaptive Rendering
- Efficient Geometry
- Optimized Textures
- Lazy Loading
- Frustum Culling
- Mobile Quality Scaling
- 60 FPS Rendering
- requestAnimationFrame Optimization

---

# 📱 Browser Support

| Browser | Supported |
|-----------|-----------|
| Chrome | ✅ |
| Edge | ✅ |
| Firefox | ✅ |
| Safari | ✅ |

---

# 🛣 Roadmap

- ✅ Complete Solar System
- ✅ Planet Information Panel
- ✅ Orbit Controls
- ✅ Particle Effects
- ✅ Responsive Design
- ⏳ Spacecraft Navigation
- ⏳ VR Support
- ⏳ Voice Commands
- ⏳ Exoplanet System
- ⏳ Time Warp Simulation
- ⏳ Black Hole Simulation

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 🙌 Acknowledgements

- NASA
- Three.js
- WebGL
- MDN Web Docs
- Open Source Community

---

# ⭐ Support

If you enjoyed this project,

⭐ Star the repository

🍴 Fork it

💬 Share it

---

<div align="center">

## 🌌 Explore the Universe from Your Browser

**Built with ❤️ using HTML • CSS • JavaScript • Three.js**

⭐ **Don't forget to Star this Repository!** ⭐

</div>
