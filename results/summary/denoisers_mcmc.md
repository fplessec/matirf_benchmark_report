## MCMC — denoiser comparison (which denoiser wins per structure)

### matirf

| structure | noise | denoiser | NMSE | PSNR | Depth Error (nm) | Stack Recovery | chi2_ratio |
|---|---|---|---|---|---|---|---|
| cell | 0 | **Gaussian** | 0.227 | 20.2 | 11 | 1 | 1.35e-05 |
| cell | 0 | TV Bregman | 0.238 | 20.0 | 10 | 0.697 | 1.21e-05 |
| cell | 0 | DCT | 0.302 | 19.0 | 14 | 0.0152 | 2.32e-05 |
| fibres | 0 | **Gaussian** | 0.115 | 33.4 | 23 | 0.991 | 0.121 |
| fibres | 0 | TV Bregman | 0.213 | 30.8 | 33 | 0.905 | 0.44 |
| fibres | 0 | DCT | 0.282 | 29.5 | 57 | 0 | 0.441 |
| vesicles | 0 | **Gaussian** | 0.166 | 33.9 | 19 | 1 | 0.0914 |
| vesicles | 0 | TV Bregman | 0.305 | 31.3 | 23 | 0.5 | 0.23 |
| vesicles | 0 | DCT | 0.45 | 29.6 | 62 | 0 | 0.214 |
| cell | 0.02 | **TV Bregman** | 0.235 | 20.1 | 13 | 0.742 | 0.894 |
| cell | 0.02 | DCT | 0.317 | 18.8 | 17 | 0.0455 | 0.925 |
| cell | 0.02 | Gaussian | 0.402 | 17.7 | 28 | 0.788 | 1.2 |
| fibres | 0.02 | **DCT** | 0.511 | 27.0 | 81 | 0 | 0.897 |
| fibres | 0.02 | TV Bregman | 0.589 | 26.3 | 67 | 0.612 | 0.954 |
| fibres | 0.02 | Gaussian | 0.791 | 25.1 | 61 | 0.534 | 0.986 |
| vesicles | 0.02 | **DCT** | 0.588 | 28.4 | 87 | 0 | 0.736 |
| vesicles | 0.02 | TV Bregman | 0.633 | 28.1 | 78 | 0.5 | 0.822 |
| vesicles | 0.02 | Gaussian | 0.797 | 27.1 | 74 | 0.5 | 0.922 |
| cell | 0.05 | **TV Bregman** | 0.453 | 17.2 | 31 | 0.561 | 0.822 |
| cell | 0.05 | DCT | 0.641 | 15.7 | 57 | 0.0455 | 0.875 |
| cell | 0.05 | Gaussian | 0.764 | 15.0 | 53 | 0.424 | 1.07 |
| fibres | 0.05 | **DCT** | 0.856 | 24.7 | 105 | 0.00862 | 0.595 |
| fibres | 0.05 | TV Bregman | 0.887 | 24.6 | 95 | 0.336 | 0.6 |
| fibres | 0.05 | Gaussian | 0.953 | 24.3 | 84 | 0.25 | 0.632 |
| vesicles | 0.05 | **DCT** | 0.889 | 26.6 | 115 | 0 | 0.539 |
| vesicles | 0.05 | TV Bregman | 0.908 | 26.5 | 111 | 0 | 0.546 |
| vesicles | 0.05 | Gaussian | 0.967 | 26.3 | 97 | 0 | 0.584 |

### deconv

| structure | noise | denoiser | NMSE | PSNR | SSIM | chi2_ratio |
|---|---|---|---|---|---|---|
| img_001 | 0.02 | **TV Bregman** | 0.0245 | 23.4 | 0.596 | 0.98 |
| img_001 | 0.02 | Gaussian | 0.0415 | 21.0 | 0.372 | 0.948 |

