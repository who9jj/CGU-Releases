# GDE V1 User Guide

GDE is organized around the life of an NCAA 14 dynasty, not a collection of disconnected menus. NCAA remains the game where you play, advance, and save; GDE helps you understand, plan, and safely complete supported dynasty-management work.

> **The native-write rule:** Before every GDE workflow that changes NCAA-native data, save in NCAA, exit the dynasty, close RPCS3, sync the closed save in GDE, preview and apply the action, relaunch RPCS3, reload and verify, then save in NCAA. Read-only tools do not need this sequence.

## A. Installation and initial setup

Install GDE, then launch **College Gridiron Universe**. In **Import / Dynasty Sync**, select the parent RPCS3 `savedata` directory—not a temporary extraction and not an incomplete individual save. Choose the discovered dynasty and sync it.

Confirm the team, season context, and roster shown by GDE match NCAA before using any writeback-capable workflow. GDE stores its own history under your Windows user-data root; see [Backup, Restore, and Upgrade](backup-restore-upgrade.md).

[SCREENSHOT: Import / Dynasty Sync selection]

## B. Starting a dynasty

Create and save the dynasty in NCAA 14 / College Football Revamped first. If you use a custom roster, load it before creating the dynasty. Close RPCS3, then perform the first GDE sync.

You may use a supported display-season setting in GDE for presentation, but GDE does not claim to rewrite NCAA's native year mechanics. Treat NCAA's saved dynasty as the source for on-field progression and GDE as the companion for supported management and history.

## C. First-season preseason

The first preseason is where the Initial Portal, roster planning, and early recruiting context come together. Start with a closed-save sync, review active roster count, Development Reserve, and any temporary Initial Portal staging. An active roster may be below 70; **70 is a maximum, not a target you must fill.**

Use the Offseason Decision Center to see shortages, graduating exposure, and candidate decisions. Its analysis is read-only until you deliberately hand off to an owning supported workflow.

## D. Initial Portal

The **Initial Portal** occurs only in the first preseason. GDE uses an Initial Portal Staging Pool to organize candidates while you make the opening roster decisions.

- Staged players are temporary, not permanent extra roster slots.
- Staging must resolve to **zero** before normal preseason/redshirt decisions.
- Active roster is at most **70**.
- Development Reserve is at most **10**.
- Controlled population (Active + Reserve) is at most **80**.

Staging exists to make the inaugural transition understandable without pretending you have an unlimited roster. Resolve each candidate through the supported roster/portal workflow before normal play begins.

## E. Development Reserve

Development Reserve is a bounded long-term roster option:

- Native active roster maximum: **70**.
- Development Reserve maximum: **10**.
- Total controlled population maximum: **80**.
- A player may use Reserve **once in a career**, for **exactly one season**.
- Entering Reserve consumes that player's redshirt.
- The following offseason, resolve the player through **Activate**, **Transfer**, or **Cut**.

Reserve players are outside the active native 70 and cannot be redshirted again. Their development/progression is preserved. Active-roster players may still use normal NCAA redshirts when eligible.

First season: clear Initial Portal staging first, then make Reserve decisions. Later seasons: Reserve is part of normal offseason reconciliation, not a second redshirt or a permanent holding list.

[SCREENSHOT: Development Reserve roster screen]

## F. Native redshirts

Normal NCAA redshirts remain separate from Development Reserve. Use the supported redshirt workflow only for an eligible active-roster player and only after the required save/exit/sync sequence. Do not try to redshirt a Reserve player; Reserve has already consumed that player's redshirt.

After applying a supported native change, reload NCAA and verify before saving. If GDE refuses a change, preserve the current save and follow the refusal/recovery message.

## G. Regular season

Play and advance in NCAA as usual. At meaningful checkpoints, save, exit the dynasty, close RPCS3, and sync GDE. This keeps roster, recruiting, history, and analytics aligned with the actual NCAA save.

Use read-only history, analytics, team-resume, Program Momentum, and roster views during the season to understand trends. They do not modify NCAA.

## H. Recruiting

GDE supports the accepted recruiting lifecycle and guarded recruiting actions. Use the recruiting workflow to evaluate needs, scouting context, offers, visits, and eligible commitment options; do not infer that every displayed data point is writable.

For any recruiting action that GDE identifies as native writeback-capable, use the standard closed-save workflow, review the preview, apply once, reload NCAA, verify, and save. GDE fails closed when the expected source state, identity, or relationship is unsafe.

## I. Junior scouting and regional scouts

Use junior-scouting and regional-scout views to organize longer-horizon recruiting information. They help prioritize where to invest attention and how a class fits roster need; they are not permission to bypass the supported recruiting workflow.

When scouting changes are analysis-only, no NCAA save handling is required. When a view hands off to a supported NCAA action, return to the native-write rule at the top of this guide.

## J. Program Momentum and Portal Attractiveness

Program Momentum and Portal Attractiveness explain the program context around wins, achievements, opportunity, roster fit, and coaching signals. They are **read-only analysis**. They do not change NCAA prestige, force portal outcomes, or modify your save.

Use them as one input when judging needs and transfer strategy, not as a replacement for roster reconciliation or on-field results.

## K. CFP and postseason

Use the CFP/postseason workspace to review the accepted postseason picture and supported projections. NCAA remains authoritative for games and results. Any supported NCAA-facing postseason action follows the same closed-save, preview, verify, and save workflow.

Do not advance or manipulate a live NCAA save while RPCS3 is open and a GDE writeback is pending.

## L. National Championship Rewards

Winning a national championship unlocks **one** reward for the following season:

- **Championship Commitment**
- **Elite Scouting**
- **Development Edge**
- **Retention Edge**

