# Evidence Matrix

This matrix traces each major project claim to its controlling source, confidence, and unresolved question. Confidence applies to the **claim as written**, not to the entire source.

| ID | Claim | Source | Confidence | Unresolved question / closure condition |
|---|---|---|---|---|
| E01 | Route A preserves more native WK1 driveline geometry than Route B. | `sources/WK1_Free_Only_Feasibility_Sprint.md` | High | Confirm actual stock crank/bellhousing/NV146 output coordinates on the vehicle before teardown. |
| E02 | WK1 baseline uses 3.73 final drive with 200-mm front and 226-mm rear differential families. | Free-Only Feasibility Sprint; factory/Dana references summarized there | High | Verify actual axle tags/BOMs and condition on the project vehicle. |
| E03 | Existing public WK1 GLB mechanical nodes are not fabrication-grade and must be quarantined. | `sources/WK1_Digital_Build_Asset_Map.md` | High | None for disposition; any replacement geometry must be separately verified. |
| E04 | 8HP95 Trackhawk longitudinal/output references are useful sanity checks but do not establish MP3015C installed geometry. | Free-Only Feasibility Sprint; Asset Map | High | Directly measure the actual donor assembly if Route B is reopened. |
| E05 | Route B is mechanically feasible but requires a complete donor measurement/bench-validation workflow before fabrication release. | `sources/WK1_Route_B_Build_Book.md` | High | Close G00–G05 on actual hardware. |
| E06 | 2008 WK and Trackhawk CAN compatibility must not be assumed. | Route B Build Book | High | Bench-validate PCM/TCM/DTCM/security/chassis-state message dependencies with donor-specific wiring. |
| E07 | Sound German is a credible transmission-integration lead, but public evidence does not by itself prove complete MP3015C/DTCM + WK1 ABS/traction integration. | Historical Trackhawk feasibility research + later Build Book correction | Medium-High | Obtain direct vendor confirmation or bench proof for the exact 6.2/8HP95/MP3015C/WK1 combination. |
| E08 | A native-style Hellcat-to-WK1 integration can retain stock 6.1 mounts and WK1 ECU/harness strategy with crank-trigger/VVT changes in at least one observed build. | `docs/OBSERVED_BUILD_EVIDENCE.md` | Medium | Power, NV146 configuration, mileage, launch duty, and long-term durability of that build remain unknown. |
| E09 | 850-WHP Route A should use a max-effort NAG1 hardware class rather than relying on a stage label. | `sources/WK1_850_WHP_Reliability_Build_Investigation.md` | Medium-High engineering recommendation | Vendor must provide written BOM, clearances, planetary inspection, and calibration compatibility. |
| E10 | A built NV146 should be installed before enabling full 850-WHP calibration. | 850-WHP Reliability Investigation | Medium-High engineering recommendation | Long-term public survival data at exactly this duty cycle remain sparse; validate temperature/fluid after shakedown. |
| E11 | Front/rear driveshafts and rear axle shafts should be upgraded before full-power commissioning. | 850-WHP Reliability Investigation | Medium-High | Final shaft dimensions, joint choice, critical-speed margin, and balance must come from installed measured geometry and vendor review. |
| E12 | Stock-size front 200-mm differential/CV architecture can be retained initially after inspection. | 850-WHP Reliability Investigation | Medium | No public dataset proves unlimited 850-WHP launch durability; upgrade only after evidence of need/failure. |
| E13 | Stock 226-mm rear housing/3.73 gearset can be retained with professional refresh while upgrading the LSD and axles. | 850-WHP Reliability Investigation | Medium | Ring-and-pinion/housing remain a likely weak point; inspect setup and monitor under progressive-load testing. |
| E14 | Reliability at 850 WHP depends strongly on managed low-gear torque, preserved WOT shift torque reduction, heat control, and launch limits. | 850-WHP Reliability Investigation; MMX/vendor evidence summarized there | Medium-High | Final torque caps must be validated by logs with the chosen tuner/controller/transmission builder. |
| E15 | The defensible current verdict is YELLOW: 800–850 WHP is supportable for street pulls and occasional controlled drag-radial launches, not repeated slick/two-step abuse. | 850-WHP Reliability Investigation | Medium-High synthesis | Accumulate real project mileage, temperatures, fluid inspections, launches, and failure-free service history before promoting to GREEN. |
| E16 | Target drivetrain budget is roughly $19.4k–$23k before installation, with ~$23.4k–$31k installed/validated if outsourced. | 850-WHP Reliability Investigation | Medium | Requote all major vendors in current market; shipping/core/tax and local labor can materially move totals. |
| E17 | Final fabrication dimensions must come from direct measurement, not forum numbers or proxy models. | Asset Map; Free-Only Sprint; Route B Build Book | High | Close every MEASURE gate before part release. |

## Confidence interpretation

- **High** — directly supported by factory/OEM data, explicit source-quality audit, or a process rule that does not depend on unverified performance assumptions.
- **Medium-High** — convergent completed-build/builder evidence plus engineering synthesis, but without enough long-term public data to call statistically proven durability.
- **Medium** — credible observed configuration or engineering recommendation with meaningful unanswered duty-cycle/condition questions.
- **Low** — proxy/unverified. No current locked project claim should depend on low-confidence evidence.

## Promotion rule

A claim moves upward in confidence only when new evidence directly closes its unresolved question. Marketing horsepower ratings, isolated dyno pulls, or visually successful fitment do not automatically promote durability or fabrication confidence.
