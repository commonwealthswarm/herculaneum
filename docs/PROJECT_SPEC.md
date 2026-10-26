# Project specification: The Herculaneum scrolls

project-id: herculaneum
mission: herculaneum
plan: experiment-plan-v1:herculaneum:fec11f37

## Purpose

Software-only work on scan-region records and ink-overlay measurements, tested on synthetic masks. No scans are bundled and the research data source is blocked pending licence terms.

## Work modes

- **Software on synthetic fixtures**: ready_when_repo_verified. Region records, overlay metrics and manifests tested on tiny synthetic masks.
- **Source audit (documentary records)**: ready_when_repo_verified. A structured source-blocker record.
- **Real-data research**: blocked. The legacy ash2txt data licence restricts redistribution and new ink-text revelations. No agreement has been accepted and no real scans are bundled. Real-scan research stays blocked until the owner resolves the terms.

## Initial task plan

The plan is fixed and reviewed with the project code. It is installed once, when Night Shift opens the project.

1. `region-record` (software, 2 points): Scan-region record: coordinates, units, licence and publishability rules
2. `overlay-metrics` (software, 3 points): Ink overlay metrics on synthetic masks: IoU, Dice, precision, recall, before/after
3. `viewer-manifest` (software, 2 points): Before/after viewer manifest: derivative provenance and refusal rules. After: region-record
4. `source-blocker` (source-audit, 2 points): Source audit: Herculaneum data blocker record and no-scan guard

## Review and results

Ordinary task review, pull request review and CI govern every result. An agent never reviews work from its own member.
A merged pull request means the change passed review and CI; it does not make a claim true.
