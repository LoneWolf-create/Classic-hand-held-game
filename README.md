♤Retro Tetris & Bluetooth Mobile Arcade
A high-performance, fully self-contained retro Tetris arcade web application optimized for mobile touchscreens, desktop browsers, and zero-latency Bluetooth gamepads. Built as a clean, single-file HTML/CSS/JavaScript architecture with zero external build dependencies or server requirements.

■Core Features

●Zero-Latency Bluetooth Gamepad Support
Designed for seamless compatibility with PlayStation (DualShock 4 / DualSense), Xbox, 8BitDo, and generic Bluetooth HID controllers across Android Chrome/WebView and desktop environments. Features high-frequency 250Hz polling, automatic hat-switch axis fallback, Delayed Auto Shift (DAS), Auto Repeat Rate (ARR), and physical controller rumble feedback on supported devices.

●Responsive Mobile Arcade Interface
Features an ergonomic portrait-optimized layout with responsive screen sizing, custom touch controls, thumb-pad clusters, and direct on-board swipe gestures for instant hard drops, soft drops, continuous lateral movement, and rotations.

●Retro Web Audio Synthesizer
Includes a fully procedural retro sound effects engine built directly on the Web Audio API, generating authentic square and triangle wave audio tones for piece movements, rotations, holds, soft drops, hard drops, line clears, level increases, and game over sequences without relying on external audio assets.

●Classic Gameplay Mechanics & Enhancements
Implements the official 7-bag randomizer piece distribution algorithm, next piece preview, hold piece mechanics, ghost piece projection, line clear flash animations, progressive difficulty scaling, and persistent high score tracking utilizing local storage.

●Authentic CRT Arcade Aesthetic
Wrapped in a custom retro cabinet styling complete with dynamic CRT scanlines, chromatic aberration simulation, vignette overlays, and crisp arcade typography powered by Google Fonts.

●Getting Started & Usage
Because this application is engineered as a pure, self-contained single file, running or deploying it requires no complex toolchains, package managers, or build steps.
To run the project locally, simply clone the repository and open the index.html file directly in any modern web browser such as Chrome, Firefox, Safari, or Edge.
To deploy the application for web hosting, upload index.html to any static hosting provider like GitHub Pages, Vercel, Netlify, or any local web server.

●Controls Reference
Keyboard controls include the Left and Right Arrow keys or A and D for lateral movement, the Down Arrow or S for soft drop, the Up Arrow, W, or X for clockwise rotation, Z for counter-clockwise rotation, C or Shift for holding pieces, and the Spacebar for instant hard drops. The P key, Escape, or the Options button on a connected gamepad toggles pause mode.
Touch and gamepad controls map intuitively to the on-screen arcade cabinet interface, allowing seamless transitions between touch inputs and physical Bluetooth controllers.
