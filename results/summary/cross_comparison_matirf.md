## Cross-comparison — matirf: which solver wins, and where

| dataset | noise | best (by NMSE) | params | NMSE | PSNR | Depth Error (nm) | Stack Recovery | chi2_ratio |
|---|---|---|---|---|---|---|---|---|
| cell_fibres_vesicles | 0 | **ADMM** | kappa=0.1, mu=0.5 | 0.0409 | 31.5 | 4 | 0.498 | 5.48e-08 |
| cell_fibres_vesicles | 0.02 | **ADMM-PnP** | denoiser=Gaussian, sigma=25, rho=0.1 | 0.174 | 25.2 | 13 | 0.0651 | 0.872 |
| cell_fibres_vesicles | 0.05 | **ADMM-PnP** | denoiser=Gaussian, sigma=50, rho=0.1 | 0.367 | 22.0 | 26 | 0.0093 | 0.808 |
