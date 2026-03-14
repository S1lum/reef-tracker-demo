# 🐠 Reef Tracker — Demo v10.19

A fully functional demo of Reef Tracker — no login required, no cloud, runs directly in the browser.

👉 **[Open Demo](https://s1lum.github.io/reef-tracker-demo/)**

---

## Demo vs. Full Version

| | Demo | Full Version |
|---|---|---|
| Login required | ❌ | ✅ Google |
| Data storage | Browser (localStorage) | Firebase Cloud |
| Sync across devices | ❌ | ✅ Real-time |
| All features | ✅ | ✅ |
| Offline capable | ✅ | ✅ |

---

## Features

### 📋 Log
- Manual entry of all water parameters (Salinity, KH, Ca, Mg, NO₃, PO₄, and many more)
- ICP analysis import and comparison with manual measurements
- Hanna PO₄ converter — ppb directly to ppm, reference table 1–200 ppb
- Calibration offsets per ICP (⚖️)
- Month navigation, parameter filter pills, search

### 📈 Charts
- Time-series charts for all parameter groups
- Calibrated values as triangles ▲, ICP values as diamonds ◆
- Green target band on Y-axis

### 📊 Stats
- **Overview widget**: tank summary, 8 key parameters with trend arrows (↑↓→), recent dosing, upcoming reminders
- Traffic-light rating of all parameters against reference ranges
- Min / Max / Average and sparklines per parameter

### 🐠 Inhabitants
- Log fish, corals, and invertebrates with emoji and notes

### 🔔 Reminders
- One-time and recurring reminders (daily / weekly / monthly)

### 🧰 Tools

| Tool | Description |
|---|---|
| 💊 Dosing Journal | Log dosing entries with chart |
| 🧂 Salt Calculator | Salt and water change calculator |
| ⚗️ Balling Light | Ca / Alk / Mg dosing calculator |
| 🧪 Trace Dosing | Reef Zlements — 14 trace elements with history and chart |

### 🌙 Dark / Light Mode
- Toggle via the ☀️ button in the header

### Multiple Tanks
- Add and switch between unlimited tanks

---

## Data Storage

All data is stored in the **browser's localStorage**. It persists as long as the browser cache is not cleared. For long-term backup, use the **JSON backup** via the avatar menu (🐠 top right → Backup).

---

## Install as iPhone App

1. Open in **Safari**
2. Tap Share → "Add to Home Screen"
3. Confirm → "Add"

The demo runs like a native app — even offline.

---

## Full Version

For cross-device sync and cloud backup, use the full version with Google login:  
👉 **[Reef Tracker (Firebase)](https://s1lum.github.io/reef-tracker/)**
