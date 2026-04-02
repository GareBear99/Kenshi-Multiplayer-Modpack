# Compatibility

## Hard Requirements

For a Kenshi multiplayer setup, these must match across all players:

- game version
- multiplayer runtime version
- modpack version
- mod archive hashes
- extracted mod contents
- final load order

## Current State

This repository includes the current multiplayer runtime bundle and the current `ModpackV1` archive collection, but the pack should still be treated as **validation in progress**.

## Recommended Rule Set

- Reject mixed game versions
- Reject mixed multiplayer runtime versions
- Reject mixed modpack hashes
- Reject mixed load orders
- Only promote mods into a release once they pass multiplayer testing

## Risk Categories

### Lower-risk candidates
Generally safer starting candidates for multiplayer evaluation:
- UI mods
- visual polish mods
- lighting/reshade style mods that do not alter game logic
- mesh fixes
- crash/stability helpers

### Higher-risk candidates
Require careful validation before being treated as multiplayer-safe:
- faction/world overhauls
- AI behavior changes
- recruitment system changes
- prisoner/recruitment overhauls
- base-building/world-state affecting mods
- mods with many patched dependencies

## Final Goal

The final public release should split mods into:

- `safe`
- `needs-testing`
- `unsafe-for-current-release`
