# ANPHILLIA-001 — Smart buff sequencing

**Status:** OPEN  
**Parent:** ANPHILLIA-000  
**Donor:** https://github.com/mtijanic/anphillia/tree/master/spells — `esm_cfg.nss`, `esm_inc.nss`

## Objective
Deep-compare Ascension's existing Rod of Buffing / buff sequencer against Anphillia ESM and add only missing quality-of-life semantics.

## Current baseline
Ascension already records spell + metamagic and replays an active profile. Do not replace the profile architecture.

## Work
Audit active-effect detection, object/location targets, metamagic, unavailable/depleted spells, interruptions, hostile/invalid targets and partial failures. Add a safe smart-cast mode that skips a buff only when the intended target already has the relevant effect. Preserve normal spell-resource consumption and all anti-recharge controls. Give clear skipped/failed feedback.

## Acceptance
Existing profiles remain compatible; smart-cast has a documented active-effect test; replay never grants free spells or bypasses legality; recording/replay/depleted/invalid/already-active cases are tested; help/commands are updated if controls change.