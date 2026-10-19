<p align="center">
  <img src="https://raw.githubusercontent.com/Aion2-Tools/tenshi-meter/main/tenshi.png" width="96" alt="Tenshi Meter">
</p>

<h1 align="center">Tenshi Meter</h1>

<p align="center">
  A DPS meter overlay for AION 2: live damage, healing and shields, skill breakdowns, past fights, an event and field
  boss tracker with reminders, pet souls, hidden cubes and gathering nodes.
</p>

## Download

Get the newest version from **[Releases](https://github.com/Aion2-Tools/tenshi-meter/releases/latest)**:

| | |
|---|---|
| **TenshiMeter-win-Setup.exe** (recommended) | Installs Tenshi for your Windows user, with a Start menu entry. No admin rights needed to install. |
| **TenshiMeter-win-Portable.zip** | Unzip it anywhere and run `Tenshi.exe`. |

Both update themselves: Tenshi checks for a new version (Settings > Window > Updates, or the tray menu), downloads it
in the background and installs it when you restart Tenshi. Use one or the other, not both.

**Needs:** Windows 10 (1809) or 11, 64-bit. Nothing else to install.

## First start

- **Windows may say it protected your PC** ("Windows SmartScreen", "unknown publisher"): Tenshi isn't code-signed.
  Click **More info**, then **Run anyway**.
- **Tenshi asks for administrator rights every time it starts.** It needs them to read the game's network traffic
  (with the WinDivert driver).
- Tenshi lives in the tray (by the clock). Click its icon to show or hide the meter, double-click it for Settings.

## What Tenshi does and doesn't do

- **It only reads.** It reads AION 2's network traffic on your PC. It never reads or changes the game's memory, never
  injects anything into the game, and never sends anything to the game or its servers.
- **The minimap markers** (off unless you turn them on) read only the part of the screen under the game's minimap.
- **No telemetry.** The only connection Tenshi makes is the update check to GitHub.
- **Some antivirus tools flag WinDivert**, the network driver Tenshi uses, as a "potentially unwanted" tool because it
  can see network traffic. Tenshi uses it read-only.

## Your files

Settings, pet souls, logs and recordings are in `%LocalAppData%\Tenshi` (Settings > Window > Open). Updates and
uninstalling leave them where they are.

## Something wrong?

[Open an issue](https://github.com/Aion2-Tools/tenshi-meter/issues/new/choose) with your Tenshi version (under the
Settings sidebar) and what happened. The log is `%LocalAppData%\Tenshi\logs\app.log`. **Logs and recordings can contain
character names**: look before you attach one.

After a game patch, the meter may show nothing until Tenshi is updated for it; that update usually comes quickly.

## About

Tenshi Meter is free and open source under the GNU GPL v3: every release has its source code
(`Tenshi-Meter-<version>-source.zip`). Credits for the data and code it builds on are in `NOTICE.md`, next to
`Tenshi.exe`. What changed in each version: [CHANGELOG.md](CHANGELOG.md).

Tenshi Meter is a fan-made tool. It is not affiliated with or endorsed by NCSOFT. AION is a trademark of NCSOFT
Corporation.
