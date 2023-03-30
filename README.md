# Silhouette-Coefficient
## Clustering

This project demonstrates how to cluster companies in the IBEX35 using K-Means clustering based on their monthly returns, and how to use the Silhouette coefficient to evaluate the quality of the resulting clusters. The Silhouette coefficient measures how well each data point fits within its assigned cluster compared to other clusters, and ranges from -1 to 1. A high Silhouette score indicates that a point is well-matched to its cluster, while a low score indicates that it may be assigned to the wrong cluster.

To calculate the Silhouette score for a particular number of clusters, we first use K-Means to cluster the data and then use the Silhouette function from the scikit-learn library. This function computes the average Silhouette coefficient across all data points for a given number of clusters. We can then plot these scores against the number of clusters to determine the optimal number of clusters for the data set.

In addition to calculating the Silhouette scores, this project also demonstrates how to create a Silhouette plot to visually inspect the quality of the resulting clusters. This plot shows the Silhouette score for each data point, with higher scores indicating a better match to its assigned cluster.

By using the Silhouette coefficient and plot, we can choose the optimal number of clusters for the IBEX35 data set, which can help us to identify meaningful groupings of companies based on their monthly returns.
