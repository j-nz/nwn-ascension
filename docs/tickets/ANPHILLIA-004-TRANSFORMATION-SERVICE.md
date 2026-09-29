# ANPHILLIA-004 — Reusable blueprint-swap transformation service

**Status:** OPEN  
**Parent:** ANPHILLIA-000  
**Donor:** https://github.com/mtijanic/anphillia/tree/master/creature — `lycan_cfg.nss`, `lycan_inc.nss`, `lycan_heartbeat.nss`, `lycan_onspawn.nss`

## Objective
Generalise Anphillia's day/night lycanthrope swap into a safe Ascension transformation service.

## Uses
Day/night monsters, cursed NPCs, Drey/planar forms, infiltrators/disguises, staged encounters and story transformations.

## Requirements
Preserve governed state such as HP percentage, location/facing, faction/hostility, relevant locals, encounter ownership and persistent identity. Explicitly define inventory/equipment/effects/spells/AI/death/loot behaviour. Support VFX, animation and dialogue hooks. Avoid duplicate actors, orphaned objects and encounter-count corruption. Builder-facing controls must use governed non-AI prefixes; AI_* remains internal.

## Acceptance
At least one reversible day/night demonstration; HP ratio verified; no item/loot duplication; encounter lifecycle remains correct; reset persistence policy documented; builder example included.