# Kenshi Multiplayer Modpack

A commit-ready GitHub package for a **Kenshi multiplayer-focused modpack** built around a bundled Kenshi multiplayer runtime plus a curated `ModpackV1` archive set.

This repository packages three things together:

1. **Multiplayer runtime files** in `KenshiMP-Install/`
2. **Current mod archives** in `ModpackV1/`
3. **Project documentation and GitHub community scaffolding** so the repo is understandable, maintainable, and easier to discover

## Current Status

This repo is a **distribution and organization layer** for the current multiplayer setup.

- The multiplayer client/server binaries are included
- The modpack archives are included as provided
- The repo now includes install, compatibility, roadmap, contribution, and manifest docs
- `manifest.json` includes SHA-256 hashes for the current `ModpackV1` contents

## Repository Layout

```text
KenshiMP-Install/
  client/
    KenshiMP.Core.dll
    KenshiMP.Injector.exe
    Kenshi_MainMenu.layout
    Kenshi_MultiplayerHUD.layout
    Kenshi_MultiplayerPanel.layout
  server/
    KenshiMP.Server.exe

ModpackV1/
  <current archive set>

.github/
  ISSUE_TEMPLATE/
  pull_request_template.md

README.md
INSTALL.md
COMPATIBILITY.md
MODLIST.md
ROADMAP.md
manifest.json
```

## What this repo is for

Use this repo if you want a single GitHub home for:

- your Kenshi multiplayer runtime files
- your current multiplayer-oriented modpack archives
- future tested load orders and compatibility notes
- submissions, issue tracking, and public-facing project documentation

## Important Reality Check

This repository does **not** claim that every archive in `ModpackV1/` has already been fully validated for long-session multiplayer stability.

Right now the correct framing is:

- **multiplayer runtime included**
- **modpack archives included**
- **manifest + structure added**
- **full compatibility certification still in progress**

## Fast Start

Read these first:

- [INSTALL.md](INSTALL.md)
- [COMPATIBILITY.md](COMPATIBILITY.md)
- [MODLIST.md](MODLIST.md)
- [ROADMAP.md](ROADMAP.md)

## Modpack Manifest

The current tracked modpack files are listed in `manifest.json` and summarized in [MODLIST.md](MODLIST.md).

## SEO / Discoverability Notes

Suggested GitHub topics for this repository:

- `kenshi`
- `kenshi-mods`
- `kenshi-multiplayer`
- `modpack`
- `open-source`
- `game-modding`
- `pc-gaming`
- `rpg`
- `sandbox-game`
- `multiplayer-mod`

Suggested repo description:

> Kenshi multiplayer modpack repository with bundled multiplayer runtime, install docs, manifest hashes, compatibility notes, and modpack roadmap.

## Included Modpack Files

- `Animal Traders-134-13-1546402785.7z`
- `AnimalBackpacksRus-212-16-1547914346.rar`
- `AnimalTradersRus-213-17-1547914706.rar`
- `Darker Nights and ReShade-241-1-1-1549850352.7z`
- `DesertUI-1004-1-2-5-1656861093.7z`
- `Engine Mesh Updater-1212-2-0-2-1736972652.zip`
- `euro swords-126-idk.zip`
- `Hive Cybernetics Expansion V1.1-1231-1-1-0-1689337937.zip`
- `Kenshi tweaks-447-2-8-3-1684227116.zip`
- `Kenshi_CTD_Fix-506-1-5-1717034322.zip`
- `M.U.D.-403-4-03-1663634888.rar`
- `Mad Monks-22--63.7z`
- `Naginata 0.74.25-1-.zip`
- `Nation Rising-24-1-2.zip`
- `No Stat Backpacks-165-1-0-1590633184.rar`
- `No Stat Backpacks.mod`
- `Particle system override (installer)-950-3-4-1701958188.zip`
- `Rag Short Loincloth-183-1-00-1546670695.7z`
- `Recruitable Prisioners Patch (IdeaDork)-1063-1-0-1661734748.rar`
- `Recruitable Prisoners-418-2-1560768753.rar`
- `ShaderSaturation-219-1-0-1548136560.zip`
- `Shirts For All-411-3-0-1562767510.zip`
- `SleepOnFloor-103-0-1.rar`
- `Slopeless-398-6-1599773032.zip`
- `T2SwiD - Universal Wasteland Expansion Add-on-1131-1-11-1704780982.zip`
- `United Cities Heightened-141-1-4-1553911379.rar`

## Next Priority

The next serious upgrade is to move from a raw archive collection to a **fully locked multiplayer-safe pack** with:

- tested load order
- enabled/disabled matrix
- conflict notes
- safe/risky tags
- version-locked releases
- install automation where legally and technically appropriate
