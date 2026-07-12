# 🕉️ Mala Jaap Pro Tracker

A modern, feature-rich digital mala (prayer beads) counter for mindful mantra chanting. Track your daily progress, set goals, and visualize your practice with a stunning glass-morphism UI — all without any server or internet dependency. **100% private — data stored locally in your browser.**

![Mala Jaap Pro Tracker](https://img.shields.io/badge/version-3.0-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Made with](https://img.shields.io/badge/made%20with-HTML%2FCSS%2FJS-orange)

---

## ✨ Features 

### 🎯 Dynamic Mala Wheel
- Beads automatically adjust to your **daily target** (set 51, 108, 500, or any number)
- Tap anywhere on the wheel to add +1 jaap
- Visual feedback with active/inactive beads
- **Center shows current count** (not remaining) — increases with each tap

### 📊 Smart Progress Ring
- Circular gauge showing **real-time progress** toward daily target
- Visual indicator of how close you are to your goal
- Glows when target is complete

### 🔥 Streak Counter
- Tracks **consecutive days** of chanting
- Encourages daily consistency
- Displayed as a fire badge in the header

### ⏱️ Smart Timer
- **Auto-starts** on first tap
- **Auto-pauses** after 3 seconds of inactivity
- Manual start/pause with button or `Space` key
- Session time shown in real-time

### 🕉️ Multiple Mantras
- 3 pre-loaded mantras:
  - "Om Hanumate Namah"
  - "Shree Ram Jai Ram Jai Jai Ram"
  - "Om Brim Brihaspataye Namah"
- Easy switching with arrow buttons or `N`/`P` keys
- Each mantra's count tracked separately

### 📈 Today's Stats (Bar Chart)
- Mantra-wise breakdown for today
- Visual bars for quick comparison
- Instantly see which mantra you've chanted most

### 📅 Last 7 Days Chart
- Mini bar chart showing daily totals
- Spot patterns in your practice
- Quick glance at weekly consistency

### 📊 Total Per Mantra + Grand Total
- Lifetime count for each mantra
- Combined grand total of all jaaps
- Persistent across sessions

### ✅ Complete Button
- Saves current count (even if less than target)
- Automatically records data for today
- Starts a new round instantly

### 🎉 Confetti Celebration
- Burst of confetti when you complete a round or hit target
- Makes practice rewarding

### 🛡️ Data Privacy
- **100% private** — all data stored in your browser's `localStorage`
- No server, no tracking, no internet required
- Data survives browser restarts
- Auto-saves every 10 seconds

### ⌨️ Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `→` / `+` | +1 jaap |
| `←` / `-` | -1 jaap |
| `↑` | +5 jaap |
| `↓` | -5 jaap |
| `Space` | Start/Pause timer |
| `C` | Complete round |
| `R` | Reset all |
| `N` | Next mantra |
| `P` | Previous mantra |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure |
| **CSS3** | Glass-morphism styling with dark/light themes support |
| **Vanilla JavaScript** | Logic, Canvas rendering, Charts |
| **Canvas API** | Mala wheel rendering |
| **localStorage** | Data persistence (no server needed) |
| **Font Awesome** | Icons |
| **Google Fonts (Inter)** | Modern typography |

---

## 🚀 How to Use

1. **Set Target** — Click the "Target" button and set your daily goal
2. **Tap the Mala** — Tap anywhere on the wheel to add +1 jaap
3. **Switch Mantra** — Use arrow buttons or `N`/`P` keys
4. **Complete Round** — Click "Complete" to save current count (even if less than target)
5. **Timer** — Auto-starts on first tap, pauses after inactivity
6. **Track Progress** — See real-time updates on ring, charts, and badges

---

## 💾 Data Storage

All data is stored in your browser's `localStorage` under these keys:

| Key | Purpose |
|-----|---------|
| `mala_jaap_data_v3` | Main database (all history) |
| `mala_session_v3` | Current session |
| `mala_settings_v3` | User settings (target) |
| `mala_counters` | Quick state |

### How to View Your Data
1. Open DevTools (`F12`)
2. Go to **Application** → **Local Storage**
3. Look for the keys above

---

## 📁 Project Structure
mala-jaap-pro/
├── index.html (Single file — everything included)
├── README.md (This file)
└── .gitignore (Git ignore rules)


---

## 🔧 How to Run Locally

1. Download or clone this repository
2. Open `index.html` in your browser
3. Start chanting! 🕉️

**No build tools, no npm install, no server required.**

---

## 🌐 Live Demo

[https://deepakkapoor553-ctrl.github.io/Mala-Jaap-Counter-Pro/](https://deepakkapoor553-ctrl.github.io/Mala-Jaap-Counter-Pro/)

---

## 📸 Screenshots

> *Add a screenshot here: `![Screenshot](screenshot.png)`*

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/deepakkapoor553-ctrl/Mala-Jaap-Counter-Pro/issues).

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

MIT License — Free to use, modify, and distribute.

---

## 🙏 Credits

- **Font Awesome** for icons
- **Google Fonts (Inter)** for typography
- Inspired by daily mantra practice

---

**Om Shanti** 🕉️
