# WK1 850HP Reliability Build

Reliability-first engineering and sourcing repository for a **2008 Jeep Grand Cherokee SRT8 (WK1)** targeting approximately **800–850 WHP** while retaining AWD street manners.

## Locked baseline architecture

**Hellcat/Redeye 6.2 → performance-built NAG1/W5A580 → NV146 → WK1 3.73 differentials → strengthened driveline as required**

The project deliberately prioritizes durability, thermal control, torque management, traction, and serviceability over peak dyno output.

## Current verdict

**YELLOW — build with operating limits.**

A reliable 800–850 WHP street configuration is defensible with a max-effort NAG1, proactively built NV146, upgraded driveshafts and rear axles, refreshed stock-size differentials, rear Wavetrac, serious cooling, and preserved torque reduction during shifts.

Repeated two-step / slick launches are outside the intended design envelope.

## Repository map

- `docs/ARCHITECTURE.md` — locked system architecture and design philosophy
- `docs/BUILD_SPEC.md` — current recommended 850-WHP drivetrain specification
- `docs/EVIDENCE_MATRIX.md` — auditable claim → source → confidence → unresolved-question matrix
- `docs/OBSERVED_BUILD_EVIDENCE.md` — documented real-world build observations, separated from durability claims
- `docs/RESEARCH_STATUS.md` — what has been established, what remains uncertain
- `sources/README.md` — normalized source-evidence index
- `sources/` — ingested research records from the asset map, feasibility sprint, Route B Build Book, Route A reliability investigation, and historical Trackhawk research
- `data/evidence-matrix.csv` — machine-readable evidence matrix
- `data/parts-budget.csv` — working sourcing/budget matrix
- `issues/` — unresolved engineering questions should be tracked as GitHub Issues

## Evidence model

The repository separates different kinds of proof:

- **Integration evidence** — demonstrates that components/configurations have physically been made to work together.
- **Power evidence** — dyno or other measured output.
- **Performance evidence** — documented track/acceleration results.
- **Durability evidence** — repeated passes, mileage, service history, temperatures, failures and corrective changes.

A running swap or dyno number alone is not treated as proof of long-term reliability.

Every major locked claim should be traceable through `docs/EVIDENCE_MATRIX.md`. A claim is promoted in confidence only when new evidence directly closes its listed unresolved question.

## Design principles

1. Preserve native WK1 geometry where evidence supports it.
2. Upgrade components because the duty cycle requires it, not because aftermarket parts exist.
3. Treat shock load, heat, and torque delivery as separate from peak horsepower.
4. Preserve transmission torque management during WOT shifts.
5. Measure before fabricating.
6. Prefer documented completed builds and builder technical evidence over marketing claims.
7. Keep the project serviceable and street-usable in hot-weather, A/C-on driving.
8. Distinguish observed configuration from inferred durability.
9. Do not allow proxy geometry or historical estimates to silently become fabrication authority.

## Target duty cycle

- ~850 WHP
- street driven
- repeated hard acceleration
- occasional hard launches
- drag radials acceptable
- no requirement for repeated transbrake/two-step/slick launches
- 95°F summer operation with A/C
- repeated pulls without overheating, slipping, limp mode, or driveline damage

## Current real-world integration evidence

An observed Hellcat-WK1 build supplied to the project reports use of a complete Hellcat 6.2, stock 6.1 WK1 engine mounts, stock WK1 ECU/harness, a 6.1-style crank tone-ring conversion, VVT lockout, Hellcat MAP sensor, and a stock-internal NAG1 with a Dings 200% valve body.

This materially supports the native-integration concept, but the available evidence does **not** establish its horsepower, NV146/driveline configuration, mileage, launch history, or 850-WHP durability. See `docs/OBSERVED_BUILD_EVIDENCE.md`.

## Source hierarchy

The current evidence base now records:

1. digital-asset/datum quality and proxy quarantine,
2. free-only Route A vs Route B feasibility,
3. controlled Route B execution requirements,
4. decision-grade Route A 850-WHP durability specification,
5. observed real-world Hellcat/WK1 integration evidence,
6. historical Trackhawk/8HP95 research retained with superseded claims clearly marked.

## Status

The repository is now an **auditable engineering knowledge base**. Architecture research is mature enough to proceed into **vendor validation, sourcing, build-cost optimization, measurement closure, and systematic collection of project durability evidence**.
