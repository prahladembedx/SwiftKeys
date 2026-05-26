# ⌨ SwiftKeys — Typing Speed Test App

> A feature-rich, beautiful typing test application — pure HTML, CSS, and JavaScript. No frameworks, no build step. Just open and type.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🚀 Features

### ⏱ Test Modes
- **Time Mode** — 15s / 30s / 60s / 120s
- **Word Count Mode** — 10 / 25 / 50 / 100 words
- **⬆ Flow Mode** — One word at a time, scrolls upward

### 🌍 Multi-Language Support
| Language | Script | Difficulty Levels |
|----------|--------|-------------------|
| 🇬🇧 English | Latin | Easy / Medium / Hard |
| 🇮🇳 Hindi | देवनागरी (Devanagari) | Easy / Medium / Hard |
| 🇪🇸 Spanish | Latin + accents | Easy / Medium / Hard |
| 🇫🇷 French | Latin + accents | Easy / Medium / Hard |

### 📁 Custom Word List Upload
- Upload any `.txt` file (drag & drop or click)
- Or paste words directly in the text area
- Words separated by newline, comma, or space
- Preview first 30 words before using

### 📊 Real-Time Stats
- Live WPM, Accuracy %, Error count, Countdown timer
- Detailed results: Consistency score, Correct words/chars

### ✍ Content Modes
- **Words** — Common vocabulary by difficulty
- **Quotes** — Famous inspirational quotes
- **Code** — JS, Python, React, SQL snippets
- **Flow** — Categories: Animals, Names, Countries, Colors, Fruits, Cities, Numbers

### 🎨 5 Themes
| Theme | Preview |
|-------|---------|
| 🌑 Dark | Dark bg, golden accent |
| ☀️ Light | Clean white, amber accent |
| 💻 Hacker | Matrix green on black |
| 🧛 Dracula | Purple-accented dark |
| 🌊 Ocean | Deep blue with cyan |

### ⚙ More Features
- Punct / Numbers / Hard Mode (no backspace) toggles
- Sound effects via Web Audio API
- 3 caret styles (Line, Block, Underline)
- 14 Achievements to unlock
- Stats tab with progress chart
- Local Leaderboard with medal system
- **PWA** — Install as desktop app (on HTTPS)
- `Tab` to restart, `Esc` to reset

---

## 📁 Project Structure

```
swiftkeys/
├── index.html              ← Complete app (all-in-one)
├── package.json            ← Project metadata & scripts
├── .gitignore              ← Git ignore rules
├── README.md               ← This file
└── .github/
    └── workflows/
        └── deploy.yml      ← Auto-deploy to GitHub Pages
```

> SwiftKeys is intentionally a **single HTML file** — ultra-portable, zero dependencies at runtime.

---

## 🎯 Roadmap

- [ ] Multiplayer race mode (WebSockets)
- [ ] More languages (German, Japanese, Arabic)
- [ ] Export stats as CSV
- [ ] Custom theme editor
- [ ] Mobile keyboard support

---

## 📄 License

MIT — use it, modify it, share it freely.

---

Made with ❤️ — Star ⭐ the repo if you like it!
