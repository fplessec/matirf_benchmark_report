## Effective parameter ranges — matirf (the atlas)

The setting that minimised NMSE at each noise level; compare to the predicted ranges in `docs/algorithms/`.

### ADAM

| noise | best params | NMSE | depth err (nm) |
|---|---|---|---|
| 0 | reg=none, lambda=0 | 0.635 | 68 |
| 0.02 | reg=tv, lambda=0.05 | 0.561 | 40 |
| 0.05 | reg=tv, lambda=0.05 | 0.668 | 58 |

### ADMM

| noise | best params | NMSE | depth err (nm) |
|---|---|---|---|
| 0 | kappa=0.1, mu=0.5 | 0.0409 | 4 |
| 0.02 | kappa=0.3, mu=1 | 0.608 | 28 |
| 0.05 | kappa=0.3, mu=1 | 0.911 | 60 |

### ADMM-PnP

| noise | best params | NMSE | depth err (nm) |
|---|---|---|---|
| 0 | denoiser=Bilateral, sigma=25, rho=0.1 | 0.0524 | 4 |
| 0.02 | denoiser=Gaussian, sigma=25, rho=0.1 | 0.174 | 13 |
| 0.05 | denoiser=Gaussian, sigma=50, rho=0.1 | 0.367 | 26 |

### MCMC

| noise | best params | NMSE | depth err (nm) |
|---|---|---|---|
| 0 | denoiser=TV Bregman, sigma=0.01 | 0.406 | 19 |
| 0.02 | denoiser=TV Bregman, sigma=0.01 | 0.432 | 21 |
| 0.05 | denoiser=TV Bregman, sigma=0.01 | 0.588 | 38 |

### PNP

| noise | best params | NMSE | depth err (nm) |
|---|---|---|---|
| 0 | denoiser=Gaussian, sigma=50 | 0.462 | 27 |
| 0.02 | denoiser=None | 0.887 | 81 |
| 0.05 | denoiser=None | 0.936 | 83 |

### PPXA

| noise | best params | NMSE | depth err (nm) |
|---|---|---|---|
| 0.02 | reg=tv, lambda=0.1 | 0.619 | 40 |

