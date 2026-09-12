# Source Evidence Index

This directory normalizes the project's existing research into auditable source records. Each record preserves what a source actually establishes, its confidence, its boundary, and the unresolved question it leaves behind.

## Evidence classes

- **Verified** — OEM/factory datum, direct measurement, or traceable exact specification.
- **Strong reference** — credible technical/vendor or scan-derived reference that must still be checked against the actual vehicle/part revision.
- **Observed build evidence** — documented running/completed build or builder statement; supports only the configuration/result actually shown.
- **Engineering recommendation** — synthesis based on multiple sources; not itself a lifetime/durability proof.
- **Proxy / approximate** — family-level or non-exact geometry suitable only for rough packaging/reference.
- **Unknown / MEASURE** — must be closed by direct measurement, donor-specific wiring, bench validation, or logged testing.

## Ingested source records

1. `WK1_Digital_Build_Asset_Map.md` — source-quality map, datum hierarchy, quarantined GLB findings, and free-data boundaries.
2. `WK1_Free_Only_Feasibility_Sprint.md` — Route A vs Route B feasibility evidence, verified WK facts, missing-data gates, and decision matrix.
3. `WK1_Route_B_Build_Book.md` — execution-control evidence for Route B, especially measurement, fabrication-release, CAN/network, and commissioning gates.
4. `WK1_850_WHP_Reliability_Build_Investigation.md` — decision-grade Route A durability specification and 2026 cost model.
5. `Trackhawk_8HP95_Feasibility_Research.md` — earlier Trackhawk/8HP95 feasibility research retained as historical supporting evidence; later sprint/build-book work supersedes any stronger claims not revalidated.

## Governing rule

A source may support integration, geometry, power, performance, durability, or control strategy. Those evidence types are not interchangeable. A running swap is not automatically durability proof; a vendor power rating is not automatically a measured reliability envelope; and a part identity does not establish a fabrication surface.

See `../docs/EVIDENCE_MATRIX.md` and `../data/evidence-matrix.csv` for claim-level traceability.
