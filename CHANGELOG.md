# Changelog

What changed in each Tenshi Meter release, newest first. Tenshi shows the latest two in Settings > What's new, and
each release on GitHub uses its section as its notes. Sections: Added, Changed, Fixed, Removed.

## [Unreleased]

## [1.0.0-rc.2] - 2026-10-20

### Added
- Combat power and deaths after each name; hovering a player shows their hit rates, top skills, the damage they took
  and the healing they got.
- Skills show their biggest and average hit, "always crits", front attacks and smites; buffs show how long each was up;
  the crit rate leaves out skills that always crit, so it shows the real critical chance.
- Enrage timers: the boss bar counts down to a boss's enrage, and its tooltip gives the DPS that kills it first. Time
  to kill follows the boss's pace over the last minute.
- A NotMeter-like look: Pill bars, exact numbers (53,480 instead of 53.5K) and a boss card with time to kill, enrage and
  how far ahead your group is.
- Settings > Meter turns each part of the meter on or off: fight time, total, tabs, column headers, rank, the boss bar's
  parts, skill columns, hit rates, buffs. Colors for you and for everyone else (or class colors); name and number size,
  bold DPS, DPS/Total/% colors and a text outline. A live preview beside the options (off at first: "Show preview").
- Pet filters in Settings > Pets: by class (Cogni, Fera, Natura, Varian) and by side (Elyos, Asmodians), with a count;
  each pet's class shows in the list.
- Share settings (Settings > Window): export yours to a file, import someone else's part by part, with Undo. Never your
  boss timers, tracked pets or nodes, pictures, minimap or click-through.
- Resize the meter right on it: pull an edge or a corner (a grip shows on hover); Ctrl + mouse wheel zooms it.
- Hold Alt over the meter or a tracker that lets clicks through to click it again.
- After a quick restart of Tenshi (a crash, an update) while the game runs, it still knows the boss and your party.

### Changed
- Boss fights follow NotMeter's rules: one fight per boss attempt, the meter follows the boss you're fighting, and
  damage matches NotMeter's on the same fight. The meter shows bosses, field bosses and training dummies; trash fights
  outside dungeons are an option (Settings > Fights).
- Nightmare bosses, raids' Hard modes and other Global bosses count as boss fights.
- The meter's look (bars, text, its picture) is on the Meter page; Appearance is the app's look.
- Hide during game menus is on by default.
- Clear feedback where there was none: "Learn it again" (minimap) shows where learning is and when it's done; "Forget
  them all" says how many boss timers it forgot; reset buttons are greyed out with nothing to reset; a picture Tenshi
  can't show, Windows refusing "Start with Windows" and "Use graphics card" waiting for a restart say so.
- Long boss fights no longer slow the meter down (a 5-minute fight's refresh is 13 times cheaper), and capture makes
  less garbage per packet.

### Fixed
- Bosses are recognized on the Global servers: Tenshi couldn't read which NPC an enemy is there, so no boss fight ever
  started and the meter stayed on Ready.
- With ExitLag, damage was counted up to twice; it now counts once.
- On Tamon, its own absorption no longer counts as your group's damage.
- Potions and food no longer count as healing.
- Kills count even when the boss's last HP update never comes, and Tenshi knows which player is you when started late.
- While no fight runs, the meter waits for a boss instead of listing trash damage at 0 DPS.
- Reminders that come at the same time stack under each other instead of on top of each other.
- A part turned off in Edit HUD stays off (opening Edit HUD or Settings turned the meter back on), and the Reminders
  box can be turned off.
- Edit HUD's Cancel puts back only what you changed there, and Settings no longer saves an old value over one changed
  elsewhere (the tray, Edit HUD, a hotkey).
- Hide during game menus works reliably: your party's damage no longer makes Tenshi think you play with the cursor
  always shown, keys you already hold no longer keep the overlays up, and how you play is remembered between starts.
- Showing or hiding Settings' preview no longer makes the window taller each time.
- The pet tracker shows once you track a pet, not as an empty box.
- Settings no longer start over when they hold a choice this version doesn't know (a bar style from a newer Tenshi):
  that choice alone gets its usual value and the rest loads. Settings a newer Tenshi added are kept when this version
  saves, settings from Tenshi 0.1 get every upgrade, and a newer Tenshi's settings keep their version.
- A settings file another program holds as Tenshi starts (an antivirus, a sync tool) is waited for, and never saved
  over with the usual settings; after a start-over, the backup of your settings from before 1.0 is never replaced.

## [1.0.0-rc.1] - 2026-10-19

### Added
- Reminders for each kind (events, bosses, hidden cubes) can pop up while you're alt-tabbed, each set on its own.
- Hidden cubes pop up a reminder when one comes into view.
- Reminders show the event's icon or the boss's portrait, can be made taller, and stay as long as you set (15 s at first).
- Up next lists the field bosses with a timer among the events, and can list only what has its bell on.
- Shields tabs: shields given and damage they absorbed.
- Glass and Clear themes, background pictures for the meter and Settings, and a new Appearance page.
- Hide the overlays when the game is closed or while a game menu is open; start with Windows and wait for the game.
- Delete, Insert, Home, End, Page Up/Down and Pause can be hotkeys on their own (they work while the game is in front).
- Settings > What's new: these notes.
- Updates: Tenshi checks for a new version (Settings > Window > Updates, or the tray menu), downloads it in the
  background and installs it when you restart Tenshi.
- Your settings are backed up when a new version first opens them.

### Changed
- Settings has its own window frame: rounded corners, snapping and resizing like any window.
- One-click choices instead of dropdowns, smoother sliders, and a single-level tray menu.
- "New fight" is now "Clear meter"; the fight so far stays in Past fights.
- Show players is Me, Party or Force (Everyone is gone: it listed strangers fighting anything nearby).
- English and the Global servers only; all of Tenshi's files are in %LocalAppData%\Tenshi.

### Fixed
- Ping shows again on PCs that have been on for more than 4.66 hours.
- The fight clock no longer runs before your group starts fighting.
- Pictures stay inside their frames; a broken picture file no longer removes the one you had.

### Removed
- Fight replay and Combat Assist.

## [0.1.0] - 2026-10-17

### Added
- First version: the DPS meter overlay (damage, healing, damage taken, skills, past fights), the event and field boss
  tracker with reminders, the pet soul tracker, hidden cube and gathering node tracker with minimap markers, Edit HUD,
  hotkeys and themes.
