# GDE NCAA 14 V1 Release Notes

## GDE V1 is available

Gridiron Dynasty Engine V1 is a local-first NCAA 14 / College Football Revamped dynasty companion. It preserves NCAA as the game while expanding the dynasty-management layer around it.

### Major V1 capabilities

- Guarded native writeback with previews, managed backups, validation, reread, audit, and rollback.
- Dynasty import/sync, recruiting lifecycle support, junior scouting and regional-scout workflows.
- Development Reserve and modern transfer-portal planning, including immediate-eligibility and reconciliation safeguards.
- Program Momentum and Portal Attractiveness analysis.
- CFP and postseason administration, Championship Rewards, Team Captains, and Assistant Coach Market workflows.
- Position Change Lab, Offseason Decision Center, and non-destructive Dynasty What-If Simulator.
- Player/team history, analytics, team resume, and long-term dynasty context.
- Persistent local data, automatic backups, export/import, migration, and fail-closed recovery.
- Standalone Windows runtime with bundled dependencies and College Gridiron Universe presentation integration.

## Validation baseline

The final V1 regression completed with **3,088 passed, 1 skipped**. Focused durability coverage verified fresh initialization, migration, backup/export/import, corruption recovery, multi-dynasty retention, and 60-season-scale preservation. Current-source executable and installer acceptance passed with no separate Python or SQLite installation.

## Release boundaries

V1 is feature-frozen. See [Known Limitations](known-limitations.md) for deferred work, including native dynasty-year remapping, NCAA 13, Madden, and unproven native fields.
