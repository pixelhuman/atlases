# 🎮 ATLAS FORGE

**A free online texture atlas tool for game developers**

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-2.6-green.svg)
![Built with](https://img.shields.io/badge/built%20with-HTML%2FCSS%2FJS-orange.svg)
![Made by](https://img.shields.io/badge/made%20by-Qwen3.8--Max-purple.svg)

> Pack loose sprites into tight atlases. Analyze any spritesheet frame by frame. 100% in-browser — no uploads.

---

## 🌐 Live Demo

**[▶ Try it now at pixelhuman.github.io/atlases/](https://pixelhuman.github.io/atlases/)**

---

## ✨ Features

### 001 — Texture Packer
- **MaxRects bin-packing** algorithm for optimal sprite placement
- Adjustable **padding** (0-8px) and edge **extrude** (0-4px)
- **Trim transparency** to save space
- Optional **90° rotation** for tighter packing
- **Power-of-two** atlas sizes or auto-fit
- Export to **PNG + JSON** (Phaser, PixiJS, Godot, Unity compatible)

### 002 — Atlas Analyzer
- **Frame-by-frame scan** of any spritesheet/atlas
- **Auto-detects** every sprite with flood-fill algorithm
- Measures **width × height** of each frame
- Draws bounding **frames** over the atlas
- Rebuilds **JSON** from detected sprites
- Supports **transparent** or **color-key** backgrounds
- Hover to inspect individual frames

### 003 — JSON Formats
- Phaser/TexturePacker **hash** format
- **Array** format
- **Simple** format with frame coordinates
- Direct copy or download

---

## 🎨 Design

Styled after **Henry Northington's portfolio** with:
- Retro pixel aesthetic
- CRT scanline overlay
- 8-bit fonts (Press Start 2P, VT323)
- Terminal-style UI
- Grid background pattern
- Glitch effects

---

## 🚀 How to Use

### Pack Sprites
1. Drag & drop sprite PNGs (or load demo)
2. Adjust padding, extrude, rotation settings
3. Click **FORGE ATLAS**
4. Download PNG + JSON

### Analyze Atlas
1. Drop any spritesheet/atlas image
2. Choose background mode (transparent or color-key)
3. Adjust alpha threshold and merge gap
4. Click **ANALYZE FRAMES**
5. View detected frames + download JSON

---

## 🛠️ Technical

- **Pure HTML/CSS/JavaScript** — no build tools needed
- **Canvas API** for image processing
- **Web Audio API** for retro SFX
- **No external dependencies** (except Google Fonts)
- **100% client-side** — your images never leave your browser

---

## 📦 Installation

Just clone and open `index.html` in your browser:

```bash
git clone https://github.com/pixelhuman/atlases.git
cd atlases
open index.html
