# UAV Road Defect Segmentation Dataset

This dataset provides pixel-level ground-truth annotations for crack-like road surface defects, designed to support segmentation-based UAV inspection and geospatial analysis workflows.

The images are derived from the publicly available Road Damage Detection 2022 (RDD2022) dataset. While RDD2022 provides bounding-box annotations suitable for object detection, this dataset introduces manually annotated pixel-level segmentation masks required for fine-grained defect geometry analysis.

A total of 400 images were manually annotated at pixel level. RGB images are provided in JPG format, while the corresponding binary segmentation masks are provided in PNG format with matching filenames.

The dataset is split into train/validation/test sets following an 80/15/5 ratio (320/60/20), using a fixed random seed to ensure reproducibility.

A `splits/` directory is provided containing text files (`train.txt`, `val.txt`, `test.txt`) with the filenames corresponding to each dataset split.

## License
This dataset is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

## Citation
If you use this dataset, please cite:

Paula López Álvarez et al., *UAV Road Defect Segmentation Dataset*, Zenodo, 2025.

