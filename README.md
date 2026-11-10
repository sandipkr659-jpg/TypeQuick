# ⌨️ TypeQuick

A minimalist, aesthetic, distraction-free typing speed test built with pure HTML, modern CSS, and vanilla JavaScript. Inspired by clean developer-first interfaces like Monkeytype and Apple Human Interface guidelines.

---

## ✨ Features

- **Distraction-Free Minimalist UI**: Clean, focus-inducing design with calm typography and zero visual noise.
- **Dark & Light Mode**: Seamless one-click theme switcher with persistent preference saving in `localStorage`.
- **Typography**: Paired with Google's **JetBrains Mono** for monospaced typing precision and **Inter** for clean UI chrome.
- **Segmented Time Selectors**: Quick pill controls for 1 min, 2 min, and 3 min test durations.
- **Real-Time Telemetry**:
  - Live Words Per Minute (WPM) calculation.
  - Accuracy percentage tracking.
  - Mistake counter with subtle inline highlights.
  - Countdown timer.
- **Live Progress Bar**: A hairline progress indicator along the top edge showing test completion in real-time.
- **Caps Lock Alert**: Automatic detection and discrete badge warning if Caps Lock is accidentally active.
- **Performance Sparkline**: End-of-test results modal featuring an SVG area chart visualizing your WPM pace over time and Peak WPM.
- **Smooth Caret**: Sub-pixel accurate pulsing caret with auto line-centering scroll.
- **Auto-Start**: Begin typing immediately without having to click the start button.
- **Zero Dependencies**: Pure HTML5, modern CSS3, and vanilla ES6 JavaScript. No frameworks or heavy libraries.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| <kbd>Any Key</kbd> | Automatically starts the test |
| <kbd>Tab</kbd> | Instantly restart & refocus test |
| <kbd>Esc</kbd> | Close results modal / reset |
| <kbd>Backspace</kbd> | Correct the previous letter |

---

## 🚀 Getting Started

### Run Locally

Simply double-click `index.html` or open it in any modern browser:

```bash
# Clone the repository
git clone git@github.com:YOUR_USERNAME/Type-Quick.git

# Navigate to the folder
cd Type-Quick

# Open in browser (Windows PowerShell)
Start-Process index.html
```

---

## 🌐 Deploy to GitHub Pages (Free Live Hosting)

1. Push this repository to GitHub.
2. Go to repository **Settings** → **Pages** (in the left sidebar).
3. Under **Branch**, select `main` and `/ (root)`.
4. Click **Save**.
5. Your live app will be published at:
   `https://YOUR_USERNAME.github.io/Type-Quick/`

---

## 📁 Project Structure

```text
Type-Quick/
├── index.html       # Main application entry point
├── p2.html          # Standalone application file
├── README.md        # Documentation
└── .gitignore       # Git ignore rules
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

