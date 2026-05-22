# Single-Cell RNA-seq Analysis Pipeline
Single-cell RNA-seq pipeline with clustering, visualization, and machine learning classification of immune cells.

# Overview
This project performs a complete single-cell RNA sequencing analysis pipeline including preprocessing, clustering, visualization, marker gene detection, and machine learning-based cell type prediction.

# Dataset
PBMC 3k dataset from 10x Genomics

# Workflow
1. Data loading (Scanpy)
2. Quality control filtering
3. Normalization and log transformation
4. PCA and neighborhood graph construction
5. UMAP visualization
6. Leiden clustering
7. Differential gene expression (marker genes)
8. Cell type annotation
9. Machine learning classification (Random Forest)

# Tools Used
- Python
- Scanpy
- Pandas
- Scikit-learn
- Matplotlib

# Results
- UMAP visualization of cell clusters
- Marker gene table per cluster
- ML classification report for cell type prediction

# Key Insight
Distinct immune cell populations were identified based on gene expression patterns.
Manually add this explanation in README later:

# Interpretation
Cluster 0 → likely T cells (CD3D, CD3E)
Cluster 1 → Monocytes (LYZ)
Cluster 2 → B cells (MS4A1)
Cluster 3 → NK cells (NKG7)

## Author
Your Name
