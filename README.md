# 🛡️ Online Proctoring Detection

A sleek, modern, and browser-based proctoring system built with just **HTML**, **CSS**, and **JavaScript** — no frameworks, no dependencies. Logs tab switches, fullscreen exits, mouse movements, keyboard activity, dev tools usage, and more.


---

## 🎯 Features

| Category                     | What it Does                                                   |
|-----------------------------|-----------------------------------------------------------------|
| 🔄 Tab & App Switch Logs     | Detects if the user switches tabs or leaves the browser window |
| 🖱️ Mouse Movements           | Tracks real-time mouse coordinates                             |
| ⌨️ Keyboard Presses          | Logs every key pressed                                          |
| 📺 Fullscreen Detection      | Detects when the user exits fullscreen mode                    |
| 🖥️ Multiple Monitor Check    | Estimates if the user is on a dual-screen setup                |
| 🔍 DevTools Detection        | Alerts when Inspect Element / DevTools is opened               |
| 🌓 Theme Toggle              | Light / Dark mode switcher                                     |
| 🖥️ Fullscreen Trigger        | Enter fullscreen with a single click                           |

---

## 💻 Live Demo

> https://sabrishv.github.io/online-proctoring-detection/

---

## 🧠 How It Works

This project uses:
- `visibilitychange`, `blur`, `focus` events for **tab/app switching**
- `mousemove`, `keydown` listeners for **interaction logging**
- Fullscreen API for **fullscreen mode detection**
- Screen dimension checks for **monitor count estimation**
- Window size deltas for **DevTools detection**

All logs are shown in real-time with timestamps, grouped by category.

---