Rules:

- One reward per championship.
- The reward applies to the following season.
- Rewards do not stack indefinitely.
- An unused reward expires after its applicable season.
- A Championship Commitment recruit must still qualify.
- Program Momentum is automatic and separate.
- GDE does not modify native prestige.

Choose a reward in its owning workflow. Championship Commitment is a guarded recruiting opportunity, not a guarantee that overrides normal qualification.

[SCREENSHOT: Championship Rewards selection]

## M. Offseason portal

Beginning at the **end of Year 1**, the portal is part of the normal offseason cycle. GDE reconciles the NCAA-native roster, sequences supported transfers, and preserves class/redshirt context and immediate eligibility where the accepted workflow supports it.

Consider roster needs, Program Momentum, coaching movement, and source/destination roster health. Do not use portal planning to exceed the 70/10/80 limits. A proposed transfer is not complete until the owning workflow validates it and you verify the outcome in NCAA.

## N. Assistant Coach Market

The Assistant Coach Market is the supported workflow for accepted coordinator/staff movement. Review the candidate and reciprocal team context before applying a move. Because a coach move can affect the NCAA save, it uses the native-write rule: closed RPCS3, sync, preview, apply, reload NCAA, verify, and save.

## O. Player progression and development

Use player-development information to understand likely direction, role, and roster value across seasons. Development Reserve preserves a player's progression during its one-season use; Championship Development Edge is a time-bounded reward choice, not an endlessly stacking boost.

Do not treat analysis or a projected overall as a native edit. GDE distinguishes planning information from supported writeback workflows.

## P. Returning Development Reserve players

In the offseason after a Reserve season, every Reserve player must resolve through **Activate**, **Transfer**, or **Cut**. Review active count, Reserve count, controlled population, position health, and eligibility first. Activation returns a player to the active NCAA roster only if the supported workflow can validate a legal result.

## Q. Position Change Lab

Position Change Lab is **read-only**. It does not change an NCAA position, rating, body, eligibility, depth chart, roster count, transfer result, or native save.

It evaluates target-position fit with:

- **Excellent Fit** — a credible, high-confidence target role.
- **Good Fit** — a strong option with meaningful context.
- **Viable Depth** — useful information, not an automatic recommendation.
- **Emergency Only** — a limited contingency, not a roster-building plan.
- **Poor / Invalid** — not a credible conversion.

The projected target-position OVR is an explainable estimate based on target skills, body/athletic context, role impact, team need, and career projection. It is not a fixed overall delta or a claim to recreate NCAA's internal overall formula.

[SCREENSHOT: Position Change Lab target analysis]

## R. Offseason Decision Center

The Offseason Decision Center answers: **“What decisions do I need to make?”** It combines Active, Reserve, and temporary staging; roster compliance; position health; Keep, Reserve, Transfer, and Cut candidates; position-change candidates; and recruiting/portal needs.

It is a projected-roster workspace. Recommendations are explainable and hand off to their authoritative workflows; they do not silently apply NCAA changes. A legal active roster does not have to equal 70—70 is the maximum.

## S. Dynasty What-If Simulator

The What-If Simulator answers: **“What happens if I make these decisions?”** Build multi-action scenarios using transfers, cuts, Reserve, recruiting/portal additions, and credible position changes. Compare before/after counts, health, needs, and decisions; save scenarios for later comparison.

**SIMULATION DOES NOT MODIFY NCAA OR AUTHORITATIVE GDE STATE.** A saved scenario becomes stale when the real roster changes and must be recalculated before relying on it.

[SCREENSHOT: What-If scenario comparison]

## T. Roster reconciliation and cuts

Before a new season, reconcile active roster, Reserve, portal movement, graduating players, and position need. Use supported cut/reconciliation workflows only after saving NCAA and closing RPCS3. GDE validates the intended source state and preserves a managed recovery path.

Never use cuts to make a short roster look compliant: position health and legal maximums matter more than forcing a count of 70.

## U. Starting the next season

When portal, Reserve, reconciliation, recruiting, and supported preseason steps are resolved, verify the NCAA roster and season state, save in NCAA, and begin the next year. Sync GDE after meaningful NCAA changes to preserve history and keep planning information current.

## V. History, analytics, and team resume

GDE keeps long-term team/player history, analytics, and resume context so decisions are not made from one screen or one week alone. These views are read-only. They help explain progress, performance, and program direction without changing the save.

## W. Backups, recovery, and upgrades

GDE keeps persistent user data separate from the application, makes automatic backups, supports `.gdebackup` export/import, and performs explicit schema migration. Automatic backups retain the newest 10; manual and pre-migration backups are preserved outside that rolling limit.

For a normal update, install the newer release, launch GDE, allow it to back up/migrate/validate existing data, then confirm your selected dynasty. Use export/import to move computers or create an extra safety copy. See [Backup, Restore, and Upgrade](backup-restore-upgrade.md).

## X. Troubleshooting and safe rollback

- If GDE reports that RPCS3 is running, close it before sync, restore, or writeback.
- If a native action is refused, do not alter the source save to work around the check. Review the message and sync the correct closed save.
- If an applied result is not what you expected after reloading NCAA, stop, do not continue advancing, and use the recorded backup/rollback path.
- If GDE cannot open data, preserve the database and logs; it intentionally fails closed rather than creating a blank replacement.
- If a dynasty is not found, select the parent `savedata` directory and confirm the complete save is readable.

For data recovery and migration details, use the [Backup, Restore, and Upgrade guide](backup-restore-upgrade.md). For intentionally deferred scope, see [Known Limitations](known-limitations.md).
