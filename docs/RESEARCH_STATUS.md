# Research Status

## Closed / strong conclusions

- Route A is the current primary architecture for a reliability-first ~850-WHP WK1.
- The NAG1/NV146 path preserves substantially more native WK1 geometry and controls than an 8HP95/Trackhawk-AWD transplant.
- Peak horsepower alone is not the main durability threat; launch shock, tire grip, torque intervention, and heat are equally important.
- A max-effort NAG1, proactively built NV146, upgraded driveshafts, HD rear axles, rear LSD, and strict torque management form the current defensible reliability package.
- The front differential and front CV architecture should be retained initially unless inspection or real use demonstrates a need to replace them.
- Native 2008 WK1 controls are now the preferred baseline for Hellcat/Redeye 6.2 integration rather than assuming a standalone ECU or wholesale late-model electronics conversion.
- Direct swap evidence supports starting with stock 6.1 WK1 mounts, the stock WK1 harness/PCM, early-style 32T crank signal conversion, and VVT lockout.
- The 32T crank strategy is technically supported by Gen III HEMI trigger documentation, but cam synchronization must still be bench-verified.
- WOT shift torque management remains a structural drivetrain-protection requirement and must be preserved with the built NAG1.

## Current verdict

**Drivetrain: YELLOW — build with operating limits.**

The expected reliable envelope is approximately 800–850 WHP with controlled launches and preserved WOT shift torque reduction.

**Native 6.2 integration: YELLOW-GREEN — preferred baseline, pending bench/commissioning gates.**

Promote native integration to GREEN only after CKP/CMP sync, knock sensing, DBW, charging, OEM-function acceptance, and staged thermal/power validation pass.

See `docs/NATIVE_INTEGRATION_CLOSURE.md` for the controlling integration investigation.

## Evidence hierarchy

Use evidence in this order:

1. completed vehicles with documented configuration, performance, and service history
2. OEM / factory / primary technical documentation
3. builder technical documentation
4. attributable owner/build threads or videos
5. manufacturer claims
6. forum speculation only as a lead

## Open questions

### Integration P0

1. What exact cam target / sensor arrangement gives stable CKP/CMP synchronization with the 2008 WK1 PCM after VVT lockout?
2. Which knock sensors, mounting strategy, and calibration provide trustworthy knock detection on the 6.2 under boost with the 2008 PCM?
3. Does the chosen Hellcat throttle body operate correctly under the 2008 WK1 DBW strategy, or is an early-compatible throttle body required?
4. Does the donor alternator integrate correctly with the WK1 charging-control strategy?
5. What oil pan / pickup configuration clears the WK1 front differential and cradle while preserving correct oil control?
6. Does the 2008 PCM calibration provide sufficient MAP, injector, airflow/load, knock, and torque-model range for the final 800–850 WHP target?

### Drivetrain / vendor validation

7. Which vendor provides the best value for the required max-effort NAG1 hardware specification?
8. Which NV146 builder provides the strongest documented upgrade package and service support?
9. What converter stall / lockup strategy best balances street manners, heat, and launch durability with the selected 6.2 combination?
10. Which driveshaft vendor should own final joint, tube, critical-speed, and balance specification?
11. What exact rear axle / hub package gives the best durability-to-cost ratio?
12. What transmission-temperature limits does the selected builder require for warranty / service life?
13. What torque ceilings should be finalized in first and second gear after logged testing?
14. Does the stock front differential remain reliable under the final tire and launch strategy?
15. Which suspension / bushing changes reduce wheel hop without making the Jeep harsh?

## Do not reopen unless new evidence appears

- Broad Route A vs Route B feasibility debate
- Generic 8HP95 CAD hunting
- Unrestricted 1,000+ WHP race architecture
- Standalone ECU as the default assumption
- Custom engine mounts as the default assumption

## Next phase

**Bench closure + vendor validation + sourcing.**

Create measured/logged closure for:

- CKP/CMP synchronization
- knock-sensor validation
- DBW compatibility
- alternator/charging control
- oil pan/front-diff clearance
- A/C integration
- OEM-function acceptance
- WOT torque-management logging

In parallel, obtain comparable quotes and build sheets for:

- max-effort NAG1
- multi-disc converter
- built NV146
- front/rear driveshafts
- rear Wavetrac / differential refresh
- rear axle shafts
- transmission cooling
- tuning / commissioning

The next decision should be based on exact hardware, measured fitment, logged behavior, support, lead time, and total installed cost rather than vendor stage labels or generic swap assumptions.
