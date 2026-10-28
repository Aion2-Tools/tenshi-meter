<p align="center">
  <img src="https://raw.githubusercontent.com/Aion2-Tools/tenshi-meter/main/tenshi.png" width="96" alt="Tenshi Meter">
</p>

<h1 align="center">Tenshi Meter</h1>

<p align="center">
  A damage meter and companion overlay for AION 2.
</p>

<p align="center">
  <a href="https://github.com/Aion2-Tools/tenshi-meter/releases/latest"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FAion2-Tools%2Ftenshi-meter%2Fmain%2Fdownloads.json&style=for-the-badge" alt="Downloads"></a>
  <a href="https://ko-fi.com/yushi47"><img src="https://img.shields.io/badge/Ko--fi-Support%20Tenshi-72A4F2?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Support Tenshi on Ko-fi"></a>
</p>

## ✨ Features

- **Damage meter.** Damage, healing, damage taken and shields for you, your party or your force, with each player's
  skills, hit rates and buffs.
- **Boss fights.** The boss's HP, an enrage timer, time to kill, and your past fights.
- **Event tracker.** Timed events and field boss timers in your region's server time, with reminders.
- **Pet tracker.** The souls you collect for each pet.
- **Hidden cubes and nodes.** A reminder when one comes into view, and markers on the game's minimap.
- **Your layout.** Move, resize and snap every overlay in Edit HUD. Five themes, accent colors and background pictures.
- **Stays out of the way.** Never takes focus from the game, lets clicks through, and hides with the game or during
  its menus.
- **Updates itself** in the background and installs when you restart it.

## 📥 Download

Get the newest version from **[Releases](https://github.com/Aion2-Tools/tenshi-meter/releases/latest)**:

| | |
|---|---|
| **TenshiMeter-win-Setup.exe** (recommended) | Installs Tenshi for your Windows user. No admin rights needed to install. |
| **TenshiMeter-win-Portable.zip** | Unzip it anywhere and run `Tenshi.exe`. |

Use one or the other, not both. Both update themselves.

**Needs:** Windows 10 (1809) or 11, 64-bit. Nothing else to install.

## 🚀 First start

- **Windows may say it protected your PC.** Tenshi isn't code-signed yet. Click **More info**, then **Run anyway**.
- **Tenshi asks for administrator rights when it starts.** It needs them to read the game's network traffic.
- **Tenshi lives in the tray**, by the clock. Double-click its icon to open Tenshi; right-click it for the menu (show or hide the meter, and more).

## 🛡️ Safe by design

- **It only reads.** Tenshi reads AION 2's network traffic on your PC. It never reads or changes the game's memory and
  never sends anything to the game or its servers.
- **Minimap markers** look only at the minimap on your screen, and can be turned off in Nodes.
- **No telemetry.** Tenshi connects only to its page on GitHub: to check for updates, and to show in Settings > Updates
  how many times it was downloaded. With automatic update checks off, it connects only when you click Check for updates.
- **Some antivirus tools flag WinDivert**, the network driver Tenshi uses, because it can see network traffic. Tenshi
  uses it to read only.

## 📁 Your files

Settings, pet souls, logs and recordings are in `%LocalAppData%\Tenshi`. Updating or uninstalling keeps them.

## 🐛 Something wrong?

[Open an issue](https://github.com/Aion2-Tools/tenshi-meter/issues/new/choose) with your Tenshi version, shown under
the sidebar in Tenshi, and what happened. The log is `%LocalAppData%\Tenshi\logs\app.log`. **Logs and recordings can
contain character names**, so check before you attach one.

After a game patch, the meter may show nothing until Tenshi is updated for it.

## ℹ️ About

Tenshi Meter is a free, fan-made tool. It is not affiliated with or endorsed by NCSOFT. AION is a trademark of NCSOFT
Corporation. What changed in each version: [CHANGELOG.md](CHANGELOG.md).
