## ADMM-PnP — denoiser comparison (which denoiser wins per structure)

### matirf

| structure | noise | denoiser | NMSE | PSNR | Depth Error (nm) | Stack Recovery | chi2_ratio |
|---|---|---|---|---|---|---|---|
| cell | 0 | **Gaussian** | 0.157 | 21.8 | 4 | 0.0152 | 8.3e-06 |
| cell | 0 | DCT | 0.314 | 18.8 | 15 | 0.0303 | 6.17e-07 |
| cell | 0 | TV Bregman | 0.838 | 14.6 | 67 | 0 | 0.022 |
| fibres | 0 | **DCT** | 0.23 | 30.4 | 52 | 0 | 0.00201 |
| fibres | 0 | Gaussian | 0.292 | 29.4 | 24 | 0.0259 | 3.22 |
| fibres | 0 | TV Bregman | 0.782 | 25.1 | 87 | 0 | 12.1 |
| vesicles | 0 | **Gaussian** | 0.311 | 31.2 | 15 | 0 | 1.66 |
| vesicles | 0 | DCT | 0.442 | 29.7 | 66 | 0 | 0.00219 |
| cell | 0.02 | **Gaussian** | 0.177 | 21.3 | 9 | 0 | 0.96 |
| cell | 0.02 | DCT | 0.363 | 18.2 | 25 | 0.106 | 0.61 |
| cell | 0.02 | TV Bregman | 0.848 | 14.5 | 70 | 0 | 58.4 |
| fibres | 0.02 | **DCT** | 0.568 | 26.5 | 75 | 0 | 0.424 |
| fibres | 0.02 | Gaussian | 0.73 | 25.4 | 61 | 0 | 1.99 |
| fibres | 0.02 | TV Bregman | 0.805 | 25.0 | 95 | 0 | 4.79 |
| vesicles | 0.02 | **DCT** | 0.603 | 28.3 | 85 | 0 | 0.4 |
| vesicles | 0.02 | Gaussian | 0.755 | 27.3 | 79 | 0 | 1.43 |
| vesicles | 0.02 | TV Bregman | 0.803 | 27.1 | 101 | 0 | 3.33 |
| cell | 0.05 | **Gaussian** | 0.307 | 18.9 | 21 | 0 | 0.903 |
| cell | 0.05 | DCT | 0.707 | 15.3 | 59 | 0.106 | 0.587 |
| cell | 0.05 | TV Bregman | 0.853 | 14.5 | 72 | 0 | 10.1 |
| fibres | 0.05 | **TV Bregman** | 0.862 | 24.7 | 105 | 0 | 1.18 |
| fibres | 0.05 | DCT | 0.883 | 24.6 | 95 | 0.00862 | 0.402 |
| fibres | 0.05 | Gaussian | 0.949 | 24.3 | 85 | 0 | 0.826 |
| vesicles | 0.05 | **TV Bregman** | 0.87 | 26.7 | 118 | 0 | 0.956 |
| vesicles | 0.05 | DCT | 0.9 | 26.6 | 109 | 0 | 0.382 |

