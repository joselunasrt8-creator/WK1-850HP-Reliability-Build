# Source Record — WK1 Free-Only Feasibility Sprint

**Original source:** `WK1_Free_Only_Feasibility_Sprint.pdf`  
**Role:** Route A vs Route B architecture evidence package.

## Decision captured by the source

**Route A requires less custom engineering with the free evidence available.**

Route A:

**Redeye 6.2 → built NAG1 → NV146 → WK1 differentials**

was favored because it can preserve the existing transmission position, crossmember logic, NV146 placement, 3.73 axle set, differential locations, and potentially parts of the shaft architecture subject to measurement.

Route B:

**Hellcat/Trackhawk 6.2 → 8HP95 → MP3015C → WK1 differentials**

was judged the better high-torque production architecture, but not fabrication-ready from public data because the WK tunnel/cradle coordinates and the mated 8HP95/MP3015C geometry were not closed.

## Verified / strong facts

- WK1 wheelbase: **2781 mm**.
- Front/rear track: **1608 / 1577 mm**.
- Front/rear ring gear families: **200 / 226 mm**.
- Axle ratio: **3.73:1**.
- W5A580 ratios: **3.59 / 2.19 / 1.41 / 1.00 / 0.83**.
- Trackhawk 8HP95 bellhousing-plane-to-output reference: **634.1 mm** — strong reference, donor measurement still governs.
- Trackhawk output reference: **34.5 mm OD, 43 splines, ~4.1 in stickout** — interface sanity check only.
- Redeye installation information supplies verified fuel, main-cooling, charge-air-cooling, reservoir, heat-exchanger, and initial engine-angle requirements.

## Route A implications

- Chassis/tail-end confidence is comparatively high because stock drivetrain coordinates can be retained as the physical template.
- Main unresolved Route A fitment zones are forward of the bellhousing: sump/front diff/rack, blower/hood, FEAD/radiator/fans, headers/rails/steering, and ancillary cooling/fuel packaging.
- Built NAG1 and NV146 remain durability/heat/shock gates; the sprint explicitly warns not to treat the word `built` as a rating.

## Route B implications

- A complete donor is the cleanest source of mating interfaces and network components.
- Custom mounts, crossmember, both driveshafts, exhaust, cooling/fuel plumbing, wiring/network integration, and possible tunnel work are expected.
- Exact PCM/TCM/MP3015C and ABS/traction integration remained unverified.
- Bench-network validation was required before final mechanical installation.

## Architecture decision matrix

The source scored Route A higher for:

- chassis-coordinate reuse,
- tunnel/crossmember certainty,
- potential shaft reuse,
- free-model completeness,
- lower immediate custom engineering.

Route B scored higher for high-torque production matching.

## Missing-data gates

P0 measurement gates included:

- WK body datum registration,
- engine bay/front cradle/rack/diff surfaces,
- tunnel/crossmember geometry,
- stock crank/bellhousing/mount/TC-output coordinates,
- front/rear pinion flange faces and axes,
- dressed 6.2 geometry,
- mated 8HP95 + MP3015C geometry.

## Governing conclusion

Route A was the defensible free-only preliminary architecture. Route B remained the higher-capability branch and could be reopened if the Route A durability plan became inadequate or a complete Trackhawk donor became available for registered measurement and bench-network validation.
