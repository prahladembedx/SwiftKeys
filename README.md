# ⌨ SwiftKeys — Typing Speed Test App

> A feature-rich, beautiful typing test application built with pure HTML, CSS, and JavaScript — no frameworks, no build tools, just open and type.

![SwiftKeys Preview](https://img.shields.io/badge/SwiftKeys-v1.0-e2b714?style=for-the-badge&logo=keyboard&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🚀 Features

### ⏱ Test Modes
- **Time Mode** — 15s / 30s / 60s / 120s
- **Word Count Mode** — 10 / 25 / 50 / 100 words

### 📊 Real-Time Stats
- Live **WPM** (Words Per Minute)
- Live **Accuracy** percentage
- Live **Error** count
- Countdown timer

### ✍ Content Modes
- **Words** — Common English words (Easy / Medium / Hard difficulty)
- **Quotes** — Famous inspirational quotes
- **Code** — Programming snippets (JS, Python, SQL, React)

### 🎨 5 Beautiful Themes
| Theme | Description |
|-------|-------------|
| 🌑 Dark | Sleek dark with golden accent (default) |
| ☀️ Light | Clean white with amber accent |
| 💻 Hacker | Matrix-style green on black |
| 🧛 Dracula | Purple-accented dark theme |
| 🌊 Ocean | Deep blue with cyan accent |

### ⚙ Customization
- **Punctuation toggle** — Add commas, periods, question marks
- **Numbers toggle** — Include random numbers in words
- **Hard Mode** — Backspace disabled (no corrections!)
- **Sound Effects** — Satisfying click sounds via Web Audio API
- **3 Caret Styles** — Line │, Block █, Underline _

### 📈 Results Screen
- Detailed WPM, Accuracy, Consistency, Errors breakdown
- **WPM-over-time chart** (Chart.js)
- Correct words and characters count
- New Personal Best detection

### 🏆 Achievements (14 total)
- Speed milestones (50, 75, 100, 120 WPM)
- Accuracy milestones (95%, 100%)
- Test streaks (5, 10, 50 tests)
- Special challenges (Zero Mistakes, Hard Mode finisher, Code Monkey, Marathon)

### 📋 Stats & History
- Last 20 tests in a history table
- Progress chart (WPM + Accuracy trends)
- All-time Personal Best
- Average WPM and accuracy (last 10 tests)
- Total words typed counter

### 🥇 Leaderboard
- Top 20 scores saved locally
- Enter your name and track your rank
- Medal system (🥇🥈🥉) for top 3

### ⌨ Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `Tab` | Restart test |
| `Esc` | Reset test |
| `Space` | Submit word and move to next |
| `Backspace` | Delete character (disabled in hard mode) |

---

## 🛠 Tech Stack

| Component | Technology |
|-----------|------------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Charts | Chart.js 4.4 |
| Fonts | JetBrains Mono, Bebas Neue (Google Fonts) |
| Sound | Web Audio API |
| Storage | localStorage |
| Hosting | Any static file server / GitHub Pages |

---

## 🚀 Getting Started

### Option 1 — Open directly
```bash
# Just open the file in your browser!
open index.html
```

### Option 2 — Local server
```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve .

# Using VS Code — Install Live Server extension and click Go Live
```

Then visit `http://localhost:8080`

### Option 3 — GitHub Pages
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your app is live at `https://yourusername.github.io/swiftkeys`

---

## 📁 Project Structure

```
SwiftKeys/
├── index.html          # Complete app (single file)
└── README.md           # This file
```

SwiftKeys is intentionally a **single HTML file** — making it ultra-portable. Drop it anywhere and it works.

---

## 🎯 Roadmap / Future Features

- [ ] Multiplayer race mode (WebSockets)
- [ ] Custom word list upload
- [ ] More language support (Hindi, Spanish, French)
- [ ] PWA support (installable as mobile app)
- [ ] Export stats as CSV
- [ ] Custom theme editor
- [ ] Replay past tests

---

## 🤝 Contributing

Pull requests are welcome!

```bash
git clone https://github.com/yourusername/swiftkeys.git
cd swiftkeys
# Edit index.html
# Open in browser to test
```

---

## 📄 License

© prahladembedX --- All Rights Reserved.

 — If you like it, give it a star on GitHub!
