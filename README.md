# RETRO TETRIS // BLUETOOTH & MOBILE ARCADE 🕹️⚡

A feature-rich, ultra-responsive, zero-latency **Retro Tetris Arcade** web application built with vanilla HTML5 Canvas, modern CSS (CRT scanlines & retro neon aesthetics), and a Web Audio synthesizer. Optimized for **mobile portrait play** (touch gestures & thumb pad) and **Bluetooth gamepads** (PlayStation DualShock/DualSense, Xbox, and 8BitDo controllers) with ultra-fast 250Hz polling.

🌐 **Play Live:** [https://jeffry-lacanglacang.github.io/Classic-hand-held-game/](https://jeffry-lacanglacang.github.io/Classic-hand-held-game/)

---

## ✨ Key Features

- **🎮 Zero-Latency Bluetooth Gamepad Engine**: Automatically detects and maps controllers (DualShock, DualSense, Xbox, generic HID) via the W3C Gamepad API with custom 250Hz polling, DAS (Delayed Auto Shift), and ARR (Auto Repeat Rate). Includes native vibration/rumble actuator support.
- **📱 Mobile-First Ergonomic UI**: Portrait-optimized layout featuring a responsive flex grid, compact HUD, and an on-screen D-pad with smooth continuous auto-repeat.
- **👆 Direct Touch Board Gestures**: Swipe left/right to move pieces, swipe down for soft drop, flick up for an instant hard drop, and tap to rotate.
- **🎵 Retro Web Audio Synthesizer**: Pure JavaScript Web Audio API sound effects for rotations, soft/hard drops, line clears, level ups, and game overs—no external audio assets required.
- **🎨 Authentic Arcade Aesthetic**: CRT scanlines, vignette overlays, custom neon bevel block rendering, 7-bag randomizer, hold piece mechanics, ghost piece previews, and high-score persistence via `localStorage`.

---

## 🚀 Quick Start / Running Locally

Because this is a completely self-contained **single-file web application**, you do not need any complex build tools, package managers, or bundlers!

1. Clone or download this repository:
   ```bash
   git clone https://github.com/jeffry-lacanglacang/Classic-hand-held-game.git
   ```
2. Open the file directly in any modern web browser or serve it locally via any static server.

---

## 🎮 Controls Reference

| Action | Bluetooth Gamepad | Touch / D-Pad | Keyboard |
| :--- | :--- | :--- | :--- |
| **Move Left / Right** | D-Pad Left / Right | Left / Right D-Pad buttons (or Swipe Left/Right) | `ArrowLeft` / `ArrowRight` (or `A` / `D`) |
| **Soft Drop** | D-Pad Down | Down D-Pad button (or Swipe Down) | `ArrowDown` (or `S`) |
| **Rotate (CW)** | Circle ($\bigcirc$) | Rotate Button ($\circlearrowright$) | `ArrowUp` / `X` / `W` |
| **Hard Drop** | Triangle ($\triangle$) | Drop Button ($\triangle$) (or Flick Up) | `Spacebar` |
| **Hold Piece** | L1 / R1 | Hold Button (`HOLD`) | `C` / `Shift` |
| **Pause / Resume** | Options / Start | Pause / Resume buttons in UI | `P` / `Escape` |

---

## 🛠️ Tech Stack

- **HTML5 Canvas**: High-performance rendering engine with device pixel ratio (DPR) scaling for crisp graphics on Retina/OLED mobile screens.
- **CSS3**: Custom properties, flexbox grid architecture, CSS animations, and CRT visual filters.
- **JavaScript (ES6+)**: Custom 7-bag piece randomizer, collision detection, wall kick logic, high-frequency gamepad polling loop, and Web Audio API synthesizer.

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.