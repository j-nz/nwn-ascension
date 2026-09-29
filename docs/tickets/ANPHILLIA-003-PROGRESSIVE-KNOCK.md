# ANPHILLIA-003 — Progressive Knock and caster–rogue cooperation

**Status:** OPEN  
**Parent:** ANPHILLIA-000  
**Donor:** https://github.com/mtijanic/anphillia/blob/master/spells/nw_s0_knock.nss

## Objective
Evaluate and adapt Anphillia's partial-success Knock mechanic within Ascension's governed door stack.

## Work
Inspect current `nw_s0_knock` and door behaviour first. Preserve special-key, plot, scripted, Knock-immune and linked-mechanism restrictions. Define a level-21-appropriate casting check. On partial success, temporarily weaken unlock DC rather than opening the lock outright. Define duration, floor, stacking rules and feedback.

Original DC must restore safely after timeout, reset, close/relock, interruption and repeated Knock attempts.

## Acceptance
Protected doors cannot be bypassed; temporary changes never become permanent; stacking cannot reduce below governed floor; Open Lock remains valuable; existing door lifecycle remains intact; success/partial/failure/immunity/key/restoration cases are tested.