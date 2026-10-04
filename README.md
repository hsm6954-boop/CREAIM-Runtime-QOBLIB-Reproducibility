# CREAIM Runtime — QOBLIB reproducibility reference

This public repository is the stable solver/run reference for CREAIM Runtime submissions to **ZIB-AOPT/QOBLIB**.

It identifies the exact solver builds used for the submitted runs, records the externally relevant run protocol and execution environment, preserves submitted solution artifacts and checksums, and records QOBLIB validation provenance.

## Submissions

| QOBLIB class | PR | Instances | Paradigm | Solver build |
| --- | --- | --- | --- | --- |
| Maximum Independent Set (`07-independentset`) | `ZIB-AOPT/QOBLIB#84` | `C125-9`, `p_hat1500-3`, `hamming10-4` | Classical / stochastic | `CREAIM-RUNTIME-MIS-20261002` |
| LABS (`02-labs`) | `ZIB-AOPT/QOBLIB#85` | `labs067`, `labs099` | Classical / stochastic | `CREAIM-RUNTIME-LABS-20261002` |

## Solver identifiers

- MIS build SHA-256: `85bd754b14aa1679df290d2b5c68658ddfe225d1cb5209d85247c76bf027b76a`
- LABS build SHA-256: `f1a931f89d6abb64721d4fc4edf21500cd4cbcd0f5391c46977eb6dd2a897a19`

## What this repository publishes

- stable solver/build identifiers and build digests;
- submitted instance names and objective values;
- outer-run counts and fixed outer seeds;
- execution environment and observed runtimes;
- exact submitted solution files and solution SHA-256 digests;
- frozen QOBLIB validation provenance and checker outcomes;
- explicit claim boundaries.

See `RUNS.md`, `VALIDATION.md`, and `solutions/`.

## IP boundary

The solver implementations are proprietary CREAIM Runtime components. This public benchmark artifact does **not** redistribute internal source code, orchestration logic, unpublished architecture, patent-sensitive implementation details, or proprietary Runtime Computing mechanisms.

For QOBLIB reference purposes, the solver is identified by the immutable build identifier, SHA-256 digest, externally relevant run protocol, submitted outputs, and independent QOBLIB checker evidence recorded here. No claim of open-source or source-level reproducibility is made.

If maintainers require additional non-public verification material, CREAIM can discuss an appropriately scoped review channel separately.

## Claim boundary

These are classical benchmark submissions. No physical-QPU execution, quantum advantage, quantum speedup, universal solver superiority, new-public-best claim, or independent proof of optimality is asserted. QOBLIB ledger labels such as `optimal` and `best known` remain QOBLIB classifications.

## Links

- QOBLIB PR #84: https://github.com/ZIB-AOPT/QOBLIB/pull/84
- QOBLIB PR #85: https://github.com/ZIB-AOPT/QOBLIB/pull/85
- CREAIM Runtime: https://runtime.creaim.ai/


## About CREAIM

CREAIM Inc. is a South Korean AI technology company conducting research and development in Runtime Computing™, execution validation, optimization, and AI systems.

- **Company:** CREAIM Inc.
- **Corporate:** https://creaim.inc
- **Technology & Research:** https://runtime.creaim.ai
- **Contact:** contact@creaim.ai

### Research & Collaboration

CREAIM welcomes research collaboration, benchmarking, technical validation, and industry partnerships related to Runtime Computing™, optimization, AI systems, and execution validation.

For research or collaboration inquiries: contact@creaim.ai
