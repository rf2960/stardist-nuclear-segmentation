# 1-path Analysis Results

This folder tracks small summary files only.

Large generated artifacts are intentionally kept local:

- `1path_stardist_analysis.html`
- `analysis_data_1path.json`
- `detected_cells_1path.csv`

`detected_cells_1path.csv` is the full per-cell table. It includes centroid columns for small-circle overlays plus boundary JSON columns (`boundary_full_json`, `boundary_model_json`, and `boundary_grid_patch_json`) for reconstructing the final segmentation outlines.

The committed CSV summaries provide enough information to understand the final analysis at a glance without pushing large files to GitHub.
