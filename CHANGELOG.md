# Changelog

What changed in each Tenshi Meter release, newest first. Tenshi shows the latest two in Settings > Updates, and each
release on GitHub uses its section as its notes. Sections: ✨ New, 🔧 Improved, 🐛 Fixed. A first release can open
with a few lines about Tenshi before them.

## [Unreleased]

## [1.0.0-rc.2] - 2026-10-20

### ✨ New
- **Combat power and deaths** next to each name. Hover a player to see their hit rates, top skills, damage taken and
  healing received.
- **Skill details.** Biggest and average hit, front attacks, smites, and how long each buff was up. Crit rates leave
  out skills that always crit, so they show your real chance.
- **Enrage timers.** The boss bar counts down to the enrage and shows the damage per second you need to beat it.
- **New look options.** Pill bars, exact numbers, and a boss card with time to kill and enrage.
- **Meter options.** Turn each part of the meter on or off, and choose its colors, text sizes and outline.
- **Pet filters** by type and by side.
- **Share settings** with a file, and pick which parts to bring in.
- **Resize the meter directly** by pulling an edge. Ctrl + mouse wheel zooms it.
- **Hold Alt** over an overlay that lets clicks through to click it.
- **Quick restarts** keep the current boss and your party.

### 🔧 Improved
- **Boss fights.** One fight per boss attempt, and the meter follows the boss you're fighting. It shows bosses, field
  bosses and training dummies, and mobs outside dungeons if you want them.
- **More bosses** count: Nightmare bosses, raid Hard modes and other Global bosses.
- **Clear feedback** from buttons and settings that used to give none.
- **Long fights stay fast.** A 5-minute fight refreshes 13 times faster than before.
- **Hide during game menus** is on by default.

### 🐛 Fixed
- Bosses are recognized on the Global servers. Before, the meter stayed on Ready.
- Damage is no longer counted twice when you play through a network optimizer.
- Tamon's own absorption no longer counts as your group's damage.
- Potions and food no longer count as healing.
- Kills count even when the boss's last HP update is missing, and Tenshi knows which player is you when started late.
- The meter waits for a boss instead of listing mob damage at 0 DPS.
- Reminders that arrive together stack instead of overlapping.
- Overlays turned off in Edit HUD stay off, and Edit HUD's Cancel only undoes changes made there.
- Hide during game menus works reliably and remembers how you play.
- The pet tracker no longer shows as an empty box.
- Your settings are no longer reset by an option from a newer version, or by another program holding the file.

## [1.0.0-rc.1] - 2026-10-19

The first test build of Tenshi Meter, a damage meter and companion overlay for AION 2. Tenshi reads the game's network
traffic. It never reads the game's memory or sends anything to the game, and its overlays never take focus from it.

### ✨ Features
- **Damage meter.** Damage, healing, damage taken and shields for you, your party or your force, with each player's
  skills and your past fights.
- **Event tracker.** Timed events and field boss timers in your region's server time, with reminders before the ones
  you pick.
- **Pet tracker.** The souls you collect for each pet.
- **Hidden cubes and nodes.** A reminder when a hidden cube comes into view, and markers on the game's minimap if you
  turn them on. Markers look only at the minimap on your screen.
- **Edit HUD.** Move, resize and snap every overlay.
- **Themes.** Dark, Light, Glass, Clear and High contrast, with your own accent color and background pictures.
- **Hotkeys** for the main actions. Keys like Insert or Home work on their own while the game is in front.
- **Fits your setup.** Hide the overlays with the game or during its menus, and start with Windows.
- **Updates** download in the background and install when you restart Tenshi. Your settings are backed up first.
