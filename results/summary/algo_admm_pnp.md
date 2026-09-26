## ADMM-PnP — standard vs optimal

### matirf

| use | dataset | noise | params | NMSE | PSNR | Depth Error (nm) | Stack Recovery | chi2_ratio |
|---|---|---|---|---|---|---|---|---|
| standard | cell | 0 | denoiser=Gaussian, sigma=25, rho=0.1 | 0.216 | 20.5 | 6 | 0.0303 | 4.46e-07 |
| optimal | cell | 0 | denoiser=Gaussian, sigma=50, rho=0.03 | 0.157 | 21.8 | 4 | 0.0152 | 8.3e-06 |
| standard | cell | 0.02 | denoiser=Gaussian, sigma=25, rho=0.1 | 0.236 | 20.1 | 11 | 0.0455 | 0.765 |
| optimal | cell | 0.02 | denoiser=Gaussian, sigma=50, rho=0.03 | 0.177 | 21.3 | 9 | 0 | 0.96 |
| standard | cell | 0.05 | denoiser=Gaussian, sigma=25, rho=0.1 | 0.411 | 17.7 | 30 | 0.0455 | 0.752 |
| optimal | cell | 0.05 | denoiser=Gaussian, sigma=50, rho=0.03 | 0.307 | 18.9 | 21 | 0 | 0.903 |
| standard / optimal | fibres | 0 | denoiser=Gaussian, sigma=25, rho=0.1 | 0.136 | 32.7 | 22 | 0.0259 | 0.118 |
| standard / optimal | fibres | 0.02 | denoiser=Gaussian, sigma=25, rho=0.1 | 0.509 | 27.0 | 56 | 0 | 0.648 |
| standard / optimal | fibres | 0.05 | denoiser=Gaussian, sigma=25, rho=0.1 | 0.845 | 24.8 | 85 | 0 | 0.532 |
| standard / optimal | vesicles | 0 | denoiser=Gaussian, sigma=25, rho=0.1 | 0.193 | 33.3 | 12 | 0 | 0.0265 |
| standard / optimal | vesicles | 0.02 | denoiser=Gaussian, sigma=25, rho=0.1 | 0.546 | 28.7 | 68 | 0 | 0.559 |
| optimal | vesicles | 0.05 | denoiser=TV Bregman, sigma=40, rho=4 | 0.87 | 26.7 | 118 | 0 | 0.956 |

