# Operator Brief: Carson

Carson gets a local, deterministic pressure test around carson, whole, and pitch. The useful part is the repeatable evidence path from fixture to failure to operator action.

## Highest-leverage checks

- carson evidence replay -> block release until cited evidence is regenerated (carson_coverage, evidence ev_0088).
- generative operator packet -> accept only if decision claims cite fixture evidence (whole_risk, evidence ev_0055).
- pitch regression harness -> open a regression issue with trace and benchmark delta (pitch_precision, evidence ev_0066).
- whole boundary probe -> route to reviewer with evidence packet (generative_latency, evidence ev_0077).

## What makes this useful

The workflow is intentionally local and deterministic. A reviewer can run the same fixture set, inspect the evidence IDs, open the dashboard, and see exactly why a recommendation passed, went to review, or blocked.
