# CAN Battery Monitor (AP_Periph / DroneCAN)

> Portfolio reference work derived from public job postings (CONTEXT-BOUND / PLANNED). Source jobs are requirements inspiration only; no client execution, fabrication, bench test or production claim is made.

**Status:** INITIAL / EVIDENCE REQUIRED · **Workspace phase:** Phase 2 · **Source:** JOB-03
**Handoff ID:** `CAN-ENERGY-PORTFOLIO-2026-09-15` · **Drive folder:** `Projelerim / Elektrik-Elektronik Mühendisliği / 15.09.2026 / 002-Proje Çıktıları / 03_can_battery_monitor`

## Goal
Connect battery measurements to a CAN-based telemetry architecture inspired by JOB-03.

## Current scope
Phase 2 project; implementation directories are deferred until measurement and protocol interfaces are explicit. Canonical requirement prefix: `BAT-` (not yet defined).

## Required future artifacts
Measurement requirements/architecture, calibration strategy, CAN protocol map, fault model, firmware architecture, simulation plan, bench test plan, decision register and validation matrix.

Empty implementation-stage directories are intentionally not created until useful artifacts exist.

## Repository layout
```
can-battery-monitor-ap-periph/
├─ README.md
└─ docs/00_shared/   # governance mirrored from workspace
```

## Governance
- Source jobs are requirements inspiration only; they are not evidence of client execution.
- VERIFIED / VALIDATED / TESTED / PASS / COMPLETE / PRODUCTION READY / MANUFACTURING READY require evidence paths — see [evidence_policy](docs/00_shared/evidence_policy.md).
- Hardware status is limited to DESIGNED, SIMULATED, FABRICATED, ASSEMBLED, BENCH_TESTED, FIELD_TESTED — see [terminology](docs/00_shared/terminology.md).
- Major architecture choices are recorded in decision registers; unknowns remain OPEN or BLOCKED — see [engineering_rules](docs/00_shared/engineering_rules.md).

## Workspace execution order

| Phase | Scope |
|---|---|
| 0 | Governance + job-source map + requirement templates |
| 1 | Project 01 and Project 02 baselines |
| 2 | Project 03 |
| 3 | Project 04 |
| 4 | Cross-project consistency |
| 5 | Releases only when evidence is traceable |

Related repositories: see [portfolio_map](docs/00_shared/portfolio_map.md).
