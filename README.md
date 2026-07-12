<div align="center">

# 🐟 Fish Life Adventure

**A pixel-art ocean survival game built with HTML5 Canvas and vanilla JavaScript**

[![Play Now](https://img.shields.io/badge/🎮_Play_Now-Live_Demo-667eea?style=for-the-badge)](https://tonytheg.github.io/fish-life-adventure/)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

<br/>

*Survive the ocean depths. Eat smaller fish. Grow bigger. Evolve.*

</div>

---

## 🎮 Gameplay

You start as a tiny fish in a vast ocean. Your goal is to **eat fish smaller than you** to grow, while **avoiding predators** that are larger. As you grow, you'll evolve through multiple life stages and unlock the ability to take on bigger prey.

### Controls
| Key | Action |
|-----|--------|
| `↑` `↓` `←` `→` | Move your fish |
| `Space` | Dash / Boost |

### Features
- 🎨 **Pixel-art graphics** — Retro-style visuals with smooth animations
- 🌊 **Dynamic ocean environment** — Scrolling backgrounds with depth layers
- 📈 **Growth system** — Eat fish to grow larger and evolve
- 🐠 **Multiple fish types** — Different species with unique behaviors and speeds
- 🏆 **Score tracking** — Track your survival time and fish eaten
- ⚡ **Dash mechanic** — Boost to catch prey or escape predators
- 🎵 **Responsive design** — Scales to fit any screen size

---

## 🚀 Quick Start

### Play Online
👉 **[Click here to play instantly](https://tonytheg.github.io/fish-life-adventure/)** — no download required!

### Run Locally
```bash
# Clone the repository
git clone https://github.com/tonytheg/fish-life-adventure.git
cd fish-life-adventure

# Open in your browser (no build step needed!)
open index.html
# or on Windows:
start index.html
```

> **Zero dependencies** — This is a single-file HTML5 game. No npm, no build tools, no framework. Just open and play.

---

## 🏗️ Technical Details

### Architecture
The entire game is built in a **single HTML file** (~900 lines) using:

- **HTML5 Canvas API** for rendering
- **Vanilla JavaScript** for game logic
- **No external dependencies** — pure browser APIs

### Key Implementation Details
- **Game Loop** — `requestAnimationFrame`-based 60fps render loop
- **Collision Detection** — Axis-aligned bounding box (AABB) detection
- **Entity System** — Object-oriented fish entities with individual AI behaviors
- **Scaling** — Canvas scales 3x from 320×180 native resolution for crisp pixel art
- **State Machine** — Menu → Playing → Game Over state management

---

## 📁 Project Structure

```
fish-life-adventure/
├── index.html      # Complete game (HTML + CSS + JS in one file)
├── README.md       # This file
└── LICENSE         # MIT License
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs via [Issues](https://github.com/tonytheg/fish-life-adventure/issues)
- 💡 Suggest new features
- 🔧 Submit pull requests

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Made with ❤️ and JavaScript**

⭐ Star this repo if you enjoyed the game!

</div>
