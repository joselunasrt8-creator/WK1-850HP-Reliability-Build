# Source Record — WK1 Route B Build Book

**Original source:** `WK1_Route_B_Build_Book.pdf`  
**Role:** execution-control plan for a complete Trackhawk 6.2 / 8HP95 / MP3015C transplant after donor purchase.

## Mission captured by the source

Convert Route B from a proven concept into a **minimum-measurement, minimum-fabrication execution plan**. The book begins after donor purchase and deliberately stops the broad CAD hunt.

## Locked execution assumptions

- Complete Trackhawk 6.2 + AWD 8HP95 + MP3015C kept mated as long as practical.
- WK1 body/cradle/suspension architecture retained.
- WK1 front/rear differentials retained initially, then strength-gated.
- Custom front/rear driveshafts expected; no shaft ordered before installed coordinates are frozen.
- Donor powertrain/security network preserved and bench-proven before permanent installation.

## Four hard rules

1. Keep the donor operating and complete until electronic dependencies are recorded.
2. Preserve WK stock driveline coordinates before removal.
3. Trial-fit the complete mated donor stack before structural cuts or fabrication release.
4. If the answer exists on the actual WK or donor, mark **MEASURE** and close it physically.

## G00–G10 gate structure

The source requires explicit PASS/FAIL gates for:

- donor baseline and module inventory,
- WK datum repeatability,
- post-removal WK scan registration,
- mated donor capture,
- bench network validation,
- reversible trial fit,
- mount/crossmember release,
- frozen driveshaft geometry,
- cooling/fuel/exhaust/steering integration,
- stationary commissioning,
- progressive road-load validation.

## Measurement doctrine

- Shared right-handed coordinate system tied to WK factory PLP targets.
- Direct measurement for holes, pilots, threads, flange faces, axes, and sealing surfaces.
- Scan/photogrammetry used for envelopes/corridors only.
- Every measurement records tool, setup, operator, repeat count, uncertainty, and photo/file trace.
- No untraceable number enters a fabrication drawing.

## Electronics conclusion

Primary strategy: preserve a functioning donor powertrain/security network and expose only controlled WK body interfaces.

The source explicitly states:

- the 2008 WK and Trackhawk CAN networks are **not presumed compatible**;
- the donor PCM, 8HP mechatronic/TCM, DTCM/MP3015C, shifter, security/gateway nodes, and required chassis-state inputs must be bench-validated;
- wheel-speed, steering/yaw, brake-state, and torque-management dependencies must be demonstrated rather than assumed;
- no permanent harness thinning occurs before the donor network works on the bench.

## Fabrication release principle

Mounts, crossmember, shafts, exhaust, and cooling packages are released only from measured geometry and reviewed gates. Static screenshots are not acceptance evidence; motion, heat, service access, working angles, critical speed, and vendor review are required where applicable.

## Source boundary

This build book is not evidence that Route B is inherently better than Route A. It is evidence that Route B can be executed in a controlled manner **after** the complete donor exists and its geometry/electronics can be measured and validated.

## Unresolved questions left by this source

1. Exact donor-specific CAN/message dependencies and whether a third-party controller can materially reduce retained donor-network scope.
2. Exact MP3015C/DTCM requirements in a WK1 environment.
3. Real installed clearances and driveline geometry; all remain MEASURE until hardware exists.
4. Final durability of retained WK1 differential/CV components at the selected power/launch duty.
