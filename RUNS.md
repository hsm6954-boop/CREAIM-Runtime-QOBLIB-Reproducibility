# Run record

## Maximum Independent Set — PR #84

Solver build: `CREAIM-RUNTIME-MIS-20261002`  
Build SHA-256: `85bd754b14aa1679df290d2b5c68658ddfe225d1cb5209d85247c76bf027b76a`

Outer-run protocol:
- algorithm type: stochastic
- paradigm: classical
- runs per instance: 10
- seed base: `28123`
- seed stride: `100003`
- outer seeds: `28123, 128126, 228129, 328132, 428135, 528138, 628141, 728144, 828147, 928150`
- `OMP_NUM_THREADS=4`
- search does not read QOBLIB target objective values or reference solutions.

Results:

| Instance | Best | Feasible | At best | Mean wall time |
| --- | ---: | ---: | ---: | ---: |
| C125-9 | 34 | 10/10 | 10/10 | 0.067599 s |
| p_hat1500-3 | 94 | 10/10 | 9/10 | 0.977763 s |
| hamming10-4 | 40 | 10/10 | 10/10 | 0.787105 s |

Environment: Base44 sandbox; 4 vCPU x86_64; virtualized AuthenticAMD; Linux/gVisor; GCC 12.2.0; no GPU; no QPU.

## LABS — PR #85

Solver build: `CREAIM-RUNTIME-LABS-20261002`  
Build SHA-256: `f1a931f89d6abb64721d4fc4edf21500cd4cbcd0f5391c46977eb6dd2a897a19`

Outer-run protocol:
- algorithm type: stochastic
- paradigm: classical
- runs per instance: 5
- outer seeds: `28123, 128126, 228129, 328132, 428135`
- `OMP_NUM_THREADS=4`
- exact full-sequence LABS energy is independently recomputed before output.
- search does not read QOBLIB target energies or reference sequences.

Results:

| Instance | Best energy | Feasible | At best | Mean wall time |
| --- | ---: | ---: | ---: | ---: |
| labs067 | 241 | 5/5 | 5/5 | 19.010000 s |
| labs099 | 577 | 5/5 | 5/5 | 59.506000 s |

Environment: Base44 sandbox; 4 vCPU x86_64; virtualized AuthenticAMD; Linux/gVisor; GCC 12.2.0; no GPU; no QPU.

The internal solver mechanics and proprietary search implementation are outside the public disclosure scope.
