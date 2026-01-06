# 🌌 NEON BREACH

**Neon Breach** is a high-speed cyberpunk FPS built specifically for Chromebook web browsers using Three.js. Navigate shifting sectors, manage your system integrity, and customize your controls for the ultimate arena experience.

## 🕹️ Quick Start
1. Download `index.html`.
2. Open it in Chrome.
3. Enter your Codename and choose a Sector (Labyrinth, Courtyard, or Gauntlet).
4. Hit **Initialize** to enter the simulation.

## ⌨️ Controls (Customizable)
* **WASD**: Movement
* **SHIFT**: Dash (Speed boost)
* **C / CTRL**: Crouch (Lower profile)
* **SPACE**: Jump
* **LEFT CLICK**: Shoot
* **ESC**: Open Menu / Settings

## 🛠️ Features
* **Modular Map System**: Level layouts are generated from data arrays.
* **Smart Collision**: Distance-based wall physics for smooth movement.
* **Persistent Settings**: Your custom keybinds are saved to `localStorage`.
* **Minimap HUD**: Real-time position tracking.

## 📝 Developer Log
* **Performance**: Optimized with wireframe geometry and distance fog to ensure smooth 60FPS on low-end hardware.
* **Collision Logic**: Implemented a custom vector-bounce system to prevent "wall-clipping" without needing a physics library.
* **UI/UX**: Designed with a "Neon-on-Black" aesthetic to maximize visual clarity on standard LCD screens.

---
Created as an open-source web project.