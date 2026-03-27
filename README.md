<div align="center">

![ARVION-OS Banner](https://capsule-render.vercel.app/api?type=waving&height=230&color=0:020617,35:0f172a,70:0ea5e9,100:22d3ee&text=ARVION-OS&fontColor=ffffff&fontSize=64&fontAlignY=38&desc=Futuristic%20Browser%20Desktop%20Experience&descAlignY=61&animation=twinkling)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=23&duration=2500&pause=800&color=38BDF8&center=true&vCenter=true&width=920&lines=Desktop-like+UI+inside+your+browser;Interactive+windows+%7C+motion+%7C+3D+atmosphere;Built+for+impactful+frontend+experiences)](https://github.com/Y7X-bit/ARVION-OS)

[![Live](https://img.shields.io/badge/Live-arvion--os.vercel.app-0ea5e9?style=for-the-badge&logo=vercel&logoColor=white)](https://arvion-os.vercel.app)
[![Repo](https://img.shields.io/badge/GitHub-ARVION--OS-0b1220?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Y7X-bit/ARVION-OS)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=0b0f19)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-7-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind](https://img.shields.io/badge/Tailwind-3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=06283D)](https://tailwindcss.com/)

</div>

---

## Overview

ARVION-OS is a high-immersion web interface that simulates a futuristic operating system in the browser.
It focuses on cinematic UI motion, layered interactions, and a desktop-like workflow instead of a traditional static page.

## Highlights

- Desktop-inspired interaction model with app-style windows
- Motion-first interface using Framer Motion and GSAP
- 3D depth and atmosphere powered by Three.js
- Clean, scalable React + TypeScript architecture
- Performance-friendly Vite setup for fast iteration

## Product Preview

<div align="center">
  <video src="./Arvion%20OS.mp4" controls autoplay muted loop playsinline preload="metadata" width="100%"></video>
</div>

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 18, TypeScript |
| Build Tool | Vite 7 |
| Styling | Tailwind CSS 3 |
| Motion | Framer Motion, GSAP |
| 3D | Three.js |
| State | Zustand |
| Hosting | Vercel |

## Typography

ARVION-OS uses local custom fonts from the repository:

- `font/termina-test/TerminaTest-Regular.otf`
- `font/termina-test/TerminaTest-Medium.otf`
- `font/termina-test/TerminaTest-Bold.otf`

They are configured in `src/index.css` as `font-family: "TerminaTest"`.

## Local Setup

```bash
git clone https://github.com/Y7X-bit/ARVION-OS.git
cd ARVION-OS
npm install
npm run dev
```

Runs at `http://localhost:5173`.

## Production Build

```bash
npm run build
npm run preview
```

Output folder: `dist/`

## Project Structure

```text
ARVION-OS/
+-- assets/
+-- font/
¦   +-- termina-test/
+-- src/
¦   +-- components/
¦   +-- pages/
¦   +-- App.tsx
¦   +-- index.css
¦   +-- main.tsx
+-- Arvion OS.mp4
+-- index.html
+-- package.json
+-- postcss.config.js
+-- tailwind.config.js
+-- vite.config.ts
```
