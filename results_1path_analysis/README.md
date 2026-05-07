# 1-path Analysis Results

This folder tracks the 1-path summary files plus mentor-facing large outputs.

Large generated artifacts:

- `1path_stardist_analysis.html` is tracked with Git LFS.
- `detected_cells_1path.csv` is tracked with Git LFS.
- `analysis_data_1path.json` remains local because the HTML viewer already embeds the review payload.

`detected_cells_1path.csv` is the full per-cell table. It includes centroid columns for small-circle overlays plus boundary JSON columns (`boundary_full_json`, `boundary_model_json`, and `boundary_grid_patch_json`) for reconstructing the final segmentation outlines.

The committed CSV summaries provide enough information to understand the final analysis at a glance without pushing large files to GitHub.
