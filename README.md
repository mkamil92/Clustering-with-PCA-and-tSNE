# Clustering-with-PCA-and-tSNE
In this repository i used different clustering techniques applied on two different datasets using K-Means Clustering and various dimensionality reduction methods, including PCA (Principal Component Analysis) and t-SNE (t-Distributed Stochastic Neighbor Embedding). The goal is to explore the clustering patterns, interpret the results, and visualize the clusters effectively.

## Table of Contents

- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Techniques Used](#techniques-used)
  - [PCA 2D](#pca-2d)
  - [t-SNE](#t-sne)
  - [Analysis of Elbow Curve](#analysis-of-elbow-curve)
  - [Cluster Visualization Using PCA](#cluster-visualization-using-pca)
  - [Polar Plot](#polar-plot)
  - [Clusters Data with Centroid](#clusters-data-with-centroid)

## Project Overview

In this project i apply **K-Means Clustering** to two different datasets and analyze the results using dimensionality reduction techniques like **PCA** and **t-SNE**. The clusters are evaluated through different visualizations and analyses to draw insights about the dataset structure and groupings. The following key aspects are explored in this project:

- **PCA 2D** visualization to reduce the dataset to 2 dimensions and observe clustering patterns.
- **t-SNE** visualization to further enhance cluster visualization with non-linear dimensionality reduction.
- **Analysis of the elbow curve** to determine the optimal number of clusters for K-Means.
- **Cluster visualization using PCA** to display K-Means clustering results on a 2D PCA plane.
- **Polar plot** for more granular visualization of cluster separation.
- **Clusters data with centroids** to analyze the concentration of points and the position of centroids.

## Datasets

The project uses two different datasets(Travel Reviews and Sobar Data ). Each dataset will be analyzed separately with the same clustering techniques. These datasets may contain various features that describe the data points, and we aim to group them based on their characteristics. In these two dataset one is clustering data while second one is classification data.


Travel Reviews: https://archive.ics.uci.edu/dataset/484/travel+reviews
Sobar-72: https://www.kaggle.com/datasets/rizqiakbar/sobar-72

## Techniques Used

### PCA 2D

The data points are plotted on a 2-dimensional plane where the x-axis represents PCA1 and the y-axis represents PCA2. The clustering patterns observed in the plot suggest that there are distinct groups within the dataset.

### t-SNE

Using **t-SNE**, we visualize the high-dimensional data in a lower-dimensional space. This plot provides a deeper understanding of the clustering patterns and can show distinct groups that share similar characteristics.

### Analysis of Elbow Curve

The **elbow curve** is plotted to find the optimal number of clusters for K-Means Clustering. The elbow point suggests the most reasonable value for `k` where the sum of squared errors starts decreasing at a slower rate.

### Cluster Visualization Using PCA

The clusters are visualized after applying K-Means Clustering on the PCA-reduced dataset. This visualization highlights the density of data points within each cluster and their separation based on their characteristics.

### Polar Plot

A **polar plot** is used to show the distribution of clusters and reveal potential cyclic or periodic patterns within the data.

### Clusters Data with Centroid

The **centroids** of the clusters are visualized on the plot to show the average position of each cluster. The density of data points within each cluster is analyzed, with outliers often appearing farther from the centroids.

