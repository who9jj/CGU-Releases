# Backup, Restore, and Upgrade

## Your CGU data

CGU stores its authoritative SQLite database under your per-user CGU data root, normally under `%LOCALAPPDATA%\Gridiron Dynasty Engine`. It is not stored beside the application binary, in a temporary folder, or in browser cache. The installed application may be replaced during an update without deleting this data.

SQLite is embedded in CGU. Users do not install, configure, or run SQLite separately.

The data root can contain multiple dynasties and their long-term history. V1 acceptance includes preservation of two dynasties with 60 seasons each.

Older release controls may still use the GDE labels quoted below. The retained
user-data directory and `.gdebackup` format keep their existing names.

## Automatic and manual protection

On normal startup, CGU validates the database and makes a bounded automatic backup. The newest **10 automatic backups** are retained. Manual exports and pre-migration backups are not part of that rolling limit.

Use **Settings > Data / Backups** to review the data location, application version, schema version, and backup status.

### Export GDE Data

Use **Create Backup** or **Export GDE Data** before moving computers, before a major experiment, or whenever you want a portable copy. An export is a complete `.gdebackup` package containing the database and a checksum manifest.

Keep exports somewhere separate from the computer running CGU when practical. An export is a safety and portability tool; it is not required before every ordinary update.

### Import / Restore GDE Data

Use **Import / Restore GDE Data** only with a verified `.gdebackup` package. CGU validates the package and database before replacement, preserves the current database as a recovery backup, migrates when required, validates again, and only then activates it.


## Normal update workflow

1. Exit CGU and ensure RPCS3 is closed.
2. Install the newer CGU release to the normal application location.
3. Start CGU.
4. CGU detects existing data, creates a pre-migration backup if needed, migrates, validates, and continues.
5. Confirm the selected dynasty and most recent sync before doing further writeback.

The intended flow is: **install newer CGU → detect existing data → backup → migrate → validate → continue**.

## Moving to another computer

1. On the old computer, use **Export GDE Data** and copy the `.gdebackup` file securely.
2. Install the same or a newer supported CGU release on the new computer.
3. Launch it once, then use **Import / Restore GDE Data**.
4. Configure the new computer's RPCS3 `savedata` location and confirm the intended dynasty before syncing.

The database moves your CGU history; the NCAA save itself should be copied and protected separately using your normal RPCS3 save-management practice.

## Corruption and recovery

If CGU cannot read an existing database, it fails closed: it preserves the existing file and does **not** silently replace your history with a blank database. Read the recovery message, keep the affected file and logs, and restore a verified export or managed backup.

Do not delete the existing database to make an error disappear. If a restore fails validation, choose a different verified backup rather than forcing the package through.

## What upgrades preserve

Schema migrations are explicit and audited. A newer unsupported schema or unreadable database is refused rather than guessed at. Multiple dynasties and long history are preserved by the V1 durability contract.
