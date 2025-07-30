# 🎮 Steam Grid Fetcher

A Python tool that **automatically downloads and applies high-quality Steam grid images** (library, hero, logo, header) for non-Steam games.  
It fetches assets from Steam’s official CDN and places them directly into your Steam.

---

## ✨ Features
- 🔍 Search for non-Steam games by name using the Steam API  
- 📥 Download official Steam images for your game  
- 🔄 Automatically rename and place them in the correct Steam directory  
- 🎵 Plays background music during the process  
- 🎨 Fun ASCII animations while processing  
- 💾 Saves your Steam account ID for future runs  

---

## 🚀 How to Use for Non-Steam Games

1. **Add Your Non-Steam Game to Steam First**
   - Open Steam → **Games** → **Add a Non-Steam Game to My Library**  
   - Run the steam-grid-fetcher.exe
   - When prompted, **enter your Steam Account ID** (only required on first run).  
   - Then, **type the game name exactly as it appears in your Steam library**.  
     - ✅ Example: `Grand Theft Auto V`  
     - ❌ Do not use abbreviations or typos.

2. ✅ **Restart Steam** to see the new images applied to your game.

## 🛠️ Screenshots
<img width="858" height="523" alt="image-sc1" src="https://github.com/user-attachments/assets/85730bc1-2751-4113-92bb-4540d08f0fb3" />

---

## 🛠️ Requirements
- Windows OS  
- Python 3.8+  
- Steam installed at default location:

---
### 📦 Install dependencies:
```bash
pip install requests
````
---
> **⚠️ DISCLAIMER**  
> This project is an **independent, unofficial tool** and is **not affiliated with, endorsed, or sponsored by Valve Corporation**.  
> - All images and assets belong to Valve and their respective publishers.  
> - The tool only automates downloading publicly available assets for personal use.  
> - Redistribution or commercial use of downloaded images is prohibited.  
> - Use at your own risk; the author is not responsible for misuse, bans, or data loss.

---
[LICENSE](LICENSE)

