# Fragrance Clustering Analysis (COM7022 ML Assignment)

This repository contains a full end-to-end **unsupervised learning pipeline** for clustering a real-world **fragrance (perfume) dataset**.  

Using a dataset of fragrances scraped from an e-commerce platform, the notebook:

- Cleans and preprocesses the data
- Handles missing values and outliers
- Encodes and scales features
- Trains multiple clustering models (**K-Means, Agglomerative Clustering, DBSCAN**)
- Evaluates them using internal validation metrics
- Visualizes the clusters via **PCA** and **t-SNE**
- Provides **business-friendly interpretations** of each cluster (e.g. "premium bestsellers", "budget long-tail" etc.)

---

## 1. Project Structure

Recommended project layout:

```text
.
├── Ml_Assignment_code.ipynb    # Main notebook with full pipeline
├── Fragrance Dataset - COM7022 - [4037].csv  # Raw dataset (1000 rows x 10 columns)
