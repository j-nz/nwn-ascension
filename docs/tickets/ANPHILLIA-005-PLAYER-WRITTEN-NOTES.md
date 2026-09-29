# ANPHILLIA-005 — Physical player-written notes, letters and evidence

**Status:** OPEN  
**Parent:** ANPHILLIA-000  
**Donor:** https://github.com/mtijanic/anphillia/blob/master/tools/note.nss

## Objective
Add physical writable note/letter items, distinct from persistent cartographic map notes.

## Player flow
Create -> set title/body -> preview -> edit before finalisation -> finalise -> copy where permitted.

## Integration
Use the current chat-command framework and document it in !commands. Preserve author/provenance metadata, creation/finalisation/copy timestamps and copier identity as appropriate. Integrate with RP item editing so provenance cannot be silently destroyed. Expose hooks for investigation, alteration/forgery and evidentiary use. Builder-authored immutable documents remain protected.

## Guardrails
Text length/sanitisation; no protected/quest/system copying; no script/data injection; decide whether copying consumes blank paper.

## Acceptance
All flows work; originals preserve provenance; copies are metadata-distinct; protected documents cannot be cloned; !commands and investigation documentation are updated.