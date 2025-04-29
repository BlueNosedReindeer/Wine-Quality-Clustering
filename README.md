# Wine Quality Clustering Project

This repository contains an unsupervised machine learning project that analyzes the Wine Quality dataset. The objective is to cluster red wine samples based on their chemical properties using KMeans clustering and visualize the resulting groups using PCA.

---

## Project Overview

- **Goal**: Group red wines into clusters using only their chemical features
- **Approach**:
  - Load and clean the dataset
  - Perform Exploratory Data Analysis (EDA)
  - Scale features for clustering
  - Use the Elbow Method to determine optimal number of clusters
  - Apply KMeans clustering
  - Visualize clusters using Principal Component Analysis (PCA)

---

## Dataset

- **Source**: UCI Machine Learning Repository / Kaggle
- **File**: `winequality-red.csv`
- **Size**: 1,599 samples, 12 columns
- **Features**:
  - 11 chemical attributes (e.g., acidity, sugar, sulfur dioxide, alcohol)
  - 1 quality score (ignored for unsupervised learning)

---

## Results

- Wines were successfully grouped into **4 distinct clusters**
- PCA visualization showed clear separation between clusters
- Chemical composition alone was effective in identifying natural groupings

---

## Insights

- Clusters showed variation in chemical properties like alcohol, sulfur dioxide, and acidity
- Some clusters appeared more densely populated, indicating a majority profile type
- Potential use cases include product segmentation or guiding production adjustments

---

## Reproducibility

1. Clone the repo:
```bash
git clone https://github.com/yourusername/wine-clustering.git
cd wine-clustering
```
Run the notebook:
```bash
jupyter notebook notebookaf6a166c9a.ipynb
```
