# unsupervised-cluster
Mall Customer Segmentation
Problem Statement:
You own the mall and want to understand the customers like who can be easily converge (Target customers) so that the sense can be given to marketing team and plan the strategy accordingly.

Description Variables:
CustomerID: Unique ID assigned to the customer

Gender: Gender of the customer

Age: Age of the customer

Annual Income (k$): Annual Income of the customer

Spending Score (1–100): Score assigned by the mall based on customer behavior and spending nature.

****************************************************************************************************************************************************************
definition:

Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. In the realm of machine learning, k-means clustering can be used to segment customers (or other data) efficiently.

Properties of Clusters:

All the data points in a cluster should be similar to each other.

The data points from different clusters should be as different as possible.

The approach Kmeans follows to solve the problem is called Expectation Maximization:

Specify number of clusters K.

Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.

Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.

Compute the sum of the squared distance between data points and all centroids.

Assign each data point to the closest cluster (centroid).

Compute the centroids for the clusters by taking the average of the all data points that belong to each cluster.

Stopping Criteria for K-Means Clustering

There are essentially three stopping criteria that can be adopted to stop the K-means algorithm:

Centroids of newly formed clusters do not change

Points remain in the same cluster

Maximum number of iterations are reached

When to use Cluster Analysis?

If we are using a labeled data we can use classification technique whereas in case when the data is not labeled we can cluster the data based on certain feature and

try to label it on our own.So when we use cluster analysis we don’t have labels(ie..data is not labeled)in the context of machine learning this is called as

unsupervised learning.

Final Goal:

The goal of clustering is to maximize the similarity of observation within the cluster and maximize the dissimilarity between the clusters.
