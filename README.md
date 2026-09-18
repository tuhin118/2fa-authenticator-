# 🔐 Authenticator

A premium, dark-green themed 2FA authenticator that runs entirely in your browser.
Works offline. No accounts. No servers. Installable as a PWA.

## ✨ Features
- 📱 Scan QR codes from any app (Google, GitHub, Binance, Facebook…)
- ⌨️ Manual Base32 secret entry
- 🔒 Everything stored locally (localStorage) — no cloud, no tracking
- 🌙 Premium dark-green UI with smooth animations
- ⏱️ Live 30s countdown ring, auto code refresh
- 📋 Tap code to copy
- 📤 Export / import encrypted-free JSON backup
- 📲 Installable — Add to Home Screen
- 🚀 Works 100% offline after first load

## 🚀 Deploy on GitHub Pages

1. Create a new repo (e.g. `authenticator`)
2. Upload `index.html`, `manifest.json`, `sw.js`, `icon.svg`
3. Go to **Settings → Pages**
4. Source: **Deploy from a branch** → `main` / `root` → Save
5. Open: `https://<your-username>.github.io/authenticator/`

## 📲 Install on Phone
Open the GitHub Pages URL → tap the install banner (or browser menu → **Add to Home Screen**).

## ⚠️ Important
- This stores secrets in your browser's **localStorage** — clearing site data erases them.
- **Always export a backup** (menu → Export backup).
- Not encrypted. Don't use on a shared/public device.

## 📄 License
MIT
