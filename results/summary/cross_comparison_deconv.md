## Cross-comparison — deconv: which solver wins, and where

| dataset | noise | best (by NMSE) | params | NMSE | PSNR | SSIM | chi2_ratio |
|---|---|---|---|---|---|---|---|
| img_001 | 0 | **ADAM** | reg=none, lambda=0 | 0.0191 | 24.4 | 0.694 | 1.96e-07 |
| img_001 | 0.02 | **MCMC** | denoiser=TV Bregman, sigma=0.03 | 0.0245 | 23.4 | 0.596 | 0.98 |
| img_001 | 0.05 | **ADAM** | reg=tikhonov, lambda=0.1 | 0.0371 | 21.5 | 0.511 | 1.09 |
