<div align="center">

# 🐟 Fish Life Adventure

**An educational aquarium ecosystem game built with HTML5 Canvas and vanilla JavaScript**

[![Play Now](https://img.shields.io/badge/🎮_Play_Now-Live_Demo-667eea?style=for-the-badge)](https://tonytheg.github.io/fish-life-adventure/)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

*Keep a fish healthy by finding oxygen, avoiding pollution, and caring for its habitat.*

</div>

---

## 🌎 About the Game

**Fish Life Adventure** is an educational game for elementary and middle school students. You guide one fish through an aquarium and learn how environmental conditions affect living things.

Swim through clean water, collect oxygen bubbles near plants, and avoid polluted water and floating trash. Plants and oxygen sources help the fish recover, while pollution and debris reduce its health and oxygen. The goal is to keep the fish alive until the timer ends.

### Learning Focus

- 🌱 **Earth and life science** — A healthy habitat is necessary for life.
- 💧 **Ecosystem awareness** — Pollution changes the conditions organisms need to survive.
- 💻 **Digital literacy** — Players learn through interactive feedback, health, oxygen, and time indicators.

---

## 🎮 Gameplay

The fish begins in an aquarium with plants, oxygen bubbles, moving water, polluted areas, and floating trash. Use clean areas and plants to maintain oxygen; avoid hazards that drain health and oxygen.

The game ends when the three-minute timer finishes or when the fish loses all health. The end screen reinforces the connection between clean habitats and survival.

### Controls

| Key | Action |
|-----|--------|
| `↑` `↓` `←` `→` or `W` `A` `S` `D` | Swim |
| `Space` | Start or restart the game |

### Environmental Conditions

- 🫧 **Oxygen bubbles and plants** replenish oxygen.
- 🌊 **Clean water** provides a safer place to explore.
- ☁️ **Polluted water** lowers oxygen and health.
- 🗑️ **Floating trash** damages the fish and can create additional hazards.
- ❤️ **Health and oxygen bars** give immediate feedback about the fish's condition.

---

## ✨ Features

- 🎨 Pixel-art aquarium rendered with HTML5 Canvas
- 🫧 Interactive oxygen, plant, pollution, and trash systems
- ❤️ Health and oxygen management with a timed survival goal
- 💬 Contextual tips and clear start, win, and game-over states
- 🖥️ Single-file browser game with no build step or external dependencies

---

## 🚀 Play or Run Locally

### Play Online

👉 **[Play Fish Life Adventure](https://tonytheg.github.io/fish-life-adventure/)** — no download required.

### Run Locally

```bash
git clone https://github.com/tonytheg/fish-life-adventure.git
cd fish-life-adventure
```

Open `index.html` in a browser. No installation, build tools, or framework are required.

---

## 🏗️ Technical Details

The game is implemented in a single HTML file using browser-native technology:

- **HTML5 Canvas API** for pixel-art rendering
- **Vanilla JavaScript** for the game loop, input, state, and interactions
- **`requestAnimationFrame`** for smooth rendering updates
- **Axis-aligned bounding-box collision detection** for the fish and hazards
- **A 320 × 180 canvas scaled 3×** for crisp pixel visuals
- **A state machine** for the menu, gameplay, win, and game-over screens

---

## 📁 Project Structure

```text
fish-life-adventure/
├── index.html      # Complete game: HTML, CSS, and JavaScript
├── README.md       # Project documentation
└── LICENSE         # MIT License
```

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

