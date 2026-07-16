[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

本项目的源代码采用 [GNU General Public License v3.0](LICENSE) 进行许可。

# Draw-My-World
This is an extremely powerful image-to-command-block painting platform for Minecraft Bedrock Edition, named "Draw My World". Simply put, you can upload any image, and the tool will automatically quantize it into pixel art made of Minecraft blocks, then output a chain of command block commands ready to be used directly in the game.

**Convert any image into a Minecraft Bedrock command-block painting – entirely in your browser.**

No installation, no uploads – all processing stays local. Customize palettes, color matching algorithms, dithering, and generate ready‑to‑run command chains.

![Screenshot](screenshot.png) <!-- replace with your screenshot -->

---

## ✨ Features

- **100% Local & Private** – everything runs in your browser; no data is ever sent to any server.
- **Rich Color Metrics** – OKLab, OKLCH, CIEDE2000, CIE94, CMC, ΔE76, IPT, luma‑weighted, hue‑weighted, linear RGB, sRGB, and more.
- **Flexible Palettes** – built‑in presets (legacy 84‑block, safe modern, vivid, natural, etc.) plus manual toggling for each block group.
- **Smart Quantization & Dithering** – Floyd‑Steinberg, Atkinson, Sierra Lite, Bayer 4×4, blue‑noise, with edge protection and texture awareness.
- **Live Preview & Editing** – three linked views (source, quantized, game‑like render) with brush, smart restore, fill, replace, eraser, and undo/redo.
- **Command Generation** – auto‑generates a complete command‑block chain with adjustable tick delay, scoreboard name, air‑only placement, and optional base‑color compression.
- **Extra Utilities** – pixel inspector, manual gap markers, compression analysis, JSON export, and a fully responsive mobile UI.

---

## 🚀 Quick Start

### Online
Open the [live demo](https://crimsonfollower.github.io/draw-my-world) (if deployed) directly.

### Local
Just download the single `index.html` and open it in any modern browser:
```bash
git clone https://github.com/CrimsonFollower/draw-my-world.git
cd draw-my-world
# open index.html in your browser
