# ANPHILLIA-010 — Regenerating breachable barriers

**Status:** OPEN  
**Parent:** ANPHILLIA-000  
**Donor:** https://github.com/mtijanic/anphillia/blob/master/utils/anph_gate_ondmg.nss

## Objective
Adapt Anphillia's regenerating gate idea into a governed encounter/placeable component for temporary breaches.

## Uses
Sieges, dungeon gates/barricades, timed breaches, alarm/reinforcement hooks.

## Requirements
Builder-configurable breach conditions, temporary open/unlock state, repair delay and encounter/event signal. Integrate with current door/placeable/encounter lifecycle rather than creating a parallel framework. Preserve plot/key/scripted protections. Repair must be idempotent across encounter reset/empty area/state changes.

## Acceptance
One encounter example demonstrates breach -> signal/alarm -> passage -> repair/reseal; no permanent state corruption; simultaneous attackers cannot duplicate events/rewards; builder documentation included.