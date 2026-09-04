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
