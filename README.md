<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&size=42&duration=3000&pause=1000&color=F4C430&center=true&vCenter=true&width=700&lines=%D9%85%D9%88%D8%B2%DB%8C%DA%A9%D8%A7%D8%B1;MUSICAR;Offline-First+Music+Player;Built+with+React+%2B+PWA" alt="Typing SVG" />

<br/>

![Deployed](https://img.shields.io/badge/deployed%20on-GitHub%20Pages-222?style=for-the-badge&logo=github&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-installable-8A2BE2?style=for-the-badge&logo=pwa&logoColor=white)
![Offline](https://img.shields.io/badge/works-offline-00C853?style=for-the-badge&logo=cloudflare&logoColor=white)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)

<br/>

### 🎧 A personal, offline-capable music player — installable straight from your browser, no app store required.

<br/>

<img src="./readme-assets/screenshot.jpg" alt="Musicar App Screenshot" width="360" />

<br/>
<br/>

![stars](https://img.shields.io/github/stars/alirezadavari1/musicar?style=social)
![forks](https://img.shields.io/github/forks/alirezadavari1/musicar?style=social)
![watchers](https://img.shields.io/github/watchers/alirezadavari1/musicar?style=social)

</div>

---

<br/>

## ✨ Overview

**Musicar (موزیکار)** is a sleek, RTL-first personal music player built as a modern web app — and packaged as a fully installable **Progressive Web App (PWA)**. Add your tracks, organize them into playlists, and play everything even when you're completely offline.

No native build tools. No app store review. No 200MB download. Just open the link, tap **"Add to Home Screen,"** and you have a real app icon on your device.

<br/>

<div align="center">

```
  ╭──────────────────────────────────────────╮
  │   🎵  Add tracks   →   📂 Organize        │
  │   💾  Store locally →  📴  Play offline   │
  ╰──────────────────────────────────────────╯
```

</div>

<br/>

## 🚀 Features

<table>
<tr>
<td width="50%" valign="top">

### 🎨 Design
- Full **RTL** (Persian) interface, built correctly from the ground up
- Custom dark theme with vivid purple/blue accents
- Smooth, native-feeling transitions and gesture support
- Responsive — works equally well on mobile and desktop

</td>
<td width="50%" valign="top">

### ⚡ Core Functionality
- Create and manage **playlists**
- Persistent local library via **IndexedDB**
- Custom seek & volume sliders (properly RTL-aware!)
- Background playback with a persistent mini-player

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📴 Offline-First
- Installable **PWA** — real home-screen icon
- Service worker caches the entire app shell
- Downloaded tracks are stored **on-device**
- Zero network required after first load

</td>
<td width="50%" valign="top">

### 🛠️ Under the Hood
- **React 19** + **TypeScript** (strict mode)
- **Zustand** for state management
- **Dexie.js** wrapper over IndexedDB
- **Vite** build with `vite-plugin-pwa`

</td>
</tr>
</table>

<br/>

## 📱 Install It

<div align="center">

| Step | Action |
|:---:|:---|
| 1️⃣ | Open **[the live site](https://alirezadavari1.github.io/musicar/)** in Chrome (Android) or Safari (iOS) |
| 2️⃣ | Tap the **⋮ menu** → **"Add to Home Screen"** |
| 3️⃣ | Confirm — the Musicar icon appears on your home screen |
| 4️⃣ | Open it once online to cache everything |
| 5️⃣ | ✈️ Enable airplane mode — it still works! |

</div>

<br/>

## 🧩 Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square&logo=react&logoColor=white)
![Dexie](https://img.shields.io/badge/Dexie.js-FFCA28?style=flat-square&logo=indexeddb&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PWA](https://img.shields.io/badge/vite--plugin--pwa-5A0FC8?style=flat-square&logo=pwa&logoColor=white)

</div>

<br/>

## 🏗️ Project Structure

```
musicar/
├── src/
│   ├── components/     # UI building blocks (PlayerBar, TrackList, ...)
│   ├── pages/           # Route-level views
│   ├── store/            # Zustand stores (playback, library, playlists)
│   ├── db/                # Dexie/IndexedDB schema
│   ├── hooks/              # Custom React hooks
│   ├── utils/                # Helpers
│   └── types/                 # Shared TypeScript types
├── public/
│   └── icons/                    # PWA app icons
├── vite.config.ts                 # Vite + PWA plugin config
└── index.html
```

<br/>

## 🖥️ Local Development

```bash
# Clone the repo
git clone https://github.com/alirezadavari1/musicar.git
cd musicar

# Install dependencies
npm install

# Start the dev server
npm run dev

# Build for production (outputs to /dist)
npm run build
```

<br/>

## 📦 Deployment

This project is deployed as a static site via **GitHub Pages**, served directly from the `dist/` build output. The PWA service worker (`vite-plugin-pwa`) precaches the entire app shell on first visit, enabling full offline functionality afterward.

<br/>

<div align="center">

### 🌟 If you like this project, consider giving it a star!

<img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&size=18&duration=4000&pause=1500&color=8A2BE2&center=true&vCenter=true&width=500&lines=Made+with+%E2%9D%A4%EF%B8%8F+and+lots+of+%F0%9F%8E%B5;Enjoy+your+music%2C+online+or+off." alt="Footer Typing SVG" />

</div>
