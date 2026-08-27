# Preflight Balance Data

Shared research corpus for Preflight's optional Balance Lab / Compendium work.

This repository exists so balance analysis does not depend on access to one maintainer machine. It stores versioned, machine-readable facts, normalized human observations, model inputs, and reproducible analysis code/results.

## Data layers

- `snapshots/` — version-labelled canonical content snapshots and exact extracted facts.
- `observations/` — normalized tier lists, pairwise claims, build notes, patch judgments, and other human evidence.
- `schemas/` — versioned contracts for snapshots and observations.
- `analysis/` — reproducible notebooks/scripts and retained research outputs.
- `models/` — versioned model policies/artifacts when the first real fitted models exist.

Heavy raw material belongs in the connected Google Drive workspace `Preflight Balance Lab Research`:

- `00 Raw Sources`
- `01 Canonical Game Snapshots`
- `02 Normalized Corpus`
- `03 Tournament + Video Evidence`
- `04 Analysis + Model Runs`

GitHub is the reproducible machine-readable layer. Drive is the bulky/raw research archive.

## Authority rule

Keep these separate:

1. source/public observation;
2. exact game/mod fact for a named content version;
3. normalized comparative claim;
4. derived analysis/model output.

A community rating is evidence about human judgment, not game-data truth. Wiki-derived records are useful public calibration snapshots; an exact installed-game extractor is the eventual authority for a player's current mod profile.

## Reference eDP versus local meta

A canonical `reference eDP` belongs to an exact item/version under a named policy. A heavily modded profile can change peer percentile and matchup exposure without silently rewriting that canonical value. Profile-specific eDP must carry a separate profile/policy identity.

## Current seed

The initial corpus is being staged in `teamleaderleo/preflight` PR #1151 and research issues #1148/#1149. Migrate that seed here before expanding it further.

The first seed deliberately contains cases that falsify simple spreadsheet scoring, including Onslaught/Onslaught XIV, Anubis, Doom/Afflictor, Executor/Pegasus, Light Assault Gun/Light Needler, Antimatter Blaster, LR PD Laser, Harpoon, and Annihilator.

## Redistribution boundary

Public-source facts, derived tables, source links, schemas, analysis code, and original research notes are appropriate here. Do not commit licensed Starsector distribution files, private mod archives, personal/local paths, credentials, or third-party material without redistribution permission.
