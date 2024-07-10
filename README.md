## Heart Disease Dataset Analysis

This analysis focuses on clustering heart disease data from the Cleveland dataset using machine-learning techniques. The objective is to identify meaningful patterns and groupings within the data, which can be useful for predictive modeling and understanding the underlying structure of the dataset. Here are the key steps and methodologies used in the analysis:

## Clustering Methods

## K-means Clustering:
Applied K-means with 3 clusters.
Visualized clusters and evaluated performance using the Silhouette Score and Davies-Bouldin Index.

## Hierarchical Clustering:
Applied hierarchical clustering with dendrogram visualization.
Agglomerative clustering was used and evaluated using the same metrics.

## DBSCAN Clustering:
Performed a grid search to find the best parameters for DBSCAN.
Visualized clusters and evaluated performance with optimal parameters.

## Gaussian Mixture Model (GMM):
Applied GMM with 3 components.
Visualized clusters using PCA and evaluated performance.
Dimensionality Reduction
Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE) were used for 2D visualization of the clustering results, allowing for a better understanding of the data distribution in lower dimensions.
Cluster Analysis
Added cluster labels to the original data and calculated mean values of features for each cluster, providing insights into the characteristics of each group.
Evaluation Metrics
Silhouette Score: Measures how similar an object is to its cluster compared to other clusters.
Davies-Bouldin Index: Measures the average similarity ratio of each cluster with its most similar cluster, where a lower score indicates better clustering.
