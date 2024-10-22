# Mall-Customer
This dataset applies clustering techniques to segment customers of a mall based on their annual income and spending score. The goal is to identify distinct customer groups to aid in targeted marketing strategies.

# Project Synopsis
The project uses K-means and Hierarchical clustering algorithms to segment customers based on their spending habits and income. It demonstrates the process of data exploration, preprocessing, model application, and result visualization using Python and popular data science libraries.

# Data Preprocessing
The dataset requires some data preprocessing steps to ensure it is ready for analysis and modeling. These steps include:
1. Standardization
2. Feature Selection
3. Dendrogram Plotting
4. Agglomerative Clustering

# Installation
-- Python Libraries for data analysis

1. pandas
2. numpy
3. scikit-learn
4. matplotlib
5. seaborn
6. scipy

# Key Findings
1.	Optimal number of clusters: The Elbow Method suggested 5 as the optimal number of clusters for K-means.
2.	Customer Segments:
   •	Low income, low spending score
   •	Low income, high spending score
   •	Medium income, medium spending score
   •	High income, low spending score
   •	High income, high spending score
3.	Silhouette Score: The K-means clustering achieved a silhouette score of 0.55, indicating reasonably well-defined clusters.
4.	Visualization: The scatter plot of the clusters shows clear separation between the groups, validating the effectiveness of the segmentation.
 
