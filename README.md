# 🐠 Reef Tracker

A mobile-first reef aquarium water parameter tracking app — runs entirely in the browser, no server or account required.

## Features

- **Multi-tank support** — manage multiple aquariums
- **Log measurements** — salinity, KH, pH, Ca, Mg, temperature and 40+ trace elements
- **Charts** — time-series graphs per tank with ICP markers and reference ranges
- **ICP Import** — parse Fauna Marin REEF ICP PDF reports automatically
- **Salt Calculator** — Tropic Marin dosing formula
- **Balling Light Calculator** — Fauna Marin Ca / Mg / KH correction doses
- **PWA** — installable on iPhone via Safari "Add to Home Screen"
- **Offline** — works without internet, data stored in browser localStorage

## Usage

Just open `index.html` in any browser — or host it via GitHub Pages:

1. Fork / upload this repo
2. Go to **Settings → Pages → Source: main branch / root**
3. Open `https://yourusername.github.io/reef-tracker/`

## Data Storage

All data is saved locally in your browser's `localStorage`. No account, no cloud, no tracking.

> To back up your data: open browser DevTools → Application → Local Storage → copy the value of `reef_tracker_v3`
