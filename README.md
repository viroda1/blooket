# Viros XL Blooket Toolkit

![Version](https://img.shields.io/badge/version-2.0-blue) ![License](https://img.shields.io/badge/license-ESPL%202026-green)

**Viros XL** is a powerful, feature‑rich cheat overlay for Blooket. It enhances your gameplay with auto‑answering, score manipulation, ESP features, and much more – all packed into a sleek, draggable GUI.

> **⚠️ Disclaimer:** This tool is intended for **educational purposes only**. Using it may violate Blooket's Terms of Service. Use at your own risk and only on accounts you own.

---

## ✨ Features

- **Auto Answer** – Automatically selects the correct answer for you.
- **Highlight Answers** – Colors correct answers green, wrong red.
- **Set Gold / Crypto / Doubloons / etc.** – Modify your in‑game currency instantly.
- **Chest ESP** – See what’s inside each chest before you pick.
- **Password ESP** – Highlights wrong passwords during Crypto Hack.
- **Heist ESP** – Shows what’s under each chest in Pirate’s Voyage.
- **Crash Host** – Attempts to crash the host’s game (use with caution).
- **Daily Rewards Claimer** – Get max tokens and XP with one click.
- **Chat System** – In‑game chat with command support (`/cb`, `/list`, `/clear`, etc.).
- **Leaderboard** – Real‑time player rankings for the current game mode.
- **Themes & Customization** – Change colors, scale, and keybindings to match your style.
- **Toggleable Cheats** – Enable/disable features with a single click.
- **Draggable Window** – Move the GUI anywhere on your screen.

---

## 📦 Installation

### Option 1: Tampermonkey / Violentmonkey (Recommended)

1. Install a userscript manager extension for your browser:
   - [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Firefox, Edge, Safari)
   - [Violentmonkey](https://violentmonkey.github.io/) (Chrome, Firefox)

2. Create a new script and paste the entire Viros XL code (from the provided file).

3. Save the script. It will automatically run on `play.blooket.com`.

### Option 2: Bookmarklet

1. Create a new bookmark in your browser.
2. Name it `Viros XL` and paste the following code as the URL:

```javascript
javascript:(function(){var s=document.createElement('script');s.src='https://raw.githubusercontent.com/your-repo/viros-xl/main/viros-xl.js';document.head.appendChild(s);})();
