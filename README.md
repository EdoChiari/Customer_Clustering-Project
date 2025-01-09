# Clustering Analysis Project

This project focuses on applying clustering techniques to analyze customer behavior using various features such as Recency, Frequency, and Monetary Value. The main goal is to identify distinct customer groups to inform business strategies like targeted marketing and personalized customer service.

## Project Overview

Clustering is a crucial unsupervised machine learning technique for grouping data points into clusters based on similarity. This project uses:

- **K-Means Clustering** to partition customers into groups.
- **Silhouette Score** and **Inertia** to evaluate cluster quality.
- **Visualization techniques** for interpreting the clusters and their features.

Libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Clustering Methodology

### Data Preprocessing:
- Outlier detection using **boxplots**.
- Scaling features using **Standard Scaler** to ensure they have a mean of 0 and standard deviation of 1.

### Clustering:
- **K-Means** clustering was applied with a range of cluster numbers.
- Optimal cluster count was determined using the **Elbow Method** and **Silhouette Analysis**.

### Evaluation:
- **Silhouette scores** and **inertia** were plotted to compare different cluster configurations.
- **Bar plots** and **line plots** were created to visualize cluster distribution and feature means.

## Steps in the Analysis

1. Import the necessary libraries and load the dataset.
2. Perform exploratory data analysis (EDA) and visualize the distribution of key features.
3. Preprocess the data by detecting and handling outliers, and scaling the features.
4. Apply **K-Means clustering** and analyze cluster performance.
5. Visualize the results using bar plots and line charts to represent cluster sizes and average feature values.

## Results and Insights

- The analysis identified distinct customer segments based on purchasing behavior.
- The average **Recency**, **Frequency**, and **Monetary Value** for each cluster were calculated, helping to characterize each group.
- Clusters with high monetary value and frequency can be prioritized for loyalty programs, while those with low frequency and high recency can be re-engaged through targeted campaigns.
