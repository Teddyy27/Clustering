# Clustering-Assignment

## Objective

This assignment explores a comparative performance study of various clustering algorithms using different pre-processing techniques on the "Air Quality" dataset from the UCI repository. The objective is to perform clustering using KMeans, Hierarchical Clustering, and MeanShift algorithms while evaluating the results based on multiple evaluation metrics. The dataset's clustering performance is evaluated for different preprocessing techniques such as normalization and PCA.

### Dataset

The dataset used in this assignment is the "Air Quality" dataset, available from the UCI Machine Learning Repository:

[Air Quality Dataset](https://archive.ics.uci.edu/dataset/360/air+quality)

### Methods Used

- **Clustering Algorithms:**
  - K-Means
  - Hierarchical Clustering
  - MeanShift

- **Preprocessing Techniques:**
  - Normalization (StandardScaler)
  - Principal Component Analysis (PCA)

- **Evaluation Metrics:**
  - Silhouette Score
  - Calinski-Harabasz Index
  - Davies-Bouldin Index

### Clustering Results

The results presented in this assignment summarize the performance of various clustering techniques with different preprocessing combinations and numbers of clusters. The evaluation metrics indicate the clustering quality across methods and preprocessing techniques.

#### Best Clustering Results:

- **Silhouette Score:** 0.811844
- **Calinski-Harabasz Score:** 7676.529163
- **Davies-Bouldin Score:** 0.310482
- **Number of Clusters:** 3
- **Preprocessing Applied:** Normalization
- **Clustering Method:** MeanShift

### Results & Analysis

The results are evaluated using three different clustering methods. For each method, multiple preprocessing techniques were tested, and the performance was measured using the following metrics:

1. **Silhouette Score**: Measures how similar each point is to its own cluster compared to other clusters. A higher score indicates better-defined clusters.
2. **Calinski-Harabasz Index**: Measures the ratio of the sum of between-cluster dispersion to within-cluster dispersion. A higher score indicates a better clustering result.
3. **Davies-Bouldin Index**: Measures the average similarity ratio of each cluster with its most similar cluster. A lower score indicates better clustering.
   
#### Evaluation Metrics Heatmaps

- **Silhouette Score Heatmap:**

![Silhouette Scores Heatmap](https://github.com/user-attachments/assets/91a364af-8cf7-40ce-9fe9-9c8e820c9932)

- **Calinski-Harabasz Score Heatmap:**

![Calinski-Harabasz Scores Heatmap](https://github.com/user-attachments/assets/af2d8d48-7456-462e-be98-b5ae00924a45)

- **Davies-Bouldin Score Heatmap:**

![Davies-Bouldin Scores Heatmap](https://github.com/user-attachments/assets/e2ddb4de-5060-4ae3-8801-07fd05ad7550)


### Conclusion

- The **MeanShift** method with **normalization preprocessing** provided the best clustering performance for the **Air Quality** dataset, achieving a Silhouette score of 0.811844 and a Davies-Bouldin score of 0.310482 with 3 clusters.
- This method demonstrated the ability to effectively separate the data into distinct clusters, reflecting the variations in the air quality measurements across different regions.
