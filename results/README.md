# results/ — the runs behind the figures

One folder per showcase figure, named by a stable id (e.g. `vesicles_admm_noise002`). Each holds
everything needed to reproduce that figure from `matirf_python_plus`:

```
results/<figure_id>/
    config.toml     the exact run configuration (algorithm, params, input, noise)
    f.tif           the reconstruction the figure shows
    truth.tif       the ground truth (synthetic runs only)
    metrics.json    the curated metrics for this run (nmse, depth_error_nm, …)
```

Reproduce a figure's reconstruction:

```
# in matirf_python_plus, on the v2.0 tag
env/bin/python -m pipeline run results/<figure_id>/config.toml   # -> f.tif
```

The PNG shown in the report is exported from the GUI display window (depth map + profiles) via
`gui/.../export_depth_and_profiles`, at a fixed pixel size for cross-figure consistency.
