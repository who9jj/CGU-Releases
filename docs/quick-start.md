# GDE V1 Quick Start

This path takes about 5–10 minutes and gets a first NCAA 14 dynasty safely into GDE.

## 1. Install and launch

Run `GDE Setup.exe`, then launch **College Gridiron Universe** from the Start menu. GDE opens its local interface and keeps its own data in your Windows user-data location, separate from the installed application.

SQLite is built in. Do not install SQLite or create a database yourself.

## 2. Prepare RPCS3 and the dynasty

Open your dynasty in NCAA 14 / College Football Revamped, confirm it loads normally, and save it through NCAA. Then exit the dynasty and close RPCS3 before the first sync. GDE needs the save closed so it can read a stable copy.

In GDE, open **Import / Dynasty Sync** and choose the *parent* RPCS3 `savedata` directory, typically:

`RPCS3\dev_hdd0\home\<profile>\savedata`

Do not select an individual dynasty folder unless GDE explicitly asks for it.

## 3. Import your dynasty

1. Choose the compatible `BLUS31159-DYNASTY-*` dynasty GDE discovers.
2. Select **Sync Dynasty** once.
3. Wait for the completion summary, then confirm the expected team, players, and dynasty are shown.

GDE can safely resync an unchanged save. Later, repeat this process after NCAA changes and after RPCS3 is closed.

## 4. Know the two kinds of tools

**Read-only tools** help you decide without changing NCAA or authoritative GDE state. Examples: Position Change Lab, Program Momentum, analytics/history, much of the Offseason Decision Center, and the Dynasty What-If Simulator.

**Writeback-capable workflows** can make an approved NCAA change. They always require the closed-save workflow below and offer a preview before application.

## 5. The one safe writeback workflow

Use these same steps for every GDE action that changes NCAA-native dynasty data:

1. Save the dynasty in NCAA.
2. Exit the dynasty.
3. Close RPCS3.
4. Open GDE and sync the closed save.
5. Preview the action and confirm the affected player, recruit, coach, or team.
6. Apply the GDE action.
7. Relaunch RPCS3.
8. Reload the dynasty and verify the result in NCAA.
9. Save in NCAA.

GDE creates managed backups and validates/rereads approved changes. If it refuses an action or verification does not look right, stop and use the recovery guidance rather than retrying around the safeguard.

## 6. Resume play

After a successful sync or verified writeback, return to NCAA and play normally. At the next meaningful checkpoint, save, close RPCS3, and sync again. See the [User Guide](user-guide.md) for the season-by-season workflow.
