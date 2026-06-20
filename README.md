```markdown
# MDFOF — Multi-Cluster Density Fusion Outlier Factor

**Boundary-Robust Outlier Detection via Density-Scaled Clustering and Multi-Cluster Density Fusion**

---

## Overview

MDFOF is a MATLAB-based outlier detection algorithm that combines **DS-DBSCAN**
(Density-Scaled DBSCAN) clustering with a **Multi-Cluster Density Fusion** strategy
to achieve robust detection of outliers.

---

## File Structure

MDFOF/
├── dataset/                          # Benchmark datasets for evaluation
├── DS-DBSCAN.m                       # Density-Scaled DBSCAN clustering algorithm
├── DS-DBSCAN_Clustering_Process.mp4  # Visualization of the clustering process
├── MDFOF.m                           # Main outlier detection algorithm
└── README.md
---

## Quick Start

**Requirements:** MATLAB R2018b or later

1. Clone this repository:
   ```bash
   git clone https://github.com/QiuFengxh/MDFOF.git
   ```

2. Open MATLAB and navigate to the project folder.

3. Run the main algorithm:
   ```matlab
   MDFOF
   ```

---

## Dataset

Benchmark datasets are provided in the `dataset/` folder to support reproducibility
of experimental results.

---

## License

This project is licensed under the [Apache-2.0 License](LICENSE).

---

## Contact

**Author:** QiuFengxh (Haoxia)  
If you have any questions or suggestions, feel free to open an issue.
```
