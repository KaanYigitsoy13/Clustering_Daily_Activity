# Clustering_Daily_Activity

This project employs K-means clustering to analyze user activity data. We utilize scaling and Principal Component Analysis (PCA) for preprocessing and assess clustering performance using various metrics, including the silhouette, Calinski-Harabasz, and Davies-Bouldin scores. The objective is to identify activity trends and categorize days based on similar activity characteristics.

**Steps**

Data Preprocessing: Integration of data scaling and PCA to normalize differences in units (e.g., distance, minutes, calories).

Exploratory Data Analysis: Detailed visualizations to explore underlying patterns in daily activity data.

Clustering Analysis: Use of K-means clustering to derive insights from user activity patterns, comparing the performance of scaled and PCA-transformed data.

Performance Evaluation: To evaluate the effectiveness of our clustering approaches, we employed several metrics to compare the clustering quality between scaled data and PCA-transformed data:


**Results**

The analysis identifies three main clusters of daily activity:

Cluster 0: Moderately active group with balanced engagement across different activity intensities.
Cluster 1: Highly active, achieving the highest average caloric expenditure.
Cluster 2: Least active, predominantly sedentary lifestyle.
