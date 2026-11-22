Here is the fully updated **`README.md`** text complete with **all 6 members of Team Meta Beats**, their official hackathon roles.

---

```markdown
# 🌍 EARTH JS JUKEBOX SONIFICATION // TEAM META BEATS

> **NASA Space Apps Challenge Hackathon Project**  
> **Team Name:** Meta Beats  

---

## 🚀 Overview
**Earth JS Jukebox Sonification** is an advanced, multi-tier web application that transforms official NASA satellite observation data into real-time, polyphonic acoustic soundscapes and immersive 3D WebGL visualizations. Designed for the NASA Space Apps Challenge, this application bridges complex earth-science telemetry with human audio perception through a custom **5-channel Web Audio DSP synthesizer**, interactive harmonic keyboards, and live scientific theory dossiers.

---

## 👥 Team Meta Beats & Contributors
* Sahil Singh — Team Leader
* Shivam Raj — Main Developer & Lead System Architect
* Divyanshu Kumar — Co-Developer
* Palak Agarwal — PPT Manager
* Noora Tayyaba — Data Collector
* Ayushi Vyas — Data Collector

---

## 🏛️ 3-Tier System Architecture
The project is structured around a clean, scalable 3-tier architecture:

```text
📁 nasa-project-by-meta-beats/
├── 📁 1-frontend/         # Interactive HUD UI, Three.js 3D Earth & Moon, Web Audio Engine, & style.css
├── 📁 2-backend/          # Node.js & Express REST API server (/data/:track endpoints)
├── 📁 3-memory/           # NASA-certified JSON time-series archives (rain.json, ocean.json, glacier.json)
├── 📄 package.json        # Node dependencies (express, cors)
└── 📄 vercel.json         # Vercel deployment routing configuration

```

---

## 💻 Local Installation & Setup

### 1. Clone the repository:

```bash
git clone [https://github.com/ShivamRajIT/nasa-project-by-meta-beats.git](https://github.com/ShivamRajIT/nasa-project-by-meta-beats.git)
cd nasa-project-by-meta-beats

```

### 2. Install dependencies:

```bash
npm install

```

### 3. Start the local backend server:

```bash
node 2-backend/server.js

```

### 4. Open in your browser:

Navigate to `http://localhost:5000` to launch the workstation.

---

## 🚀 Deployment & Live Demo

* **Live URL:** [https://nasa-project-by-meta-beats.vercel.app](https://sound-sonification-nasa-by-meta-bea.vercel.app/)
* **Hosting Platform:** Vercel (Production)

---

## 🌟 Key Features & Technical Highlights

* **3D Earth & Lunar Orbit (Three.js WebGL):** Hardware-accelerated 3D planetary rendering with an orbiting lunar moon, satellite tracking, and touch-interactive shockwave color shifts.
* **5-Channel Web Audio DSP Synthesizer:** Polyphonic harmonic lead synth, deep sub-bass drone, procedural weather ambience generator, 808 kick percussion, and anomaly siren with a live 60FPS FFT spectrum analyzer.
* **Smart Voice-Sync Telemetry Pipeline:** Asynchronous speech synthesis synchronization ensuring narration never cuts off prematurely at normal speeds.
* **NASA-Certified Historical Datasets:** 12-month monthly monsoon cycle (Rain), 10 landmark years (Ocean), and 25 consecutive years of polar ice loss (Glacier) collected and structured by our data team.
* **Automated PDF Report Generator:** Built-in `jsPDF` engine enabling judges to export full NASA scientific theory dossiers and telemetry archives.

---

## © 2025–2026 Team Meta Beats. Built for the NASA Space Apps Challenge.

```

```
