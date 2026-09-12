# Source Record — WK1 Digital Build Asset Map

**Original source:** `WK1_Digital_Build_Asset_Map.pdf`  
**Research freeze:** 2026-09-07  
**Role:** source-quality map and digital-geometry boundary record.

## What this source establishes

- The free public record is sufficient to establish the WK body datum system and build a preliminary packaging scene, but it is **not sufficient** to release mounts, crossmembers, driveshafts, tunnel modifications, or axle parts for fabrication.
- The existing downloadable WK1 GLB is not trustworthy mechanical geometry. Its mechanical hierarchy contains BeamNG donor identifiers such as `pickup_transfer_case`, `gavril_v8_roamer_transmission`, `pickup_subframe_IFS`, `pickup_diff_F`, `pickup_halfshaft`, `pickup_frame`, and `etk800`.
- The GLB body shell may be retained as a low-confidence visual envelope only; drivetrain, suspension, differential, shaft, and cradle geometry from that model is quarantined.
- A 370-page WK factory collision/body manual is the authoritative free datum foundation.
- Dana/Spicer references support the 2008 WK SRT8 rear axle family as Super 44 / 226 mm.
- Holley Gen III HEMI mount documentation identifies useful block-side mounting interfaces across 5.7/6.1/6.2/6.4 applications, but it is not a full package model.
- Advance Adapters documentation supports the Trackhawk/TRX 8HP95 output family as 43-spline and supplies adapter-specific dimensions. Those dimensions do **not** establish the stock Trackhawk transfer-case envelope.
- No free fabrication-grade scan was found for the WK1 engine bay/tunnel/cradles, dressed 6.2, exact 8HP95, Trackhawk transfer case, or completed WK1 8HP95 installed geometry.

## Confidence model captured by the source

- **A:** OEM dimension, traceable metrology, or verified exact scan.
- **B:** plausible exact-family scan or documented vendor interface.
- **C:** proxy, photogrammetry, game mesh, or undocumented community model.
- **D:** unverified claim/appearance model.

## Engineering rule inherited into this repository

A correct part number, spline count, or family name does not establish a mounting surface. Geometry that can drive fabrication must come from OEM dimensioned data, traceable scan/CMM data, or direct measurement of the actual component revision.

## Source boundaries

This source is an **engineering research map**, not a fabrication release. Its highest-value function is to prevent false precision and to separate usable datum evidence from proxy geometry.

## Unresolved questions left by this source

1. Exact installed WK1 engine-bay/front-cradle/tunnel hard-point coordinates.
2. Dressed 6.2 outer envelope and accessory/service envelope.
3. Exact MP3015C exterior/output geometry.
4. Final installed shaft lengths and working angles.
5. Actual fitment of any proposed engine/transmission placement after motion, heat, and service clearances are applied.
