# ANPHILLIA-008 — Rest ecology and wilderness interruption

**Status:** RESEARCH FIRST  
**Parent:** ANPHILLIA-000  
**Donor:** https://github.com/mtijanic/anphillia/tree/master/core — especially `chr_inc.nss`

## Objective
Evaluate useful rest-ecology ideas without importing old HCR/CNR assumptions.

## Work
Audit current rest restrictions, rest rings, safe areas, encounter spawning and anti-farm rules. Decide whether unsafe wilderness should support area-authored interruption hooks or encounters. Any spawned threat must use current encounter/mob-balancing architecture. Define cooldowns and reward suppression so repeated rest attempts cannot farm XP/loot.

## Guardrail
Any prototype is opt-in per area and disabled by default.

## Acceptance
Design decision precedes production code; no farm loop; party/rest state recovers correctly; safe hubs remain predictable; area-builder controls are documented if adopted.