# Unsupervised-Learning

## Loading and Preprocessing:

The Iris dataset is loaded from sklearn, and the features are isolated.
The data is standardized using StandardScaler to ensure all features contribute equally to the clustering process.

### Clustering Algorithm Implementation:

KMeans Clustering:
KMeans clustering is explained: it partitions the data into K clusters and iterates over the dataset to minimize the within-cluster variance.
KMeans is appropriate for the Iris dataset because it is an unsupervised learning method that can identify natural groupings in the data.
The clusters are visualized using PCA for dimensionality reduction, with the data points color-coded by their cluster assignment.
### Hierarchical Clustering:
Hierarchical clustering is explained: it merges smaller clusters into larger ones to form a hierarchy, visualized through a dendrogram.
It is suitable for the Iris dataset because it does not require specifying the number of clusters in advance, and it creates a tree structure that shows relationships between clusters.
The clusters are visualized similarly to KMeans, using PCA for dimensionality reduction and coloring the points by their hierarchical cluster label.
## Conclusion:
This project demonstrated the use of two clustering algorithms—KMeans and Hierarchical Clustering—on the Iris dataset.

KMeans effectively grouped the data into three clusters, aligning with the three Iris species, and provided clear visual separation using PCA. It is well-suited for this dataset when the number of clusters is known.

Hierarchical Clustering also identified three clusters, offering a tree-like structure to understand cluster relationships. This method is useful when the number of clusters is not predefined.

Both algorithms successfully identified distinct clusters, showcasing their applicability in clustering tasks.
