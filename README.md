# 📰 News Fetcher by FRC All Music #2025

## 🧾 License

This software is proprietary and protected under copyright law.

⚠️ This repository does not provide the source code of the application. It is used to host update metadata only.


© 2025 FRC All Music – All rights reserved.

Use is permitted for personal or licensed commercial purposes only. Redistribution or modification is prohibited without permission.


**News Fetcher** is a lightweight, tray-based Windows utility that automatically downloads up to 10 configurable MP3 news bulletins every hour.

Built for music programmers, radio producers, and anyone who wants fresh news audio delivered quietly and reliably.

---

## ✨ Features

- ⏰ Schedule downloads to start at any minute of the hour
- ⏳ Sequential downloads spaced by 4-minute intervals
- 🔁 Retry-on-failure logic with logging
- 💾 Config export/import
- 🔔 Tray balloon notifications
- 🚀 Auto-launch at Windows startup
- 📦 Clean Windows installer
- 🔄 **Auto-update** support via `version.json`

---

## 🔧 How It Works

1. Configure up to 10 news sources (MP3 download links)
2. Choose a download folder for each
3. Select the minute of the hour to start (e.g. `57`)
4. News Fetcher will:
   - Download each enabled file
   - Wait 4 minutes between each
   - Overwrite existing files automatically

---

## 📥 Auto-Update

The app checks for updates at startup via the hosted [`version.json`](https://raw.githubusercontent.com/yourusername/news-fetcher-updates/main/version.json).

When a new version is available, you’ll see a prompt to download the latest installer.

---

## 🧾 License

This project is licensed under the [MIT License](LICENSE).

© 2025 FRC All Music — All rights reserved.
