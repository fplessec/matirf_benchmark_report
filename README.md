# MA-TIRF reconstruction benchmark — report (LaTeX)

The PDF benchmark report for `matirf_python_plus`: a comparison of six reconstruction
algorithms (Adam, PPXA, ADMM, PnP, ADMM-PnP, MCMC) on the MA-TIRF 3D and 2D deconvolution
inverse problems. Register: technical hand-over (successor + team). The results section is the
*atlas* — there is no separate atlas deliverable, the report holds it.

## Build

```
latexmk -pdf main.tex      # or: make
```

## Layout

```
main.tex              document + \input of the sections
sections/*.tex        one file per section (01_introduction … 08_reproducibility)
figures/              generated PNGs (GUI depth-map+profiles exports, metric curves, schemas)
results/              one folder per showcase figure: config.toml + f.tif (+ truth.tif),
                      so each figure is reproducible from matirf_python_plus
refs.bib              bibliography
```

## Why results live here

The reconstructions behind the figures are stored **in this repo** (`results/`), not in
`matirf_python_plus` (whose `benchmarks/results/` is gitignored and was once lost). Keeping the
`config.toml` + `f.tif` next to the report makes every figure reproducible and the report
self-contained.

## Companion

Theory and per-algorithm analysis live in `matirf_python_plus/docs/algorithms/`
(`00_foundation.md`, the per-algorithm notes, `limits.md`) and the provisional pre-benchmark
findings in `docs/benchmark/pre_benchmark.md`. This report distils them; it does not repeat them.
