# PCA - Principal Component Analysis
Welcome to the PCA_R repository! This project is designed to provide a straightforward yet comprehensive approach to performing Principal Components Analysis (PCA) using R.

## Overview

This repository contains an R script that guides you through the process of conducting PCA on a dataset. PCA is a powerful tool for dimensionality reduction, allowing you to uncover the underlying structure of your data. This script not only handles the computation of PCA but also includes data preprocessing steps and visualization techniques to help you interpret the results.
Features

  Data Import and Preprocessing
  - Reads in data from a file.
  - Imputes missing values by calculating the mean for each feature.

  PCA Calculation
  - Uses spectral decomposition to perform PCA.
  - Also includes an implementation using Singular Value Decomposition (SVD) for comparison.

  Centroid Calculation
  - Calculates centroids for three populations within the dataset (e.g., European, Asian, African).

  Visualization
  - Visualizes the PCA results using color-coded clusters for different populations.
  - Generates a PCA plot with labeled principal components.
