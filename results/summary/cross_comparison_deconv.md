## Cross-comparison — deconv: which solver wins, and where

| dataset | noise | best (by NMSE) | params | NMSE | PSNR | SSIM | chi2_ratio |
|---|---|---|---|---|---|---|---|
| img_001 | 0 | **ADAM** | reg=none, lambda=0 | 0.0205 | 24.1 | 0.675 | 7.8e-07 |
| img_001 | 0.02 | **ADAM** | reg=tv, lambda=0.05 | 0.0238 | 23.5 | 0.614 | 0.959 |
| img_001 | 0.05 | **MCMC** | denoiser=TV Bregman, sigma=0.02 | 0.0271 | 22.9 | 0.527 | 0.926 |
