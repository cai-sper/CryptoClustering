# CryptoClustering
 
## Project Overview

This project aims to cluster cryptocurrencies based on their market data to identify patterns or trends. Two methods are used for clustering: one using original data and the other using Principal Component Analysis (PCA) data.

## Table of Contents

1. [Data Preparation](#data-preparation)
2. [Clustering with Original Data](#clustering-with-original-data)
3. [Clustering with PCA Data](#clustering-with-pca-data)
4. [Visualizing and Comparing Results](#visualizing-and-comparing-results)

## Data Preparation

* Loaded `crypto_market_data.csv` into a DataFrame.
* Normalized the data using the StandardScaler from scikit-learn.

## Clustering with Original Data

* Best value for k: 4
* Initialized and fit the K-means model.
* Created a scatter plot to visualize the clusters.

## Clustering with PCA Data

* Total explained variance: Approximately 86%
* Best value for k: 4
* Initialized and fit the K-means model using PCA data.
* Created a scatter plot to visualize the clusters.

## Visualizing and Comparing Results

* Both clustering methods resulted in similar k values.
* Using PCA data led to more compact clusters, making them easier to interpret visually.
