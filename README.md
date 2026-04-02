# Kenshi Multiplayer Modpack

A curated **Kenshi multiplayer-oriented modpack repository** built around the idea of making a shared-world co-op setup easier to install, easier to audit, and easier to keep aligned across machines.

This repository is for people who want:
- a cleaner starting point for a **Kenshi multiplayer stack**
- a documented **same-version / same-modset** workflow
- a place to track **safe mods, risky mods, and compatibility notes**
- a repo that is easier to understand than a loose folder of archives

> **Important:** Kenshi is a single-player game. Real multiplayer requires a separate runtime layer, synchronized clients, and strict version matching. This repository packages the current install assets and mod archives, but it does **not** by itself turn vanilla Kenshi into native multiplayer.

## What is in this repo

- `KenshiMP-Install/` — current multiplayer runtime install assets
- `ModpackV1/` — archived mod packages currently included in this stack
- `docs/` — structure, roadmap, curation notes, and repo metadata
- community files for issues, reports, and pull requests

## Current project goals

1. Keep a **documented, repeatable install path** for the current Kenshi multiplayer setup.
2. Build a **multiplayer-safe mod list** instead of a random pile of cool mods.
3. Enforce a **same game version / same mod version / same load order** doctrine.
4. Turn the repo into a cleaner public-facing project that is easier to find, understand, and contribute to.

## Quick start

See these first:
- [`INSTALL.md`](INSTALL.md)
- [`MODLIST.md`](MODLIST.md)
- [`COMPATIBILITY.md`](COMPATIBILITY.md)
- [`ROADMAP.md`](ROADMAP.md)
- [`THIRD_PARTY.md`](THIRD_PARTY.md)

## Recommended repo description

Use this as the GitHub repository description:

**Curated Kenshi multiplayer modpack and install workflow focused on same-version co-op setup, compatibility notes, mod curation, and synchronized shared-world play.**

## Suggested topics

GitHub topics help classify repositories and improve discoverability.

Suggested topics for this repo:

`kenshi`, `kenshi-mods`, `kenshi-modpack`, `multiplayer`, `coop`, `modding`, `open-world`, `rpg`, `sandbox`, `survival`, `pc-gaming`, `game-modding`

More topic ideas are listed in [`docs/REPO_TOPICS.md`](docs/REPO_TOPICS.md).

## Current structure

```text
Kenshi-Multiplayer-Modpack/
├── KenshiMP-Install/
│   ├── client/
│   └── server/
├── ModpackV1/
├── .github/
├── docs/
├── COMPATIBILITY.md
├── CONTRIBUTING.md
├── INSTALL.md
├── MODLIST.md
├── ROADMAP.md
├── SECURITY.md
├── THIRD_PARTY.md
└── README.md
```

## Known realities

- Full Kenshi multiplayer depends on external runtime tooling, not normal data-only modding.
- Every player should use the **same Kenshi build**, **same mod archives**, and **same load order**.
- Big overhauls and world-state mods can desync or conflict unless they are deliberately curated.
- This repo should eventually move toward a **manifest-driven install and validation workflow**.

## Next steps

- normalize the mod list into a machine-readable manifest
- add per-mod source links and checksum tracking
- add a locked tested load order
- split safe vs risky mods
- add install validation scripts for same-version checks
- document Windows host + Mac via compatibility layer workflow if that is part of the target setup

## Community health

This repo now includes those scaffolding files so it reads like an actual project instead of an upload dump.
