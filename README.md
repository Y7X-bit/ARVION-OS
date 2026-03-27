# ARVION-OS

ARVION-OS is an interactive desktop-style experience that runs in the browser.  
It is built as a UI simulation of a futuristic operating system, with windowed interactions, motion-heavy transitions, and immersive visuals.

[Live Site](https://arvion-os.vercel.app)

## Preview

<div align="center">
  <video src="./Arvion%20OS.mp4" controls autoplay muted loop playsinline preload="metadata" width="100%"></video>
</div>

## Features

- Desktop-like windowed interface
- Motion and interaction effects with Framer Motion and GSAP
- 3D visuals powered by Three.js
- React + TypeScript component architecture
- Responsive layout for different screen sizes

## Tech Stack

- React 18
- TypeScript 5
- Vite 7
- Tailwind CSS 3
- Framer Motion
- GSAP
- Three.js
- Zustand

## Run Locally

```bash
git clone https://github.com/Y7X-bit/ARVION-OS.git
cd ARVION-OS
npm install
npm run dev
```

Default local URL: `http://localhost:5173`

## Build

```bash
npm run build
npm run preview
```

Build output: `dist/`

## Project Structure

```text
ARVION-OS/
├── assets/
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
├── Arvion OS.mp4
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── vite.config.ts
```
