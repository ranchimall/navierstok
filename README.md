# NAVIERSTOK ($NVSTK)
> **Linking AI with Blockchain through Memes and YouTube**

Official webpage for the **NAVIERSTOK** crypto token, designed adhering strictly to the **[RanchiMall Standard UI](https://github.com/ranchimall/standard-ui)** design guidelines and native Web Components architecture.

---

## 🌟 Overview

**NAVIERSTOK** bridges the mathematical elegance of the Millennium Prize Navier-Stokes fluid dynamics equations with artificial intelligence, decentralized finance liquidity mechanics, viral meme culture, and YouTube creator multimedia education within the RanchiMall ecosystem.

---

## 🎨 Standard UI Features Integrated

This webpage uses the native web component architecture and utilities provided by **RanchiMall Standard UI**:

- **Native Web Components**:
  - `<theme-toggle>`: Seamless dark and light theme switching with automatic system detection and local persistence.
  - `<sm-button>`: Modern button components supporting primary, outlined, and no-outline variants with ripple animations (`.interact`).
  - `<sm-input>`: Clean styled text & number inputs.
  - `<sm-popup>`: Modals for DEX trading options, newsletters, and interactive dialogues (`openPopup()`, `hidePopup()`).
  - `<sm-notifications>`: Interactive notification drawer triggered via `notify(message, type)` with audio feedback.
  - `<sm-carousel>`: Responsive touch-and-scroll carousel for memes and creator media showcases.
- **RanchiMall Color Palette & Typography**:
  - Accent colors (`#0D7377` light mode, `#32E0C4` dark mode).
  - Modern typography hierarchy with `Poppins` headings and `Roboto` / `Roboto Mono` body & equations.
- **`main_UI.js` Utilities**:
  - `getRef()`, `notify()`, `getConfirmation()`, `openPopup()`, `hidePopup()`.

---

## 📁 Project Structure

```text
navierstok/
├── assets/
│   └── aggregate.svg           # Standard UI SVG icon sprite
├── css/
│   └── main.css                # Standard UI themed layout & component styles
├── js/
│   ├── main_UI.js              # Standard UI utility library & life-cycle handlers
│   └── components.min.js       # Standard UI native web components
├── notification-sound/
│   ├── notification.mp3        # Audio feedback for alerts
│   └── notification.ogg
├── index.html                  # Main NAVIERSTOK token webpage
└── README.md                   # Project documentation
```

---

## 🚀 How to Run Locally

You can open `index.html` directly in any modern web browser or serve it with any local static HTTP server:

```powershell
# Using Python
python -m http.server 8000

# Or using Node.js npx serve
npx serve .
```

Then visit `http://localhost:8000` in your browser.

---

## 📜 License & Ecosystem

Part of the [RanchiMall](https://ranchimall.net) decentralized ecosystem.
Built with [Standard UI](https://github.com/ranchimall/standard-ui).
