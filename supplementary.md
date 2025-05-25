# Supplementary Documentation for MMP-2k

## Table of Contents
1. [CC License Detail](#cc-license-detail)
2. [Data Access](#data-access)
3. [Dataset Overview](#dataset-overview)
4. [Dataset Details](#dataset-details)


---

## CC License Detail
This dataset is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to:
- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material.

Under the following terms:
- **Attribution**: Credit must be given to the original creator.
- **NonCommercial**: You may not use the material for commercial purposes.
- **ShareAlike**: If you remix, transform, or build upon the material, you must distribute your contributions under the same license.

### Attribution Guidelines
If you use this dataset, please provide the following attribution:
Dataset name:[MMP-2k]
Creator:


---

## Data Access
### Access Link
The database is available for download at: [Huggingface](https://huggingface.co/datasets/MMP-2k/MMP-2k), [Github](https://github.com/MMP-2k/MMP-2k/releases/tag/v1.0.0). 

### Citation
Please cite if using the dataset.


---

## Dataset Overview
- **Title**: MMP-2k
- **Description**: A benchmark multi-labled macro photography (MP) database
- **Date of Release**: 23rd, Jan, 2025

## Dataset Details
### Summary
MMP-2k is a benchmark dataset containing 2,000 in-the-wild MPs. Each MP within MMP-2k is attached with a quality MOSs, a quality report consists of an overall quality description and distortion annotations.

MMP-2k dataset contains:
1. A *MMP-2k.csv* file in which each image id is associated with 17 perceptual ratings from assessors, a MOS value, distortion annotations, and a quality report. 
2. A *image* directory containing 2,000 MPs with the resolution of 512x384 (horizontal) or 384x512 (vertical).
3. A *image_1024* directory containing 2,000 MPs with the resolution of 1024x768 (horizontal) or 768x1024 (vertical).

### Structure of `MMP-2k.csv` file
| file_name  | Rating1 | Rating2 | ... | Rating17 | MOS  | Distortion annotations | Quality report |
|------------|---------|---------|-----|---------|------|------------------------|----------------|
| 1.jpg      |    *    |    *    | ... |    *    |  *   | *                      | *              |
| 2.jpg      |    *    |    *    | ... |    *    |  *   | *                      | *              |
| 3.jpg      |    *    |    *    | ... |    *    |  *   | *                      | *              |
| ...        |   ...   |   ...   | ... |   ...   | ...  | ...                    | ...            |
| 2000.jpg   |    *    |    *    | ... |    *    |  *   | *                      | *              |
---




