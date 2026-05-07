# Jiankang Analysis Results

This folder tracks the Jiankang summary files plus mentor-facing large outputs.

Large generated artifacts:

- `jiankang_stardist_analysis.html` is tracked with Git LFS.
- `detected_cells_jiankang.csv` is tracked with Git LFS.
- `analysis_data_jiankang.json` remains local because the HTML viewer already embeds the review payload.

`detected_cells_jiankang.csv` is the full per-cell table. It includes centroid columns for small-circle overlays plus boundary JSON columns (`boundary_full_json`, `boundary_model_json`, and `boundary_grid_patch_json`) for reconstructing the final segmentation outlines.

The committed CSV summaries provide enough information to understand the final analysis at a glance, while the LFS files provide the full downloadable review outputs.
