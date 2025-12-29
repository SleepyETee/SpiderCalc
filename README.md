# 🕷️ SpiderCalc

An educational game that teaches **calculus, algebra, and probability** through interactive gameplay. Help a spider navigate through spooky Halloween-themed challenges by solving math problems!

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Phaser](https://img.shields.io/badge/Phaser-3-blueviolet)](https://phaser.io/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)](https://vitejs.dev/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/SleepyETee/SpiderCalc)

## 🎬 Demo

<!-- Add your live demo link here after deployment -->
<!-- 🔗 **[Play Live Demo](https://your-netlify-url.netlify.app)** -->

### Classic Mode
![Classic Mode](public/images/spider%20web.jpg)
<!-- Replace with gameplay GIF: ![Classic Mode Gameplay](assets/classic-mode.gif) -->

### Adventure Mode
<!-- Add Adventure mode screenshot/GIF here -->
<!-- ![Adventure Mode Gameplay](assets/adventure-mode.gif) -->

## ✨ Features

- **Two Game Modes**: Classic probability-based gameplay and Adventure platformer
- **50+ Calculus Questions**: Covering limits, derivatives, and integrals
- **Visual Probability System**: See probability beams that show your chances of success
- **Progressive Difficulty**: Questions scale with your progress
- **Halloween Theme**: Spooky UI with spider mascot, pumpkins, and atmospheric effects
- **Educational Alignment**: Aligned with Common Core and AP Calculus standards

## 🎮 Game Modes

### Classic Mode
Strategic probability-based gameplay on a graph canvas:
- Adjust equations (linear, quadratic, sin, exponential)
- Answer math questions to influence probability distributions
- Fire grappling hooks with probability-weighted outcomes
- Earn combo bonuses for consecutive correct answers

### Adventure Mode
Story-driven platformer with calculus puzzles:
- **Classic Adventure**: Vertical climbing with calculus-triggered jumps
- **Story Adventure**: Narrative-driven scenes with web-swinging mechanics
- Progress through height-based chapters (0-500m)

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The dev server runs at `http://localhost:5173`

## 🛠️ Tech Stack

- **React 18** - UI framework
- **TypeScript** - Type safety
- **Phaser 3** - Game engine for Adventure mode
- **Zustand** - State management
- **Vite** - Build tool
- **Matter.js** - Physics engine

## 📁 Project Structure

```
src/
├── game/           # Phaser scenes and game logic
├── math/           # Probability, calculus, and math utilities
├── state/          # Zustand global store
├── ui/             # React components
├── App.tsx         # Main app with mode switching
└── main.tsx        # Entry point

public/
├── images/         # Game sprites and backgrounds
└── sounds/         # Background music and sound effects
```

## 🎓 Educational Standards

This game aligns with:
- **Common Core**: HSF-IF, HSA-CED, HSS-MD
- **AP Calculus AB**: Limits, derivatives, integrals
- **AP Statistics**: Probability distributions, entropy

## 📝 License

MIT License - see [LICENSE](LICENSE) for details.
