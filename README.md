<<<<<<< HEAD
# Balaraman S. — Cinematic Developer Portfolio

A React + Vite portfolio inspired by the approved Vice City sunset reference: pink/peach/coral skies, deep-plum surfaces, neon pink details, floating navigation, custom dashboard previews and cinematic motion. No people, avatars or silhouettes are used.

## Features

- 10–15 second cinematic intro with a persistent Skip Intro control (shown once per browser session)
- Animated CSS cityscape: drifting clouds, glowing sun, skyline, bridge, water reflections, palm silhouettes and moving traffic
- Sunset / Midnight theme switch
- Optional ambient synth tone, enabled only after the visitor clicks the audio control
- Smooth Lenis scrolling, GSAP hero entrance, Framer Motion reveals and project-card hover motion
- Four project case studies with custom-built interface illustrations (not falsely represented as actual product screenshots)
- Resume download, GitHub links, LinkedIn link, email copy button and mailto contact
- Responsive navigation and layouts, plus reduced-motion support

## Run locally

Requirements: Node.js 18+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Production build

```bash
npm run build
npm run preview
```

The production output is generated in `dist/`.

## Deploy free on Vercel

1. Create a new GitHub repository named `balaraman-portfolio`.
2. Extract this ZIP and push the project contents to that repository.
3. In Vercel, choose **Add New → Project** and import `balaraman-portfolio`.
4. Framework preset: **Vite** (normally detected automatically).
5. Build command: `npm run build`.
6. Output directory: `dist`.
7. Deploy. Add `balaraman.vercel.app` under Project → Settings → Domains if that subdomain is available.

No backend or environment variables are required for this static portfolio.

## Content accuracy notes

- Resume facts are based on the supplied `balaramanresume.pdf`.
- Public contact shows email only. Phone number is intentionally not displayed.
- HRMS has no public repository link supplied, so its card does not show a fabricated GitHub URL.
- Project cards use original CSS-generated preview interfaces. Replace them with genuine screenshots later if desired.
- The Interview AI Agent feature description is based on the project details supplied in the conversation.
- The resume lists Azentmart as Aug 2026–Nov 2026 and Enterprise HRMS as Dec 2025–Present; those dates are preserved as supplied.

## Customize

- Main content: `src/main.jsx`  
- Styling and animations: `src/style.css`
- Resume file: `public/assets/Balaraman-S-Resume.pdf`
=======

>>>>>>
