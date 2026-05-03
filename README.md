# Backstock Tracker

A lightweight, mobile-first web app for IT staff to track equipment backstock, manage reorders, and log store charges — no backend, no login, no fuss.

---

## What it does

**Backstock** — Add equipment by name and quantity. See at a glance what you have on hand and what's out of stock.

**Reorder queue** — When you pull equipment out of backstock, it moves to the reorder queue. Enter the store number you're charging it to, then mark it complete. The item returns to backstock automatically.

**Charge history** — Every completed reorder is logged with the equipment name, quantity, store charged, and date — so you always have a record.

---

## Using it

Open the app in any browser and add it to your phone's home screen for the best experience.

**On iPhone:** tap the Share button in Safari → "Add to Home Screen"  
**On Android:** tap the menu in Chrome → "Add to Home Screen"

It'll behave like a native app — full screen, no browser chrome.

---

## Features

- Works on any screen size — phone, tablet, or desktop
- Data saves locally to your device (no account needed)
- Alerts you when reorder items are missing a store number
- Numeric keypad on mobile for fast quantity entry
- Dark theme, easy on the eyes during long shifts

---

## Setup

No build step, no dependencies. It's a single HTML file.

1. Clone or download this repo
2. Open `index.html` in a browser — that's it

To host it on GitHub Pages:

1. Go to your repo → **Settings** → **Pages**
2. Under "Branch," select `main` and `/ (root)`
3. Hit **Save** — your app will be live at `https://yourusername.github.io/backstock-tracker`

---

## Data & privacy

All data is stored in your browser's `localStorage`. Nothing is sent to a server. Clearing your browser data will erase your inventory, so if you switch devices you'll start fresh.

---

## Built with

- Vanilla HTML, CSS, and JavaScript
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) & [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts
- No frameworks, no build tools
