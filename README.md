# Gridiron Dynasty Engine — NCAA 14 V1

**Gridiron Dynasty Engine (GDE)** is a local-first dynasty companion for **NCAA Football 14** and **College Football Revamped** running in RPCS3.

NCAA 14 remains the on-field game. GDE expands the dynasty-management experience around it with modern roster management, recruiting, transfers, coaching, postseason tools, long-term history, and carefully guarded save integration.

## Download

Download the latest installer from the **Releases** section of this repository.

Current release:

**Gridiron Dynasty Engine NCAA 14 V1.0.0**

No separate Python or SQLite installation is required.

## Major V1 Features

- Dynasty import and synchronization
- Modern transfer portal workflows
- Immediate transfer eligibility
- Development Reserve — up to 10 players beyond the native active roster
- Recruiting lifecycle enhancements
- Junior scouting and regional scouting
- Program Momentum and Portal Attractiveness
- Team Captains
- Assistant Coach Market
- CFP and postseason management
- Championship Rewards
- Position Change Lab and Career Projection
- Offseason Decision Center / Roster Compliance Manager
- Dynasty What-If Simulator
- Long-term history and analytics
- Automatic backups
- Export / import and restore
- Database migration and recovery
- Multi-dynasty and long-dynasty support

## Start Here

- [Quick Start](docs/quick-start.md)
- [Full User Guide](docs/user-guide.md)
- [Backup, Restore, and Upgrade Guide](docs/backup-restore-upgrade.md)
- [V1 Release Notes](docs/release-notes-v1.md)
- [Known Limitations](docs/known-limitations.md)
- [Community Overview](docs/community-overview.md)

## Safe NCAA Writeback

For GDE actions that modify NCAA-native dynasty data:

1. Save the dynasty in NCAA.
2. Exit the dynasty.
3. Close RPCS3.
4. Sync the closed save in GDE.
5. Preview and apply the supported action.
6. Relaunch RPCS3.
7. Reload the dynasty and verify the result.
8. Save again in NCAA.

Read-only tools such as Position Change Lab and Dynasty What-If do not modify the NCAA save.

## V1 Validation

Final automated regression:

**3,088 passed, 1 skipped**

The V1 release also passed fresh-install, upgrade/migration, backup/restore, corruption recovery, multi-dynasty, 60-season preservation, browser, and packaged-runtime acceptance.

## Requirements

- Windows PC
- RPCS3
- NCAA Football 14 / College Football Revamped
- Compatible NCAA 14 dynasty save

## Version

**GDE NCAA 14 V1.0.0**

Database schema: **1**

See [Known Limitations](docs/known-limitations.md) for intentionally deferred future work.
