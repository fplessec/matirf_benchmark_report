## Rejections, failures and cost

| solver | runs | rejected | failed/timeout | median s | max mem (MB) | top findings |
|---|---|---|---|---|---|---|
| ADAM | 63 | 10 (15%) | 4 | 25.1 | 2191 | no-better×66, depth-shift×16, collapsed×10 |
| ADMM | 24 | 0 (0%) | 0 | 1.8 | 2220 | no-better×20, depth-shift×10 |
| ADMM-PnP | 36 | 0 (0%) | 2 | 40.5 | 8414 | depth-shift×9, no-better×7 |
| MCMC | 28 | 0 (0%) | 0 | 26.4 | 2177 | no-better×11, depth-shift×10 |
| PNP | 20 | 0 (0%) | 1 | 10.3 | 9030 | no-better×28, depth-shift×14 |
| PPXA | 2 | 0 (0%) | 0 | 543.2 | 2170 | no-better×2, depth-shift×1 |
