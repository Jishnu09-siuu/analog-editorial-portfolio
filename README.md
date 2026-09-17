# Analog & Editorial Photography Portfolio

An interactive, high-fidelity 3D analog photography portfolio and digital darkroom experience. Built with WebGL, Three.js, and modern front-end techniques to showcase 35mm mechanical cameras, film anatomy, and editorial visual archives.

---

## ✨ Features

- **Interactive 3D Camera Experience**: Real-time 3D rendered Canon F-1 mechanical SLR camera model (`.glb`) with interactive inspection, orbit controls, and smooth WebGL lighting.
- **Anatomy of 35mm Film**: Visual layer-by-layer breakdown demonstrating the photographic emulsion process (anti-halation layer, subbing layer, RGB light-sensitive layers, and protective coat).
- **Editorial & Analog Gallery**: High-resolution showcase of 35mm film captures, human portraits, architecture, and cinematic street photography.
- **Atmospheric Darkroom Aesthetic**: Thoughtfully curated monochrome and warm amber palette inspired by classic darkroom workflows.
- **Zero-Dependency Local Server**: Built-in lightweight Node.js HTTP server with custom MIME support for `.glb` 3D assets, high-res textures, and web standards.

---

## 🛠️ Tech Stack

- **Core**: HTML5, Vanilla JavaScript, CSS3
- **3D & WebGL**: Three.js, GLTFLoader, OrbitControls
- **Assets**: 3D GLTF/GLB Models, High-Res 35mm Film Textures, Web Fonts
- **Backend / Serve**: Node.js (`http`, `fs`, `path`)

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14.x or higher recommended)

### Installation & Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Jishnu09-siuu/analog-editorial-portfolio.git
   cd analog-editorial-portfolio
   ```

2. **Start the local server:**
   ```bash
   npm start
   ```
   *Alternatively:*
   ```bash
   node server.js
   ```

3. **Open in browser:**
   Navigate to [http://localhost:3000](http://localhost:3000)

---

## 📁 Project Structure

```text
analog-editorial-portfolio/
├── cannonF1_v2.glb        # 3D Canon F-1 Camera GLTF model
├── filmBox1020Glb/        # 3D Film Box assets
├── filmRoll512Glb/        # 3D Film Roll assets
├── images/                # High-resolution portfolio galleries
├── index.html             # Main portfolio entry point
├── index.css              # Custom styling & darkroom typography
├── index.js               # WebGL / Three.js 3D rendering & animations
├── server.js              # Custom Node.js HTTP server (MIME & CORS support)
├── package.json           # Project metadata & npm scripts
└── README.md              # Project documentation
```

---

## 📜 License

This project is licensed under the ISC License.
