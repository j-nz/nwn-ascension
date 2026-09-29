# ANPHILLIA-007 — Projectile-spell attack model prototype

**Status:** RESEARCH / PROTOTYPE ONLY  
**Parent:** ANPHILLIA-000  
**Donor:** https://github.com/mtijanic/anphillia/blob/master/spells/spell_missile.nss

## Objective
Prototype—not globally enable—Anphillia's ranged-touch/projectile model for selected missile spells or abilities.

## Research
Compare current/vanilla/donor behaviour. Assess AB vs touch AC, concealment, criticals, Spell Focus/Combat Casting, multi-projectile distribution, level-21 balance and compatibility with current spell hooks. Identify a very small representative test set.

## Guardrail
Initial work must be behind an internal/test-only switch. No global production spell replacement is authorised by this ticket.

## Acceptance
Written comparison; working test prototype for hit/miss/concealment/multi-projectile cases; affected scripts and regressions documented; production enablement requires a separate explicit decision.