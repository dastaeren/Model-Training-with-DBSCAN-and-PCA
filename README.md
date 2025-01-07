# PCA and DBSCAN Analysis Project

## Overview
This project demonstrates the use of **Principal Component Analysis (PCA)** for dimensionality reduction and **Density-Based Spatial Clustering of Applications with Noise (DBSCAN)** for clustering. The goal is to uncover patterns in the dataset by reducing its dimensionality while retaining most of the variance and applying a density-based clustering approach to identify meaningful clusters.

## Features

### **Data Preprocessing:**
-   No missing values found
- Scales features using `StandardScaler` for uniformity.

### **Dimensionality Reduction with PCA:**
- Applies PCA to reduce dimensions while retaining 95% of the cumulative explained variance.
- Visualizes explained variance and PCA-transformed data in 2D scatter plots.

### **Clustering with DBSCAN:**
- Experiments with key parameters (`eps` and `min_samples`) to find the optimal configuration.
- Evaluates clustering performance using silhouette scores.
- Visualizes the clusters on PCA-transformed data.

## Visualizations

1. **Explained Variance Ratio Plot for PCA:**
   - A plot showing the cumulative explained variance ratio of the principal components. This helps visualize how much variance is retained as we reduce the dimensionality of the data using PCA. The plot shows the percentage of the dataset's original variance explained by each principal component.

2. **2D Scatter Plot of PCA-transformed Data:**
   - A 2D scatter plot that visualizes the data after it has been transformed by PCA. The data is projected onto the first two principal components, making it easier to explore patterns in the reduced-dimensional space.

3. **DBSCAN Clustering Results Visualized on PCA Components:**
   - A scatter plot showing the clusters identified by DBSCAN after applying PCA. Points are color-coded based on their cluster labels. Outliers (points labeled as `-1`) are also highlighted, showing how DBSCAN separates noise from the clusters.

These visualizations provide a comprehensive understanding of the data's structure, the effectiveness of dimensionality reduction with PCA, and how DBSCAN identifies meaningful clusters.


### **Cluster Analysis:**
- Provides cluster-wise data point counts and feature averages.
- Compares feature distributions across clusters.

## Files

- **Dataset**: The dataset is provided in the file path `College_Data.csv`.

