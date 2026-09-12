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
- `docs/RESEARCH_STATUS.md` — what has been established, what remains uncertain
- `data/parts-budget.csv` — working sourcing/budget matrix
- `issues/` — unresolved engineering questions should be tracked as GitHub Issues

## Design principles

1. Preserve native WK1 geometry where evidence supports it.
2. Upgrade components because the duty cycle requires it, not because aftermarket parts exist.
3. Treat shock load, heat, and torque delivery as separate from peak horsepower.
4. Preserve transmission torque management during WOT shifts.
5. Measure before fabricating.
6. Prefer documented completed builds and builder technical evidence over marketing claims.
7. Keep the project serviceable and street-usable in hot-weather, A/C-on driving.

## Target duty cycle

- ~850 WHP
- street driven
- repeated hard acceleration
- occasional hard launches
- drag radials acceptable
- no requirement for repeated transbrake/two-step/slick launches
- 95°F summer operation with A/C
- repeated pulls without overheating, slipping, limp mode, or driveline damage

## Status

Architecture research is mature enough to proceed into **vendor validation, sourcing, and build-cost optimization**.
