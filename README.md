# PCA Manual Implementation

Complete Principal Component Analysis (PCA) implementation from scratch using only NumPy/Pandas - no scikit-learn.

## Quick Start
```bash
# Install dependencies
pip install numpy pandas matplotlib jupyter

# Run notebook
jupyter notebook PCA_Formative_1.ipynb

## Features
Manual data standardization: (X - mean) / std

Covariance matrix calculation from scratch

Eigendecomposition using numpy.linalg.eig

Sort principal components by explained variance

Projects 24-dimensional data → 2D principal components

Top 2 PCs explain 40.4% variance (PC1: 31.1%, PC2: 9.3%)

Works with 594 samples of African malaria dataset

Visualizes original vs reduced data

# Implementation Steps
Load Dataset: DatasetAfricaMalaria.csv (numerical features only)

Preprocess: Handle missing values, impute with mean

Standardize: Manual standardization without sklearn

Covariance Matrix: Compute using np.cov()

Eigendecomposition: Calculate eigenvalues/vectors

Sort Components: Descending order by eigenvalue

Project Data: Dot product with top eigenvectors

Visualize: Compare 24D vs 2D representation

Analyze: Show explained variance ratios

# Dataset
Place DatasetAfricaMalaria.csv in your working directory. 
