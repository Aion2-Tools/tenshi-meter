# Changelog

What changed in each Tenshi Meter release, newest first. Tenshi shows the latest two in Settings > Updates, and each
release on GitHub uses its section as its notes. Sections: ✨ New, 🔧 Improved, 🐛 Fixed. A first release can open
with a few lines about Tenshi before them.

## [Unreleased]

## [1.0.0-rc.3] - 2026-10-21

### ✨ New
- **Update notifications.** A dot on the tray icon and a Windows notification when an update is ready, with
  **Restart now** and **Later**. Never while the game is in front.
- **Clearer updates.** See the download size and progress, when Tenshi last checked, and what went wrong. Read the
  new version's notes before you restart.
- **Boss history.** Click the boss's name at the top of the meter to see earlier bosses and mobs.
- **Summary line.** The fight time, your group's damage per second, its total and your ping, under the boss's name.
- **Quick buttons.** The crown switches between Only boss and Boss + adds. The eye hides player names for
  screenshots and streams.
- **Skills window.** Click a player to open their skills in a window of their own.
- **Show yourself on top**, and an optional **Crit %** column.
- **Colors.** A color for each class, one color for every number, and the same color picker everywhere.
- **Own opacity.** Give any overlay its own opacity in Edit HUD.

### 🔧 Improved
- **Ready from the start.** A new install reminds you of every event 5 minutes before, except Arena of Tactics, and
  reminders also pop up while you're alt-tabbed. Up next lists only what you're reminded of. Minimap markers are on.
- **A clearer Settings window.** Pages are grouped into Damage meter, Trackers and Tenshi, each page covers one
  subject, the Meter page uses tabs, and every description is short and plain.
- **One place for reminders.** Every pop-up and sound is on the Reminders page, and reminder text is bigger.
- **One switch for every overlay.** Click-through, Lock position and Overlay opacity apply to all overlays. Hold Alt
  over an overlay to click it.
- **Easier numbers.** Each number shows its unit, like 1.2M/s or 34%. Hover one to see what it is.
- **Boss bar.** A mark every 10%, red when the boss enrages, and a time to kill that turns green when you'll make it.
- **Mobs and field bosses.** Field bosses always count. Mobs count when **Count mobs too** is on. History keeps the
  last 200 fights.
- **Live preview.** A sample meter beside Settings while you change the meter.
- **Any accent color.** Pick it like every other color in Tenshi.
- **Edit HUD** opens in the middle of the screen and says what to do.
- **Tray menu** grouped into Damage meter, Trackers and Overlays. Tenshi's window and its hotkey are now simply
  **Open Tenshi**.
- **What's new is easier to read**, with the date written out, a bold lead on each change and more room between lines.
- **Updates wait for your fight.** Downloads and restarts never interrupt a fight, and the installer shows its progress.
- **Faster Settings.** Pages open without a pause, and sliders and switches respond at once.
- **Ping** hides soon after the game stops answering.

### 🐛 Fixed
- The meter grows with every player again, up to Max players shown. With Pill bars or bigger text, players past the
  fourth or fifth were cut off.
- Pulling the meter's bottom edge no longer stops it from growing with your party, and a meter that stopped grows
  again after this update. A fixed height can still be set in Edit HUD by turning off Height fits the players.
- Minimap markers, Nearby and Killed pet no longer block clicks after hiding once.
- Start with Windows works on laptops on battery, and Windows no longer stops Tenshi after 3 days.
- When capture can't start, Tenshi says why and what to do, and keeps trying.
- Minimap markers no longer make the overlays stutter.
- A reminder no longer pops up twice when Tenshi restarts before its event.
- Settings saved as Tenshi quits are kept.
- Edit HUD's Save button and its Snap and Grid choices are easy to read.
- The Settings preview shows every time you ask for it, even after switching apps, and only when you ask.
- **Test reminder** shows the event's picture, like a real reminder.
- Trying many volumes no longer uses extra memory.

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
