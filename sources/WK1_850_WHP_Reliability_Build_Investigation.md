# Source Record — WK1 850-WHP Reliability Build Investigation

**Original source:** `WK1_850_WHP_Reliability_Build_Investigation.md`  
**Pricing date:** 2026-09-08  
**Role:** decision-grade Route A durability synthesis.

## Fixed architecture

**Hellcat/Redeye 6.2 → built NAG1/W5A580 → NV146 → stock-location 3.73 front/rear differentials**

Duty cycle: street use, E85/high-octane fuel, repeated pulls, occasional drag-radial launches, 95°F Chicago operation with A/C.

## Engineering verdict

**YELLOW — build with stated operating limits.**

The source recommends:

- max-effort 4WD NAG1 before full-power calibration,
- proactively built NV146,
- upgraded front/rear driveshafts,
- upgraded rear axles,
- refreshed stock-size front/rear differentials,
- rear Wavetrac,
- retained stock front CV architecture unless demonstrated failure requires custom parts,
- strict launch, temperature, and torque-management limits.

The source explicitly states that no public dataset proves long-term 850-WHP street mileage or repeat-pass survival for a WK1 retaining the stock-size 200/226-mm differentials and front CVs.

## Completed-build evidence used

- MMX `The Dumpster` — documented at more than 900 hp at all four wheels and described as a 9-second full-function daily driver; used a Paramount Super Pro NAG1, built transfer case, Derale transmission cooler, and Dana 60 rear. This supports the max-effort NAG1/built transfer-case direction but does **not** validate the stock 226-mm rear at that output.
- A reported 1,100-hp WK1 running 9.46 sec / 145 mph confirms vehicle-level performance but did not publish enough internal drivetrain specification to establish durability.
- Southern Hotrod NAG1 9-second evidence corroborates NAG1 performance precedent but not a full reliability bill of materials.

## Recommended NAG1 specification

Minimum written build specification:

- 300M input shaft,
- new output shaft,
- added K1/K2/K3/B2 clutch capacity,
- performance frictions/steels,
- HD F1/F2 sprags/freewheels,
- high-pressure tested/calibrated valve body,
- remanufactured/fully inspected pump,
- new conductor plate/seals/filter/connector,
- measured clutch clearances and air-check report,
- documented planetary inspection and replacement where condition is not perfect.

The source concludes that **Super-Pro hardware class is justified**, while the vendor label itself is not mandatory if another builder provides equivalent critical hardware and accountability.

## Converter / flexplate / cooling

- 9.5–10-inch multi-disc lockup converter, approximately **2,800 rpm stall**.
- ATI 915663 SFI 29.1 flexplate or verified equivalent interface.
- Large auxiliary stacked-plate transmission cooler, high-capacity pan, controlled thermal bypass, -6AN-class plumbing, and dedicated temperature logging.
- Project targets: 170–190°F hard-use range; begin derate around 195°F; no repeated pull/launch above ~200°F; mandatory cooldown by ~205°F. These are project limits, not OEM published limits.

## NV146 recommendation

Proactively build before enabling the 850-WHP file:

- HD chain/bearings,
- upgraded clutch pack/steels,
- rebuilt pump,
- seals/clearance service,
- correct BOT 89 M1 Plus-equivalent fluid.

A healthy stock NV146 is accepted only for low-boost shakedown, not as the final full-power configuration.

## Differential / axle / CV decisions

- Front 200-mm 3.73 differential: **REFRESH / KEEP** if within specification.
- Front CVs/hubs: **REFRESH / KEEP**; custom 300M only after demonstrated need.
- Rear 226-mm/Super 44 housing and 3.73 gearset: **REFRESH / KEEP**.
- Rear LSD: **UPGRADE NOW** to Wavetrac.
- Rear axle shafts: **UPGRADE NOW**.
- Front/rear driveshafts: **UPGRADE NOW**, but manufacture only from final measured installed geometry.

## Torque-management envelope

Initial commissioning strategy:

- first gear delivered-torque cap approximately **600–650 lb-ft**,
- second gear approximately **700–750 lb-ft**,
- full 850-WHP airflow allowed only after driveline multiplication falls, normally third gear upward,
- preserve torque reduction on every WOT upshift,
- no `zero torque management`,
- 1,800–2,200 rpm launch ceiling during validation,
- ~3–5 psi brake boost ceiling initially,
- drag radials acceptable; slicks, two-step, transbrake, and repeated prepared-surface back-to-back launches excluded.

## 2026 budget result

- Target drivetrain parts/build services/control/tuning: **$19,400–$23,000**.
- Installed/validated with outsourced labor: approximately **$23,400–$31,000**.
- Engine, primary fuel system, exhaust, main radiator/CAC hardware, brakes, tires, and Hellcat swap labor are outside that drivetrain total.

## Remaining weak points

1. Stock-size front 200-mm gearset/front CVs.
2. Stock 226-mm rear ring-and-pinion/housing.
3. Calibration/integration errors that remove shift torque reduction or allow thermal/slip excursions.

## Evidence boundary

The architecture has credible high-power precedent, but the 800–850 WHP reliability envelope is an engineering recommendation constrained by operating limits, not a statistically proven lifetime rating.
