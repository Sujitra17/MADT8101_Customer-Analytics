# Customer Segmentation and Product Recommendation
[![](https://img.shields.io/badge/-K--Means-orange)](#) [![](https://img.shields.io/badge/-Classification-orange)](#) [![](https://img.shields.io/badge/-Student-blue)](#)

# Project objective
![image](SEC-01.jpg)

# Data Preparation/Feature Selection
![image](SEC-02.jpg)

# K-Mean Clustering
Use "elbow method" to determine the optimal number of clusters (K) for K-means clustering. The idea behind this method is to run the K-means algorithm for a range of K values and calculate the within-cluster sum of squares (WCSS) for each K. WCSS measures the variance within each cluster, and a lower WCSS indicates that the data points are closer to the centroids within their clusters, suggesting better clustering.
result k = 4
![image](SEC-03.jpg)


# Customer Segmentation
Customer segmentation based on behavior separated to 4 clusters
![image](SEC-04.jpg)

# Customer Segmentation (Proportion)
![image](SEC-05.jpg)

# Customer Segmentation Movement
Visualized by Sankey diagram
![image](SEC-06.jpg)

# EDA TOP Rank product distribution
![image](SEC-07.jpg)

# EDA Distribution Product item count by user
![.center-image](SEC-08.jpg)

# Genearte Association Rule

-using Apriori technique 
: algorithm for market basket analysis, where it helps identify patterns of co-occurrence among products in shopping baskets.

![image](SEC-09.jpg)

**Define Parameters** 

: minimum support = 0.1

: minimum threshold = 1

: lifting > 1.05

: Confident > 0.4

![image](SEC-10.jpg)
