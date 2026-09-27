## ADMM — standard vs optimal

### matirf

| dataset | noise | params | NMSE | PSNR | Depth Error (nm) | Stack Recovery | chi2_ratio |
|---|---|---|---|---|---|---|---|
| cell | 0 | kappa=0.1, mu=0.5 | 0.0318 | 28.8 | 4 | 0.636 | 5.2e-08 |
| fibres | 0 | kappa=0.1, mu=0.5 | 0.251 | 30.1 | 15 | 0.336 | 0.000278 |
| fibres | 0 | kappa=0.01, mu=0.5 | 0.0406 | 38.0 | 10 | 0.966 | 4.86e-06 |
| vesicles | 0 | kappa=0.1, mu=0.5 | 0.142 | 34.6 | 8 | 0 | 0.00024 |
| vesicles | 0 | kappa=0.01, mu=0.5 | 0.021 | 42.9 | 8 | 1 | 5.3e-06 |
| cell | 0.02 | kappa=0.1, mu=0.5 | 0.619 | 15.9 | 41 | 0.152 | 0.604 |
| fibres | 0.02 | kappa=0.1, mu=0.5 | 0.882 | 24.6 | 64 | 0.0517 | 0.436 |
| vesicles | 0.02 | kappa=0.1, mu=0.5 | 0.848 | 26.8 | 66 | 0 | 0.413 |
| cell | 0.05 | kappa=0.1, mu=0.5 | 0.899 | 14.3 | 68 | 0.0758 | 0.589 |
| fibres | 0.05 | kappa=0.1, mu=0.5 | 0.973 | 24.2 | 95 | 0.0172 | 0.411 |
| vesicles | 0.05 | kappa=0.1, mu=0.5 | 0.974 | 26.2 | 94 | 0 | 0.39 |
| esoubies | native | kappa=0.1, mu=0.5 | — | — | — | — | 19.2 |

