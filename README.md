# 📊 Corona Clustering Analysis
This R project analyzes COVID-19-related data in Sri Lanka using unsupervised learning techniques. The primary goal is to explore the optimal number of clusters and apply clustering algorithms such as K-means and PAM (Partitioning Around Medoids).

## 📈 Analysis Workflow
1. **Data Preparation**
- Load dataset
- Remove zero-variance columns
- Handle missing values using mean imputation
- Scale the data for clustering

2. **Cluster Number Estimation**
- Elbow Method using fviz_nbclust() and a manual WSS plot
- Silhouette Method using pamk()
- Gap Statistics using clusGap()
- Calinski-Harabasz Criterion using cascadeKM()

3. **Clustering Algorithms**
- K-means (with k = 4)
- PAM (Partitioning Around Medoids)

4. **Visualization**
- Cluster visualization with fviz_cluster()

## 📌 Results Summary
- Optimal number of clusters estimated using multiple methods.
- Clustering models (K-means and PAM) applied and evaluated.
- Final clusters visualized to interpret the grouping structure.

