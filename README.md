# 🛡️ The Casually Hardcore — Guild Manager

I created this tool so that everyone in **The Casually Hardcore** (WoW: Forever) can easily see more about the rest of our guild—what classes and specs people are playing, what gear and professions they have, and who is eligible to team up for dungeons!

## 📥 Download Latest Version
👉 **[Download the Latest Release Here](https://github.com/Arkansadave/Casual-Hardcore-Guild-Tool/releases/latest)**

<img width="2568" height="1408" alt="image" src="https://github.com/user-attachments/assets/6c845450-203a-4ca5-88de-7db2d6cb5d4d" />
<img width="2568" height="1408" alt="image" src="https://github.com/user-attachments/assets/8c68ec82-4c59-4c48-8109-ecf6990021f0" />

---

## ✨ Features

* **⚔️ Full Guild Roster & Local Caching:** Syncs directly with the official Blizzard Battle.net API for *WoW: Forever* and caches everything locally so the app loads instantaneously.
* **🔍 Smart Filtering:** Filter the guild roster by **Class**, **Role** (Tank, Healer, DPS), or **Professions** (multi-select dropdown supporting all primary and secondary professions).
* **🧥 Armory Character Inspector:** Click any guild member to view their character render, main talent spec, average item level, professions, and full equipped gear color-coded by item quality.
* **🛡️ WoW: Forever Dungeon Party Builder:**
  * Includes all Classic and new *WoW: Forever* dungeons with their exact level brackets.
  * Automatically lists eligible guildies for the selected dungeon.
  * Assemble a 5-person group (**1 Tank / 1 Healer / 3 DPS**) with automatic **Bloodlust/Heroism** and **Battle Rez** utility checks.
* **📋 One-Click Chat Export:** Copy your assembled dungeon group straight to your clipboard formatted either for **Discord** or as a single line for **WoW Guild Chat (`/g`)**.

---

## 🚀 How to Run (Windows)

1. Go to the **[Releases](https://github.com/Arkansadave/Casual-Hardcore-Guild-Tool/releases)** page and download the latest `.zip` file.
2. Extract the `.zip` into its own folder on your PC (so `guild_cache.json` can save next to the `.exe`).
3. Double-click **`Casual_Hardcore_Guild_Tool.exe`** to launch.
   * *First-time launch tip:* Because this is a custom guild app without a paid Microsoft signing certificate, Windows SmartScreen may show a *"Windows protected your PC"* popup. Click **More info** → **Run anyway** (Windows will remember this and won't ask again).
4. Click **🔄 Sync Full Guild** in the top-left corner to pull the latest roster, gear, and professions.

---

## 🛠️ Built With
* **C# / .NET 10 (WPF)**
* **Blizzard Battle.net Game Data & Profile APIs** (`profile-forever-us`)
