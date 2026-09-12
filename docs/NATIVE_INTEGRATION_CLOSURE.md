# WK1 Hellcat Native-Architecture Integration Closure

## Verdict

**YELLOW-GREEN — proceed with native WK1 controls as the baseline integration strategy.**

Recommended minimum-change architecture:

**Hellcat/Redeye 6.2 + supercharger → stock WK1 6.1 mounting position → early 32-tooth crank signal conversion → mechanically locked VVT → retained 2008 WK1 PCM/harness/pedal/body network/TCM → tuner-validated 3-bar pressure/temperature sensing → external supercharger-bypass control → high-capacity return fuel system → built NAG1 with torque management preserved → built NV146 → native WK1 ABS/ESP/cluster/AWD retained.**

This supersedes the earlier implicit assumption that aftermarket engine mounts or a standalone engine-management system are required.

## Strong / closed conclusions

- Completed WK1 Hellcat swaps establish that a 6.2 can physically operate in a WK1 while retaining the native driveline architecture.
- Direct JHGarage owner evidence reports stock 6.1 mounts, stock WK1 harness/ECU, Hellcat MAP sensor, VVT lockout, and a 6.1-style crank tone-ring conversion.
- Early 5.7/6.1 Gen III HEMIs used a 32-tooth crank shutter wheel; later engines use a different crank-trigger strategy. The crank sensor must match the target wheel.
- VVT lockout is technically coherent with an early non-VVT WK1 PCM strategy, but exact fixed cam phase still requires validation.
- Retaining the native WK1 PCM/TCM/network is the highest-leverage path for preserving gauges, diagnostics, ABS/ESP, cruise, AWD behavior, and NAG1 torque coordination.
- WOT shift torque management should be preserved; it is treated as a drivetrain-protection requirement.
- Built NAG1 and built NV146 remain part of the 800–850 WHP durability specification.

## Critical unresolved gates

### P0 — must close before full-power release

1. **CKP/CMP synchronization**
   - Verify exact 32T wheel and matching crank sensor.
   - Confirm cam target/sensor compatibility after VVT lockout.
   - Scope or scan during cranking and prove stable sync before enabling fuel.

2. **Knock-sensor compatibility and calibration**
   - Verify sensor identity, mounting, signal quality, sensitivity, and actual commanded spark response under controlled dyno testing.
   - No 850-WHP calibration release until this is demonstrated.

3. **NAG1 torque-management behavior**
   - Log WOT shifts and verify native engine torque reduction remains active and sufficient.

4. **Fuel-pressure and MAP scaling**
   - Confirm KOEO/barometric scaling, boost-range accuracy, differential fuel pressure, injector characterization, and stable pressure at peak demand.

### P1 — close before architecture is promoted to GREEN

- Hellcat throttle-body compatibility with the 2008 PCM DBW strategy.
- Alternator field-control/charging compatibility.
- A/C compressor/plumbing/control behavior.
- Factory cruise-control operation.
- ABS/ESP intervention without communication faults.
- OBD-II diagnostics, readiness, misfire monitoring, and cluster behavior.
- CAC pump/failsafe and IAT2 repeat-pull thermal behavior.

### P2 — physical fitment / mock-up gates

- Oil pan vs front differential / cradle clearance.
- Oil pickup / windage-tray compatibility.
- Engine-to-hood and supercharger-lid clearance.
- Supercharger snout / radiator / fan clearance.
- Steering/intermediate-shaft vs exhaust clearance.
- Intake path and throttle-body packaging.
- CAC heat-exchanger / pump / reservoir packaging.
- A/C hose geometry.
- Power-steering bracket / belt-drive layout.

## Procurement constraints

Do **not** buy the following until mock-up or bench validation closes the relevant gate:

- standalone Hellcat controller package
- custom engine mounts
- final oil pan / pickup
- headers
- custom A/C hoses
- final cold-air / inlet plumbing
- CAC heat-exchanger brackets
- bespoke power-steering brackets

Start with the stock 6.1 mount architecture and retained WK1 PCM/harness unless a measured or logged failure proves a change is necessary.

## Controls boundary

Keep the native WK1 network responsible for:

- accelerator pedal / DBW authority
- engine control
- transmission coordination
- ABS / ESP interaction
- factory cluster
- OBD-II diagnostics
- cruise control
- body-network integration

Use auxiliary systems only where the 2008 WK1 did not originally have the hardware:

- supercharger bypass / boost control
- high-current fuel-pump power
- CAC pump / heat-exchanger circuit

## Power-release sequence

Commission progressively:

1. first fire / minimum boost
2. 500–600 WHP validation
3. 650–700 WHP validation
4. 750 WHP validation
5. 800 WHP validation
6. 850 WHP final calibration

Advance only if fuel pressure, MAP scaling, knock behavior, IAT2, coolant temperature, transmission temperature, WOT shift torque reduction, and network health are acceptable.

## Current architecture chain

**Hellcat/Redeye 6.2 → stock 6.1 WK1 mounts / engine position → 32T early crank conversion + matching sensor → VVT locked at validated fixed phase → 2008 WK1 PCM/harness/pedal/TCM retained → validated boosted sensing + fueling → external bypass control + dedicated CAC/fuel power → built NAG1 → built NV146 → native WK1 ABS/ESP/cluster/body network retained.**

## Promotion criteria

Promote native integration from **YELLOW-GREEN** to **GREEN** only after:

- CKP/CMP synchronization is bench-proven,
- knock sensing is validated under boost,
- DBW and charging are verified,
- factory function acceptance passes,
- WOT torque management is logged and confirmed,
- staged 800–850-WHP thermal testing passes.

The overall 850-WHP drivetrain should still retain the project's controlled-launch operating limits even if the integration architecture is promoted to GREEN.
