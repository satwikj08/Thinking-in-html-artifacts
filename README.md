# Thinking in HTML — Interactive Artifacts Suite

> A multi-paradigm exploration of the modern web document as an autonomous, zero-build execution canvas. Rather than relying on heavy multi-gigabyte build toolchains or fragmented desktop applications, this suite demonstrates how complex operational software, high-impact keynote presentations, and real-time 3D astrophysics simulations can be architected directly within self-contained, single-file web documents.

---

## 💡 The Core Thesis: "Thinking in HTML"

For decades, the web document was relegated to a passive markup container—a static brochure waiting for a backend or bloated framework to give it life. When teams need a slide deck, they reach for proprietary presentation software. When they need an operational dashboard, they install multi-tier state machines. When they need 3D physics, they turn to compiled native engines.

**Thinking in HTML** flips this paradigm on its head:

1. **The Document as a Micro-Operating System**: A single file encapsulates structure, reactive state, styling primitives, animations, and GPU pipelines without an external bundler or dependency tree.
2. **Instant Universality & Zero Setup**: No `npm install`, no broken peer dependencies, no webpack misconfigurations. Double-click the file or host it on any static server, and it executes instantaneously across macOS, Windows, Linux, tablets, and phones.
3. **Multi-Domain Versatility**: Demonstrates that the native web runtime is equally capable of handling high-density productivity workflows, luxury editorial narratives, and hardware-accelerated scientific ray-marching.

---

## 📦 Suite Architecture & Projects

This repository packages three distinct artifacts, each addressing a unique engineering and design domain:

### 1. The Operational Dashboard — `DailyTasksDashboard.html`
*A complete, high-density personal productivity operating system built with semantic structure and local state persistence.*

* **Daily Rituals & Habit Checklist**: Non-negotiable recurring rituals (AM/PM/Any) with dynamic progress metering and one-click morning resets.
* **Granular Action Task Manager**: Multi-factor priority weighting (`High`, `Medium`, `Low`), category tags (`Product`, `Engineering`, `Design`, `Operations`, `Personal`), time estimations, and expandable multi-step sub-checklists.
* **Hourly Spacetime Schedule Grid**: Visual timeline spanning `08:00` to `20:00` with an animated live current-time indicator line, color-coded time blocks (`Deep Work`, `Meeting`, `Personal`), and modal block creation.
* **Integrated Focus Pomodoro Timer**: Switchable 25-minute deep focus and 5-minute break cycles with one-click task linking.
* **Zero-Latency Persistence**: Real-time bidirectional synchronization with browser `localStorage` and system light/dark mode adaptability.

---

### 2. The Interactive Keynote Deck — `AppleInnovation&Research.html`
*A flagship, high-contrast interactive presentation examining Apple's industrial design ethos, metallurgy, and custom silicon.*

* **Keyboard-Driven Slide Navigation**: Seamless fluid transitions across 9 curated chapters using `←` / `→` arrow keys, `Space`, or on-screen dot indicators.
* **Global Slide Navigator**: Instant bird's-eye drawer (`G` key) allowing presenters to inspect and jump across all slides instantly.
* **Interactive Atomic Material Inspector**: Deep dive into Grade 5 Titanium diffusion bonding, Tandem OLED micro-optics, and 3D-laminated singular glass with real-time specification rendering.
* **Live Dynamic Benchmark Chart**: Switchable animated data visualization comparing M1 through M4 silicon across **Neural Engine Compute (TOPS)**, **CPU Perf/Watt**, **Transistor Density**, and **Unified Memory Bandwidth**.
* **Interactive Knowledge Quiz**: Integrated 4-question engineering assessment with instantaneous option validation, technical explanations, and score tracking.

---

### 3. The Relativistic 3D Astrophysics Simulator — `WormholeSimulator.html`
*A hardware-accelerated 3D WebGL simulator of an Ellis–Morris–Thorne traversable wormhole powered by Three.js and custom GLSL shaders.*

* **Morris–Thorne Metric Spacetime Funnel**: Procedural 3D embedding geometry governed by:
  $$r(z) = b_0 \cdot \left(1 + \left(\frac{z}{L}\right)^2\right)^{\frac{\text{flare}}{2}}$$
* **Custom GLSL Shader Pipelines**: Real-time geodesic coordinate lines, relativistic frame-dragging twist ($\omega$), and Doppler energy streaking.
* **Relativistic Accretion Disk & Lensed Photon Arch**: Dual-plane Keplerian plasma rotation with differential orbital velocities and relativistic Doppler beaming.
* **Exotic Matter Throat Stabilizer & Gravitational Lensing**: Triple counter-rotating negative-energy rings maintaining throat stability ($r = b_0$), accompanied by a Fresnel Einstein ring halo and high-velocity polar plasma jets.
* **Autonomous Throat Transit**: Switch between free orbital camera controls, close-up singularity horizon grazing, or autonomous flight directly through the wormhole tunnel between Universe A and Universe B.
* **8 Live Physics Sliders**: Real-time interactive control over Throat Radius, Tunnel Length, Flare Curvature, Frame-Dragging Twist, Flow Velocity, Accretion Spin, and Cosmic Luminosity.

---

## 🛠️ Technology Stack & Zero-Build Philosophy

| Layer | Implementation | Purpose |
| :--- | :--- | :--- |
| **Markup & Runtime** | Native HTML5 Document Model | Autonomous single-file portable packages |
| **Styling & Micro-Typography** | Tailwind CSS (CDN Engine) + Custom CSS | Design system tokens, glassmorphism, responsive grids |
| **Typography** | Inter, Plus Jakarta Sans, JetBrains Mono | Editorial readability and monospace telemetry |
| **State & Interactivity** | Pure Vanilla ECMAScript (ES6+) | Event delegation, local storage, custom timers, quiz engines |
| **3D Rendering** | Three.js (r128) + WebGL | Coordinate systems, scene graphs, cameras, point clouds |
| **GPU Shaders** | Custom GLSL (Vertex & Fragment) | Spacetime curvature, plasma noise, Doppler beaming, Fresnel optics |

---

## ⚡ Getting Started

Because these projects are built under the **Thinking in HTML** philosophy, there are **no dependencies to install and no build commands to run**:

1. Clone or download the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
2. Open any file directly in your web browser:
   * Double click `index.html` to open the central launchpad.
   * Or open `DailyTasksDashboard.html`, `AppleInnovation&Research.html`, or `WormholeSimulator.html` independently.

---

## 🌐 Deploying to GitHub Pages (1-Click Hosting)

1. Push this repository to GitHub.
2. In your repository settings, navigate to **Settings** → **Pages**.
3. Under **Build and deployment** → **Source**, select `Deploy from a branch`.
4. Choose the `main` (or `master`) branch and the `/ (root)` folder, then click **Save**.
5. Your interactive suite will be live worldwide at `https://<your-username>.github.io/<your-repo-name>/`.
