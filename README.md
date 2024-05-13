# Point Cloud Clustering
This repository contains Python scripts for performing point cloud clustering using two different algorithms: DBSCAN and K-means. The scripts utilize the open3d library for point cloud processing and visualization, along with numpy, matplotlib, and scikit-learn for various tasks. Point cloud clustering is a common task in the field of 3D data analysis and computer vision. It involves grouping together points in a point cloud based on their spatial proximity or other characteristics. This repository provides scripts to perform clustering using two popular algorithms: DBSCAN and K-means.

## DBSCAN Clustering
![image](https://github.com/KAN201197/Point_Cloud_Clustering/assets/128454220/eb020530-d15a-4037-a4cf-719220a64341)

The DBSCAN (Density-Based Spatial Clustering of Applications with Noise) algorithm is a density-based clustering method that groups together points that are closely packed, marking outliers as noise. This script demonstrates how to perform point cloud clustering using DBSCAN.

### Usage
1. Install the required dependencies.
2. Run the script dbscan_clustering.ipynb to perform DBSCAN clustering on a given point cloud file.
3. Adjust the parameters eps (maximum distance between two samples for them to be considered as part of the same neighborhood) and min_samples (minimum number of samples in a neighborhood for a point to be considered as a core point) based on the dataset characteristics.

## K-Means Clustering

![image](https://github.com/KAN201197/Point_Cloud_Clustering/assets/128454220/837554d0-aa37-4757-8b3f-330d32236790)

The K-means algorithm is a centroid-based clustering method that partitions the data into K clusters by iteratively assigning each data point to the nearest centroid and updating the centroids based on the mean of the data points assigned to each cluster. This script demonstrates how to perform point cloud clustering using K-means.

### Usage
1. Install the required dependencies.
2. Run the script kmeans_clustering.ipynb to perform K-means clustering on a given point cloud file.
3. Use the elbow method to determine the optimal number of clusters (optimal_num_clusters) by plotting the inertia values against different numbers of clusters.

## Requirements
1. Python 3.10.8
2. numpy 1.22.4
3. matplotlib 3.8.2
4. sklearn 1.4.0
5. open3d 0.18.0
