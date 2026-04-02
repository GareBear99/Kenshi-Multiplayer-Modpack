# Installation

## Scope

This document explains the current repository layout and the intended install flow for the current package.

## Before you begin

You should lock these before multiplayer testing:

1. **Same Kenshi game version** on every machine
2. **Same multiplayer runtime files**
3. **Same mod archives and extracted mod contents**
4. **Same load order**
5. **Same settings profile** where relevant

If any of those drift, you increase the chance of desyncs, missing assets, broken UI layouts, or outright crashes.

## Repository folders

### `KenshiMP-Install/client/`
Client-side multiplayer runtime files currently included in the repo.

### `KenshiMP-Install/server/`
Server-side executable currently included in the repo.

### `ModpackV1/`
Compressed third-party mod archives currently stored in this repository.

## Recommended install flow

1. Install Kenshi.
2. Confirm every player is on the same game version.
3. Copy the current multiplayer client files into the target Kenshi install as required by the runtime.
4. Set up the dedicated server or host flow using the server package in `KenshiMP-Install/server/`.
5. Extract the selected mod archives from `ModpackV1/` into the Kenshi mods directory.
6. Apply the agreed load order.
7. Launch the same test save / same onboarding flow on every client.
8. Validate that every player sees the same UI, same assets, and same mod list before a real run.

## Recommended future improvement

The repo should evolve toward a manifest-driven installer with:
- file hashes
- exact load order export
- game version validation
- mod version validation
- install sanity checks

That would reduce “it works on my machine” failures.
