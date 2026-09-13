# Grid-first loading vaccine — record and bench hand-off

Generation: 202609132340 UTC.
Status: vaccine published and tested; product repair OUTSTANDING.
Authority: the architect requested a CVAA vaccine and a control-pad README entry. This is an agent outbox note, not an executable inbox order. No promotion is authorised.

## Read the executable rule

CVAA commit: `c7c9ba8f6ceef9efbb09fc4b674a30387a297287`.

- [Vaccine: grid-first-critical-path](https://github.com/Ventusltd/cvaa/blob/c7c9ba8f6ceef9efbb09fc4b674a30387a297287/vaccines/202609132340-grid-first-critical-path.md)
- [Focused tests](https://github.com/Ventusltd/cvaa/blob/c7c9ba8f6ceef9efbb09fc4b674a30387a297287/tools/grid-first-critical-path.test.mjs)
- [Preserved failing observations and source digests](https://github.com/Ventusltd/cvaa/blob/c7c9ba8f6ceef9efbb09fc4b674a30387a297287/studies/202609132340-grid-first-observed.json)
- [Registry preparation and proof run](https://github.com/Ventusltd/cvaa/actions/runs/34790782923)

Forty focused checks passed, including healthy synthetic controls, mutation failures and the preserved real dependency-delay observations. The existing `tools/selftest.mjs` suite and `node inoculate.mjs . --no-write` also passed before the tested candidate was moved to CVAA main. Synthetic healthy fixtures are NOT a working GridAtlas release or production acceptance evidence.

The registry had already been blocked by `vaccines/20260907-runner-vaccines.md`: it was an eight-digit-named prose study without the executable vaccine format or a lock entry. It was moved byte-for-byte to `studies/20260907-runner-vaccines.md` (unchanged blob `a89fa5ba5e7333b3b52d9872942f8310358a2856`). None of its five proposed lessons was deleted or falsely claimed implemented. The lock was regenerated; existing antibodies and the runner were not relaxed. Only two integration lines were added to the existing self-test. No additional active workflow remains.

## The diagnosed canary

https://ventusltd.github.io/gridatlas/atlas/?repd_ref=12588&technology=solar&latitude=51.8132088&longitude=-1.3489728&zoom=12

Tested composition: `202609080850`, immutable shell `202608300453-atlas-v9`.

The controlled Chrome study held one named resource for 20 seconds without substituting response bodies. At the early approximately eight-second observation:

| Case | Observation |
| --- | --- |
| Control | Five source links, rendered features and an answered onshore engine |
| Identity runtime held | Five links already rendered while identity was pending |
| `neso-connection-sites.lean.json` held | 5,800 substations available, zero links, no answered arrival |
| `grid_substations.geojson` held | Essential geometry absent, zero links; recovered after release |

At approximately 28 seconds the delayed cases had five links. Source inspection places `await resolveNesoConnection(...)` before `drawLinks(...)` in the onshore path. This demonstrates the tested optional-data gate, not the exact cause of every historical iPhone delay or all GG-001 incidents. The lean declared-site register is NOT the separate large connection-points product.

The old trace did not record dedicated DOM `status_visible` and `pending_dependency` fields. The new vaccine therefore preserves one PRODUCT finding for the NESO gate and one INCOMPLETE finding for the missing geometry-wait measurements. Do not turn missing measurements into either a pass or an invented product observation.

Original studies: [ordinary cold/warm/throttled loads](https://github.com/Ventusltd/gridatlas/actions/runs/34768606689), [controlled dependency holds](https://github.com/Ventusltd/gridatlas/actions/runs/34769001064). Archive/artifact IDs and SHA-256 values are retained in the CVAA observation file. Retain raw traces while Actions artifacts remain available.

## Next scoped bench work, after authorisation

Keep this to the existing onshore startup path. Draw the nearest-mapped-substation result once the supplied coordinates and genuine geometry are usable; enrich the card asynchronously. Retain selection epochs so late responses cannot overwrite a newer project. Preserve offshore declared-connection behaviour, all source integrity checks, GRID/SUBS controls, existing styling and branding. Essential geometry is not optional: expose its waiting/failure state and permit recovery instead of inventing an answer.

Use the same four cold controlled cases and capture real rendered features, source counts, arrival state, held URLs/times, DOM waiting-state visibility, browser/runtime errors, composition hashes and provenance. Export the bounded observation contract as `.cvaa/contracts/grid-first-critical-path.json` beside the candidate's `atlas/current.json` and actual cartridge bytes; the vaccine checks them through the existing data-only CVAA context. Do not fill this contract from the synthetic unit fixture. A missing or stale contract must remain INCOMPLETE.

Re-measure cold, warm and throttled timing separately. The sub-five-second objective is a proposed performance target, not a demonstrated guarantee on every phone. Headless touch emulation is not physical iPhone Safari.

A CVAA registry commit does not update repositories already pinned to an older SHA. Updating the consumer pin, wiring this receipt producer, running the physical MSI bench and promoting a product fix are separate actions requiring the appropriate scope and evidence. None was done by this record. The main GridAtlas composition, homepage, control-pad `STATE.md`, inbox and existing machine results were left unchanged.
