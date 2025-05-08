# 🎼 5510 Final Project – Music Clustering with Unsupervised Learning

This project applies unsupervised learning methods to discover natural groupings in music based on audio features, using the FMA-Small dataset.

## 🔍 Objective

- Cluster tracks based solely on their audio characteristics (no genre labels used for training)
- Evaluate clustering results using internal metrics and external genre alignment
- Compare multiple algorithms: K-Means, GMM, DBSCAN, Spectral, Hierarchical

## 📁 Project Structure

.
├── 5510-final-project.ipynb # Main analysis notebook
├── data/
│ ├── features.csv # Tracked via Git LFS
│ ├── tracks.csv # Tracked via Git LFS
│ └── fma_small/ (not included)
├── .gitattributes # LFS tracking config
└── README.md # This file


## 🚀 How to Run

1. Clone the repo
2. Download `features.csv` and `tracks.csv` (if not already present)
3. Place both files in the `data/` folder
4. Open the notebook in Jupyter and run all cells

## 📦 Dataset

- **Source**: [Free Music Archive](https://github.com/mdeff/fma)
- **Subset Used**: fma_small (8,000 tracks)
- **License**: Creative Commons BY 4.0

## 📊 Methods Used

- PCA and t-SNE for visualization
- Clustering algorithms:
  - K-Means
  - Gaussian Mixture Model (GMM)
  - DBSCAN
  - Spectral Clustering
  - Agglomerative Hierarchical Clustering
- Evaluation Metrics:
  - Silhouette Score
  - Davies-Bouldin Index
  - Adjusted Rand Index (ARI)
  - Normalized Mutual Information (NMI)

## ✍️ Author

Son Ho  
[GitHub Profile](https://github.com/sonhtgit)
