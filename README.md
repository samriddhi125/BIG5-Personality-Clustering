# Big Five Personality Test Clustering Analysis

This repository contains an analysis of the Big Five Personality Test dataset using clustering techniques, specifically K-means and agglomerative clustering. The Big Five personality traits, also known as the five-factor model (FFM) and the OCEAN model, represent five broad dimensions commonly used to describe human personality and psyche.

## Dataset Description

The dataset used in this analysis contains 1,015,342 questionnaire answers collected online by Open Psychometrics. It consists of 51 features representing responses to various questions related to the Big Five personality traits.

- **Source**: [Kaggle Dataset - Big Five Personality Test](https://www.kaggle.com/datasets/tunguz/big-five-personality-test)
- **Features**: 51
- **Instances**: 874,366

## Analysis Overview

The analysis includes the following steps:

1. **Data Preprocessing**: The dataset is loaded and checked for missing values. No imputation or scaling is required as the data is already clean.

2. **Exploratory Data Analysis (EDA)**:
   - **Correlation Matrix**: Visualize the correlation between the Big Five trait-related columns.
   - **Feature Distribution**: Explore the distribution of each feature in the dataset.

3. **K-Means Clustering**:
   - Perform K-means clustering with different numbers of centroids.
   - Calculate silhouette scores to determine the optimal number of clusters.
   - Visualize silhouette diagrams for different numbers of clusters.
   - Interpret cluster results and provide key insights.

4. **Agglomerative Clustering**:
   - Perform agglomerative clustering on a random sample of the dataset.
   - Calculate silhouette score and visualize dendrogram.
   - Interpret cluster results and provide key insights.

## Key Insights

- The analysis reveals distinct personality profiles within the dataset, characterized by combinations of the Big Five traits.
- Clustering techniques help identify groups of individuals with similar personality traits, enabling targeted interventions and personalized approaches.
- Silhouette scores and visualization aids assist in determining the optimal number of clusters and assessing clustering quality.

## Repository Structure

- `README.md`: Overview of the analysis, key insights, and repository structure.
- `BIG5_Clustering.ipynb`: Jupyter Notebook containing the Python code for data preprocessing, EDA, and clustering analysis.
- `data-final-clean.csv`: Cleaned dataset used for the analysis.
- `LICENSE`: License information for the repository.

## Dependencies

- pandas
- matplotlib
- seaborn
- scikit-learn
- scipy
- yellowbrick

---

Feel free to explore the analysis and provide any feedback or suggestions for improvement. Thank you!
