## Datasets

We use **12 two-dimensional synthetic datasets** (DS01–DS12) for evaluation. These datasets cover a wide range of cluster shapes and distributions, including circular blobs, rectangular grids, linear structures, spirals, waves, and nested rectangles. Each dataset contains labeled inliers and outliers.

| No. | Dataset | Instances | Dims | Outliers | Percentage |
|-----|---------|-----------|------|----------|------------|
| 1   | DS01    | 1043      | 2    | 43       | 4.12%      |
| 2   | DS02    | 1000      | 2    | 85       | 8.50%      |
| 3   | DS03    | 1039      | 2    | 41       | 3.95%      |
| 4   | DS04    | 1641      | 2    | 45       | 2.74%      |
| 5   | DS05    | 876       | 2    | 77       | 8.79%      |
| 6   | DS06    | 1372      | 2    | 72       | 5.25%      |
| 7   | DS07    | 1037      | 2    | 37       | 3.58%      |
| 8   | DS08    | 2259      | 2    | 159      | 7.04%      |
| 9   | DS09    | 1034      | 2    | 36       | 3.48%      |
| 10  | DS10    | 2042      | 2    | 64       | 3.13%      |
| 11  | DS11    | 1020      | 2    | 26       | 2.55%      |
| 12  | DS12    | 1242      | 2    | 50       | 4.03%      |

In each CSV file, the last column represents the ground-truth label, where **1** denotes outliers and **0** denotes inliers.

## Dataset Visualization

The following figure shows the 12 synthetic datasets, where **blue points** represent inliers and **red points** represent outliers.
![Uploading datasets.png…]()


<!-- Add your visualization figure here -->
<!-- ![Dataset Visualization](figures/datasets.png) -->

## References

The synthetic datasets used in this project are referenced from the following publications:

1. Ha, J., Seok, S., & Lee, J. S. (2015). A precise ranking method for outlier detection. *Information Sciences*, 324, 88–107. https://doi.org/10.1016/j.ins.2015.06.030

2. Zhou, Y., Xia, H., Yu, D., et al. (2024). Outlier detection method based on high-density iteration. *Information Sciences*, 662, 120286. https://doi.org/10.1016/j.ins.2024.120286

3. Xia, H., Zhou, Y., Li, J., Yue, X., & Li, J. (2024). Outlier detection method based on improved DPC algorithm and centrifugal factor. *Information Sciences*, 682, 121255. https://doi.org/10.1016/j.ins.2024.121255

## License

This project is licensed under the [Apache License 2.0](LICENSE).
