# PRODIGY_ML_02
K-means clustering algorithm to group customers of a retail store

## Dataset
- **Dataset Source:** [Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Data Shape:** (200, 5)
- **Attributes:**
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)
 
## K-means Clustering
- Used sklearn's KMeans algorithm to perform clustering.
- Chose the number of clusters (K=4) based on the elbow method.
- Fit the KMeans model to the selected features.
- Added the cluster labels to the original dataset.
- Visualized the clusters using matplotlib and seaborn.
- Analyzed the clusters to understand the characteristics of each group.

## Results
- The K-means clustering algorithm successfully grouped the customers into 4 clusters.
- Each cluster represents a distinct segment of customers based on their annual income and spending score.
- These clusters can be used for targeted marketing strategies to tailor products and services to specific customer segments.

## Conclusion
The clustering analysis provides valuable insights into customer segmentation, which can be used for personalized marketing strategies and business decisions.
