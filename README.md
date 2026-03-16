<div align="center">

# ⌨️ Typer

**A real-time typing speed test that measures your WPM and accuracy**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

</div>

---

## 📖 About

Typer is a minimalist typing speed test built with vanilla JavaScript. It generates random English words and tracks your typing performance in real-time over a 30-second session, showing WPM (Words Per Minute) and highlighting correct/incorrect characters as you type.

## ✨ Features

- **30-second timed rounds** — focused, sprint-style typing sessions
- **Real-time WPM calculation** — updates live as you type
- **Character-level feedback** — each letter highlighted green (correct) or red (incorrect)
- **200-word pool** — randomized word selection from a curated list
- **Auto-scrolling** — word display shifts as you progress through lines
- **Pause & resume** — take a break mid-session without losing progress
- **Instant reset** — start a new game anytime

## 🏗️ Architecture

```
Typer/
├── index.html      # Game layout and word display container
├── typing.js       # Core game engine — timer, WPM calc, input handling
└── styles.css      # Styling with current-word highlighting & animations
```

The game engine handles keyboard events directly, comparing each keystroke against the expected character and advancing through words as they're completed.

## 🚀 Getting Started

```bash
git clone https://github.com/Emrebym/Typer.git
cd Typer
open index.html      # or use Live Server in VS Code
```

No build step or dependencies required — pure vanilla JS.

## 📝 License

MIT
