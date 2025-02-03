# NBA-Analysis
NBA Player Performance Analysis 

## Overview

This repository contains Jupyter Notebooks implementing and analyzing clustering algorithms using Python. The primary algorithms covered include:

- **K-Means Clustering**
- **Hierarchical Clustering**
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**

Additionally, an optimized model selection process is included in `Best Model.ipynb` to determine the most suitable clustering technique.

## Files Description

### 1. `Best Model.ipynb`

This notebook evaluates different clustering algorithms and determines the best model based on various performance metrics. Key components include:

- Data preprocessing
- Applying multiple clustering techniques
- Evaluating cluster quality using silhouette scores and other relevant metrics

### 2. `DBSCAN.ipynb`

This notebook focuses on the DBSCAN clustering algorithm, covering:

- Explanation of the DBSCAN algorithm
- Implementation using `sklearn.cluster.DBSCAN`
- Hyperparameter tuning (eps, min\_samples)
- Evaluation and visualization of clusters

### 3. `K_Means_and_Hierarchical_Clustering.ipynb`

This notebook compares K-Means and Hierarchical Clustering methods, including:

- Implementation of K-Means clustering
- Choosing the optimal number of clusters using the Elbow method and Silhouette analysis
- Implementation of Agglomerative Hierarchical Clustering
- Dendrogram analysis for cluster selection

## Requirements

Ensure you have the following dependencies installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/Pardhasai7/NBA-Analysis.git
   cd NBA-Analysis
   ```
2. Install required dependencies.
3. Open the Jupyter notebooks and run them in order.

## Results and Insights

- Each notebook provides visualizations and metrics to assess clustering effectiveness.
- `Best Model.ipynb` helps in selecting the most appropriate clustering algorithm for the given dataset.

## Author

[Pardha Sai Nekkalapu]


