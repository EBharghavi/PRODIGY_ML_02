# PRODIGY_ML_02
# Clustering Algorithms
Clustering algorithms are powerful tools in machine learning for grouping similar data points together. In this study, we will explore four popular clustering algorithms: K-means, Hierarchical, DBSCAN, and Affinity Propagation.

# K-means Clustering
K-means is an iterative algorithm that partitions data into K distinct clusters based on the proximity of data points to the cluster centroids. It aims to minimize the within-cluster sum of squares. K-means is computationally efficient and works well when clusters are well-separated and of similar size. It requires specifying the number of clusters in advance.

# Hierarchical Clustering
Hierarchical clustering builds a hierarchy of clusters by iteratively merging or splitting existing clusters based on their similarity. It can be agglomerative (bottom-up) or divisive (top-down). Hierarchical clustering does not require specifying the number of clusters in advance and provides a dendrogram to visualize the clustering hierarchy.

# DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
DBSCAN is a density-based clustering algorithm that groups together data points based on their density. It defines clusters as dense regions separated by sparser areas. DBSCAN can discover clusters of arbitrary shapes, handle noisy data, and does not require specifying the number of clusters in advance. It classifies points as core, border, or noise based on density and connectivity.

# The Dataset
Column	Description
CustomerID	An identifier for each customer.
Gender	Indicates the gender of the customer (Male or Female).
Age	Represents the age of the customer in years.
Annual Income (k$)	Denotes the annual income of the customer in thousands of dollars.
Spending Score (1–100)	A score ranging from 1 to 100 that quantifies the customer’s spending habits and preferences. A higher score indicates a higher tendency to spend.
Explore the dataset on Kaggle 🌐 View Dataset
