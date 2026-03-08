# HexaMatch

> Interactive fractions-matching game built with HTML5 Canvas and vanilla JavaScript.

[![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange?style=flat-square&logo=html5)](https://html.spec.whatwg.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-Responsive-blue?style=flat-square&logo=css3)](https://www.w3.org/Style/CSS/)

---

## Overview

HexaMatch is an educational game that teaches fractions through interactive hexagon tile matching. Players click hexagon tiles to accumulate a sum that matches a target value within a time limit, combining math practice with engaging gameplay. Built with vanilla JavaScript and HTML5 Canvas, this game demonstrates educational game design principles and provides an enjoyable learning experience.

The game features progressive difficulty levels, visual feedback, and a polished dark-themed interface. It's designed for learners of various ages and skill levels, making fraction concepts tangible and fun through hands-on interaction.

---

## Features

- Click hexagon tiles to match target fraction sums
- Timed rounds (30 seconds) with progressive difficulty
- Fraction-based arithmetic challenges
- Three-life system with retry mechanics
- Real-time score tracking and level progression
- Selection feedback with tile highlighting
- Polished visual design with custom font
- Dark-themed responsive interface
- Toggleable instructions and info panels
- No framework dependencies (vanilla JS only)
- Canvas 2D rendering for smooth performance

---

## Screenshots

> Drop screenshots into `screens/` or the root and they'll render here.

![HexaMatch Game](screens/hexamatch.png)

---

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required

### Play Online

Visit the live game at: https://hexamatch-by-naadir.netlify.app/

### Local Development

```bash
git clone https://github.com/Naadir-Dev-Portfolio/HTML5-Game-Hexamatch.git
cd HTML5-Game-Hexamatch
# Open index.html in your web browser
python -m http.server 8000  # Or use any local server
```

Then navigate to `http://localhost:8000` in your browser.

---

## Tech Stack

- HTML5 Canvas — 2D tile rendering and graphics
- CSS3 — Responsive styling, animations, and layouts
- Vanilla JavaScript (ES6) — Game mechanics and tile generation
- Netlify — Cloud deployment

---

## How It Works

The game displays a target fraction value and a set of hexagon tiles with various fraction values. Players click tiles to add their values to a running sum. When the sum matches the target exactly, they score 10 points and advance to the next round. If they overshoot the target or time runs out, they lose a life and must retry. The difficulty increases with each level, introducing more complex fractions.

---

## Configuration

Gameplay parameters can be customized in the `CONFIG` object at the top of the script block:

- `ROUND_TIME` — Seconds per round (default: 30)
- `TILE_COUNT` — Number of hexagon tiles (default: 8)
- `TILE_RADIUS` — Hexagon size in pixels (default: 44)
- `FONT_TILE` — Font for tile labels
- `FONT_HUD` — Font for HUD text

---

## Related Projects

- [HTML5-Game-Algebraverse](https://github.com/Naadir-Dev-Portfolio/HTML5-Game-Algebraverse)
- [HTML5-Game-LogicGrid](https://github.com/Naadir-Dev-Portfolio/HTML5-Game-LogicGrid)
- [HTML5-Game-RainDrops](https://github.com/Naadir-Dev-Portfolio/HTML5-Game-RainDrops)
