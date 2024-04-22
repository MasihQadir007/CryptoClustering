
# Cryptocurrency Clustering Analysis

This repository contains code and data for performing clustering analysis on cryptocurrency data using K-Means clustering and Principal Component Analysis (PCA).

## Overview

The analysis includes the following steps:

1. **Data Preparation**: The cryptocurrency market data is loaded from a CSV file and preprocessed.
2. **Feature Scaling**: StandardScaler is used to normalize the data to prepare it for clustering.
3. **Dimensionality Reduction**: Principal Component Analysis (PCA) is applied to reduce the dimensionality of the data.
4. **Elbow Method**: The Elbow method is used to determine the optimal number of clusters (k) for both the original and PCA data.
5. **Clustering**: K-Means clustering is performed on both the original and PCA data using the optimal k obtained from the Elbow method.
6. **Visualization**: The clustering results are visualized using scatter plots to analyze the clusters.
7. **Comparative Analysis**: A composite plot is created to contrast the elbow curves and visualize the impact of using fewer features for clustering.

## Files

- `crypto_market_data.csv`: CSV file containing cryptocurrency market data.
- `Clustering_Analysis.ipynb`: Jupyter Notebook containing the Python code for the clustering analysis.
- `README.md`: This file providing an overview of the repository.

## Usage

To reproduce the analysis:

1. Clone this repository to your local machine.
2. Open and run the `Clustering_Analysis.ipynb` notebook in a Jupyter environment.

## Dependencies

- pandas
- scikit-learn
- hvplot
- matplotlib



## Author

Masih Qadir 


