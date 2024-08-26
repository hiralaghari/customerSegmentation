# Customer Segmentation using K-Prototypes

This project demonstrates customer segmentation using the K-Prototypes algorithm. The dataset consists of various categorical and numerical features related to customers, such as age, gender, income, education, region, loyalty status, purchase frequency, purchase amount, product category, promotion usage, and satisfaction score.

## Project Overview

Customer segmentation is the process of dividing customers into distinct groups based on similar characteristics. In this project, I performed customer segmentation using the K-Prototypes algorithm, which is suitable for datasets containing both categorical and numerical data.

## Key Steps

1. **Exploratory Data Analysis (EDA):**
   - Summary statistics for both categorical and numerical features.
   - Visualizations such as bar plots, count plots, and pair plots to understand the data distribution.

2. **Customer Segmentation:**
   - Applied the K-Prototypes algorithm to the dataset to identify distinct customer segments.
   - Determined the optimal number of clusters using the elbow method and silhouette scores.
   - Segmentation was done without applying one-hot encoding to the categorical features.

3. **Cluster Analysis:**
   - Analyzed the characteristics of each cluster by examining the distribution of features within each cluster.
   - Created cluster profiles to summarize the key attributes of each segment.

4. **Visualizations:**
   - Visualized the distribution of clusters using various plots such as bar plots and heatmaps.
   - Displayed the distribution of categorical features within each cluster.

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- kmodes

## Conclusion
This project highlights the use of the K-Prototypes algorithm for customer segmentation when dealing with mixed data types. The results provide valuable insights into customer behavior and preferences.
