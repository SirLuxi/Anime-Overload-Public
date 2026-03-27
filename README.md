# ⚔️ Anime Overload Macro

![Version](https://img.shields.io/badge/Version-v1.0.0-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Tech Stack](https://img.shields.io/badge/Tech-PyTauri%20%7C%20Svelte%20%7C%20OpenCV-success)

A high-performance, fully automated farming macro for **Anime Overload** on Roblox. Built with a lightning-fast Python backend and a premium Svelte frontend, this tool is designed to completely automate your grinding so you can focus on the game.

![App Screenshot](./templates/screenshot.png) ---

## ✨ Core Features

* 🎯 **Smart Vision Tracking:** Uses OpenCV image recognition to detect waves, units, and UI elements in real-time. No more blind clicking.
* 🖥️ **Background Docking:** Strips the Roblox window borders and docks it directly inside the macro UI. It runs seamlessly without hijacking your entire screen.
* 🔄 **Auto-Reconnect & Private Servers:** Game crashed? Disconnected? The macro automatically detects the reconnect screen, kills the instance, and relaunches straight into your private server.
* 🎥 **Smart Placement Recorder:** Easily record, save, and import custom unit placement configurations for different maps and challenges.
* 📊 **Live Session Stats & Webhooks:** Track your wins, losses, total runs, and runtime directly in the UI, or send live updates straight to your Discord server.
* ⚡ **Over-The-Air Updates:** Built-in auto-updater. The moment a new version or game patch drops, you can update with a single click inside the app.

---

## 🚀 Installation & Setup

1. Head over to the [Releases](../../releases/latest) tab.
2. Download the latest `anime-overload-setup.msi` file.
3. Run the installer (Windows may prompt a Defender warning since this is a new indie app—click "More info" -> "Run anyway").
4. Open the app, paste your license key, and launch Roblox!

### ⚙️ How to Use
1. Open **Anime Overload** and load into the main lobby.
2. In the macro UI, click **Dock** to attach the Roblox window to the app.
3. Select your Map, Act, and Difficulty in the setup panel.
4. Hit **Start Macro** and step away from your keyboard. 

*(Use `F1` to Dock, `F4` to Undock, and `F2` to easily toggle the macro on and off).*

---

## 🛠️ Tech Stack

This macro was engineered from the ground up to be lightweight and fast:
* **Frontend:** SvelteKit & Tauri (Minimal RAM footprint, fluid UI).
* **Backend:** Python 3 (For raw execution speed).
* **Vision Engine:** OpenCV & Pillow.
* **Input Simulation:** PyAutoGUI & PyDirectInput.

---

## ⚠️ Disclaimer

This software is for educational and testing purposes. Use at your own risk. The developer is not responsible for any actions taken against your Roblox account by the game's moderation team.

---
*Built by SirLuxi*
