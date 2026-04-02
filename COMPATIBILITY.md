# Compatibility Doctrine

## Core rule

For multiplayer testing, every client should match on:

- **Kenshi version**
- **runtime files**
- **mod set**
- **mod versions**
- **load order**

## Why this matters

Kenshi was not built as a native multiplayer game. Once you add a multiplayer runtime layer, any mismatch can create:
- missing entities
- broken UI layouts
- invisible equipment or models
- differing world state
- crashes during join/load/combat

## Multiplayer-safe categories

Usually safer:
- UI mods
- texture/style mods
- some mesh fixes
- some non-invasive quality-of-life mods

Higher risk:
- world overhauls
- faction rewrites
- economy rewrites
- recruitment system changes
- settlement/world state changes
- scripted event-heavy mods

## Policy this repo should adopt

- maintain a **tested whitelist**
- maintain a **known-risk list**
- reject “everything pack” thinking until it has been validated
- treat load order as part of the protocol, not a suggestion

## Mac + Windows note

The safest practical target is usually:
- same Kenshi build
- same runtime version
- same mod manifest
- Windows-native or compatibility-layer client parity

Do not assume “Mac” means a native macOS Kenshi client stack.
