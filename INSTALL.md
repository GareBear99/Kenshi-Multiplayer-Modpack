# Install Guide

## 1. Requirements

- Same Kenshi game version on every participating machine
- Same multiplayer runtime files
- Same modpack contents
- Same final load order

## 2. Multiplayer Runtime

Client files are stored in `KenshiMP-Install/client/`.

Server files are stored in `KenshiMP-Install/server/`.

Current client bundle:

- `KenshiMP.Core.dll`
- `KenshiMP.Injector.exe`
- `Kenshi_MainMenu.layout`
- `Kenshi_MultiplayerHUD.layout`
- `Kenshi_MultiplayerPanel.layout`

Current server bundle:

- `KenshiMP.Server.exe`

## 3. Modpack Files

All current mod archives are stored in `ModpackV1/`.

Before multiplayer testing, every player should have:

- the same archive set
- the same extracted mod contents where required
- the same enabled mod list
- the same load order

## 4. Recommended Setup Flow

1. Lock the Kenshi game version.
2. Lock the multiplayer runtime version.
3. Lock the modpack version using `manifest.json`.
4. Verify hashes before play sessions.
5. Export and store the tested load order in the repo.
6. Only then begin multiplayer validation.

## 5. What still needs to be finalized

This repository still needs a final tested load order and a reviewed compatibility matrix for the included mod archives.

Until that is complete, treat this as a **structured project package**, not a fully certified one-click install.
