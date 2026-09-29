# ANPHILLIA-002 — Settlement projects and community resource pools

**Status:** OPEN  
**Parent:** ANPHILLIA-000  
**Donor:** https://github.com/mtijanic/anphillia/tree/master/factions — `faction_donate.nss`, `faction_inc.nss`

## Objective
Adapt Anphillia's donation/resource-pool idea into an Ascension settlement/project economy without importing faction-war architecture.

## Candidate uses
Saltsprey/Newcastle rebuilding and defence; expeditions; temple/community works; Professor Ryan research/planar gates; Pillar-linked world-state projects.

## Design
Use Campaign DB. Define governed resource categories, valuation, rejected items, contribution/account logging, project targets/stages/completion hooks and repeatability. Builders should configure projects without new code where practical. Project state should be available to NPC dialogue/world-state hooks.

## Exploit controls
Reject plot/quest/bound/no-donation items and merchant/value loops. Prevent renamed/generated junk arbitrage and double-awards. No arbitrary player-created currency conversion.

## Acceptance
One pilot project works end-to-end; totals survive reset; contributions are auditable; invalid donations fail safely; stage transitions are idempotent; builder documentation exists.