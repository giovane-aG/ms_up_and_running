# OPM1: Use ADRs for decision tracking

## Status
Accepted

## Context
A microservices architecture is complex and we'll need to make many decisions. We'll need a wat to keep track of the important  decision we make, so that we can revisit and re-evalute them in the future.
We'd prefer to use a lightweight, text-based solutions so that we don't haveto install any new software tools.
## Decision
We've decided to use Michael Nugard's lightweight architectural decision record (LADR) format. LADR is text based and is lightweight enough to meet our needs. We'll keep each LADR record in tis own text file and manage the files like code.

We also considered the floowing alternative solutions:
* Project management tooling (not selected, bevause we didn't want to install tools)
* Informal or "word of mouth" record keeping (not reliable)

## Consequences
* We'll need to write decision records for key decisions
* We'll need a source code management solution to mage dicision record files