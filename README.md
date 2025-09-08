# A11y Widget — Drop-in Accessibility Panel

Opera Extension - https://github.com/codelyfe/A11y-Widget-Place-Anywhere-Opera-Extension 

[![License: GPL v2](https://img.shields.io/badge/License-GPL_v2-blue.svg)](LICENSE)
![Vanilla JS](https://img.shields.io/badge/JS-vanilla-informational)
![No Dependencies](https://img.shields.io/badge/deps-none-success)
![Accessible](https://img.shields.io/badge/a11y-WCAG%202.1%2B-brightgreen)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-ff69b4)

A single-file, drop-anywhere accessibility widget to help **everyone** use your website comfortably.  
Created by **Randal Burger Jr.** (ShipWr3ck | Codelyfe) to **help others** and promote **fair treatment** online.

---

## ✨ Features

- **Centered modal panel** with ultra-high z-index (999,999) so it never hides behind UI
- **Dark mode** (hard overrides with `!important`) and **High Contrast** mode
- **Text size scaler** (80%–220%) and **Text spacing** for readability
- **Dyslexia-friendly font** toggle (system, ligatures off, wider letter spacing)
- **Underline links** and **always-visible focus ring**
- **Hide images**, **Grayscale**, **Pause animations** (respects `prefers-reduced-motion`)
- **Reading mask** spotlight stripe that follows the cursor
- **Smarter Text-to-Speech** (TTS) using `SpeechSynthesis`:
  - Select text → **Play/Pause/Stop**, adjustable **Rate** & **Pitch**
  - **Auto-read selected text** (optional)
  - **Hover-to-Read**: floating button appears near the cursor to read hovered text
- **Mute & pause videos** toggle (global)
- **Skip to content** link injected for keyboard users
- **Local persistence**: all settings saved in `localStorage` (`a11y_widget_prefs_v4`)
- **No dependencies**, no trackers, no network calls

---

## 🚀 Quick Start

Add the widget **near the end of your `<body>`** on any page you want it:

```html
<!-- A11y Widget by Randal Burger Jr. -->
<script>
/* Paste the entire widget script here (the single <script> block you have) */
</script>
