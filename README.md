# ⏱️ Precision Stopwatch & Lap Timer

A sleek, lightweight web-based stopwatch application built with vanilla HTML, CSS, and JavaScript. It features millisecond-level precision, pause/resume capability, and split-lap recording wrapped inside a modern gradient UI.

---

## 🚀 Features

* **High-Precision Timing:** Displays elapsed time in `HH:MM:SS.cs` (hours, minutes, seconds, centiseconds).
* **Smart Dynamic Controls:**
  * **Start / Stop:** Toggles timing with pause and resume retention.
  * **Lap / Reset:** Context-aware actions—records lap splits while running; clears data and resets timer when paused.
* **Lap Recording:** Dynamically appends numbered split times to an on-screen lap list.
* **Modern Aesthetic:** Centered card layout, smooth linear-gradient background, SVG circular frame, and tactile button transitions.
* **Zero Dependencies:** Pure HTML5, CSS3, and modern vanilla JavaScript.

---

## 📁 File Structure

```text
├── index.html       # Document markup, SVG dial, and control buttons
├── style.css        # Layout, typography, gradients, and animations
└── script.js        # Timer calculations, interval handlers, and state management
```

---

## 🕹️ How It Works

| Action | When Stopped | When Running |
| :--- | :--- | :--- |
| **Left Button** | **Start:** Begins time tracking | **Stop:** Pauses current timer |
| **Right Button** | **Reset:** Clears display and wipes lap list | **Lap:** Captures split time to list |

---

## 🛠️ Built With

* **HTML5:** Semantic structuring and SVG graphics.
* **CSS3:** Flexbox alignment, CSS gradients, and responsive sizing.
* **JavaScript (ES6):** Interval management via `setInterval` and `Date` delta calculations to avoid drift.

---

## ⚡ Getting Started

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/your-username/stopwatch.git](https://github.com/your-username/stopwatch.git)
   cd stopwatch
   ```

2. Open `index.html` directly in any web browser, or serve it locally using VS Code's **Live Server** extension.
