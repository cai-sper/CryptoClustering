# CryptoClustering

## Project Overview

The goal of this project is to use unsupervised machine learning techniques to cluster cryptocurrencies based on their 24-hour and 7-day price changes.

## Table of Contents

1. [Data Preparation](#data-preparation)
2. [K-Means Clustering](#k-means-clustering)
3. [PCA Optimization](#pca-optimization)
4. [Analysis and Results](#analysis-and-results)

## Data Preparation

* Loaded the `crypto_market_data.csv` into a DataFrame.
* Normalized the data using the `StandardScaler` from scikit-learn.

## K-Means Clustering

### Original Data

* Best value for \( k \) is 4, determined using the elbow method.
* Fitted the K-means model using the original scaled DataFrame.

### PCA Data

* Total explained variance is approximately 86%.
* Best value for \( k \) remains 4.

## Analysis and Results

* Both the original and PCA data suggested 4 clusters.
* Using fewer features (PCA) resulted in more tightly clustered data, making the clusters easier to interpret.
