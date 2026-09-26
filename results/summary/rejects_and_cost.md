## Rejections, failures and cost

| solver | runs | rejected | failed/timeout | median s | max mem (MB) | top findings |
|---|---|---|---|---|---|---|
| ADAM | 45 | 4 (8%) | 0 | 17.2 | 2176 | no-better×72, depth-shift×18, collapsed×4 |
| ADMM | 19 | 1 (5%) | 0 | 1.7 | 2204 | no-better×20, depth-shift×10, collapsed×1 |
| ADMM-PnP | 37 | 3 (8%) | 1 | 14.7 | 10210 | no-better×61, depth-shift×18, collapsed×2 |
| MCMC | 39 | 0 (0%) | 0 | 9.7 | 2236 | no-better×47, depth-shift×17 |
| PNP | 37 | 0 (0%) | 0 | 3.7 | 3591 | no-better×40, depth-shift×18 |
| PPXA | 2 | 0 (0%) | 0 | 291.7 | 1656 | no-better×3, depth-shift×1 |
