# 🕉️ Mala Jaap Pro Tracker

A beautiful, interactive digital mala (prayer beads) counter designed for mindful mantra chanting. Track your daily progress, set goals, and visualize your practice with stunning glass-morphism UI — all without any server or internet dependency.

## ✨ Key Features

### 🎯 Dynamic Mala Wheel
- Beads automatically adjust to your **daily target** (set 51, 108, 500, or any number)
- Tap anywhere on the wheel to add +1 jaap
- Visual feedback with active/inactive beads
- Completion ring animation when target is met

### 📊 Smart Progress Ring
- Circular gauge showing **real-time progress** toward daily target
- Displays remaining count and target value
- Glows when target is complete

### 🔥 Streak Counter
- Tracks **consecutive days** of chanting
- Encourages daily consistency
- Displayed as a fire badge

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

## 🛠️ Tech Stack

- **HTML5** — Structure
- **CSS3** — Glass-morphism styling
- **Vanilla JavaScript** — Logic, Canvas, Charts
- **Canvas API** — Mala wheel rendering
- **localStorage** — Data persistence
- **Font Awesome** — Icons
- **Google Fonts (Inter)** — Typography

## 🚀 How to Use

1. **Set Target** — Click the "Target" button and set your daily goal
2. **Tap the Mala** — Tap anywhere on the wheel to add +1 jaap
3. **Switch Mantra** — Use arrow buttons or `N`/`P` keys
4. **Complete Round** — Click "Complete" to save current count
5. **Timer** — Auto-starts on first tap, pauses after inactivity
6. **Track Progress** — See real-time updates on ring, charts, and badges

## 💾 Data Backup & Restore

- All data is stored in `localStorage` under these keys:
  - `mala_jaap_data_v3` — Main database
  - `mala_session_v3` — Current session
  - `mala_settings_v3` — User settings
  - `mala_counters` — Quick state
- To backup: Open DevTools → Application → Local Storage → copy keys
- To restore: Paste keys back

## 📁 Project Structure

```
mala-jaap-pro/
├── index.html          (Single file — everything included)
├── README.md           (This file)
└── .gitignore          (Git ignore rules)
```

## 📄 License

MIT License — Free to use, modify, and distribute.

## 🙏 Credits

Made with ❤️ for daily mantra practice.

---

**Om Shanti** 🕉️
