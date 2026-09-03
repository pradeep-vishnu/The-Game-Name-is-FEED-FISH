# 🐟 Feed Catfish

A fast-paced, minimalist HTML5 arcade survival game built entirely in a single file with zero dependencies. Balance gravity, hunt golden insect swarms, and dodge predators in a living, procedurally generated ocean.

## 🏷️ Topics
`html5-game` `canvas-api` `vanilla-javascript` `arcade-game` `web-audio-api` `procedural-generation` `zero-dependencies` `responsive-design`

---

## 🎮 Play the Game
**No installation required!** 
Simply download or clone this repository and open `index.html` in any modern desktop or mobile browser. 

👉 **[Play Live Demo]** *(Link your GitHub Pages URL here if you host it)*

---

## 📖 How to Play

You control a powerful, mature catfish swimming continuously forward. The ocean current accelerates the longer you survive.

*   **Controls:** Press **ANY KEY**, **CLICK**, or **TAP** anywhere on the screen to thrust upwards.
*   **The Physics:** Gravity constantly pulls you down. Balance your upward thrusts to stay in the safe middle waters.
*   **The Reward:** Leap out of the water to catch golden flying insects. Catch multiple in quick succession to trigger massive Combo multipliers!
*   **The Danger:** 
    *   **Sharks:** Prowl the deep waters. Don't sink too low!
    *   **Vultures:** Patrol the sky ceiling. Don't jump too high!

---

## ✨ Features

*   **Zero Dependencies:** 100% pure Vanilla JavaScript, HTML, and CSS. No React, no Phaser, no external libraries.
*   **No External Assets:** Every visual element (catfish, sharks, vultures, plants, particles) is procedurally drawn using the HTML5 `<canvas>` API.
*   **Procedural Web Audio:** Sound effects (splashes, jumps, insect catches, death) are synthesized in real-time using the Web Audio API—no `.mp3` or `.wav` files required.
*   **Crash-Proof Architecture:** Features strict DOM-memory management and audio garbage collection to prevent crashes during intense high-speed gameplay.
*   **Session Analytics:** Tracks your runs and renders a beautiful, custom-built line graph of your score progression directly on the canvas.
*   **Progression System:** Includes locally saved Personal Bests and a fully animated Achievement unlock system.
*   **Responsive:** Scales perfectly to any screen size, supporting both desktop monitors and mobile touch screens seamlessly.

---

## 🛠️ Technical Details

This project is an exploration of minimalist game development. The goal was to create a fully polished, responsive, and highly replayable arcade experience using only native browser APIs. 

*   **Game Loop:** Powered by `requestAnimationFrame` with delta-time clamping for consistent physics across different refresh rates.
*   **Procedural Generation:** The ocean floor, plant life, background fish, and predator spawn rates are generated dynamically based on survival time and current speed.
*   **Storage:** Uses browser `localStorage` to safely persist high scores and achievements between sessions.

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to fork, modify, and learn from the code!
