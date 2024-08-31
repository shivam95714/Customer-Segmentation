# Mall Customer Segmentation

## Aim
- Classify/cluster Mall Customers based on numerical and categorical features.
- Unsupervised Learning problem.

## Dataset Attributes
- CustomerID
- Gender
- Age
- Annual Income (k\\$)
- Spending Score (1-100)

## Notebook Contents
- Dataset Information
- Exploratory Data Analysis (EDA)
- Summary of EDA
- Feature Engineering
- Modeling
- Conclusion

## What you will learn
- Data Visualization techniques.
- K-Means Clustering Algorithm.
- Statistical Tests for hyperparameter selection.
- Difference in model performance with original & normalized datasets.

## Dataset Information
The notebook starts by importing necessary libraries and loading the dataset ('Mall_Customers.csv'). The data consists of CustomerID, Gender, Age, Annual Income, and Spending Score.

## Exploratory Data Analysis (EDA)
The features are divided into numerical and categorical. Categorical features are visually represented, and distributions of numerical features like Age, Annual Income, and Spending Score are explored.

### Categorical Features
The distribution of gender is illustrated through pie charts and count plots.

### Numerical Features
Histograms and descriptive statistics are used to analyze the distribution of numerical features.

### Numerical Features vs. Categorical Features
Box plots and violin plots are employed to compare numerical features with gender.

### Numerical Features vs. Numerical Features w.r.t Categorical Feature
Scatter plots are used to explore relationships between pairs of numerical features.

## Summary of EDA
The summary highlights key observations from the EDA, such as the distribution of customers across age groups, income ranges, and spending scores. It also suggests potential segmentation of customers based on these features.

## Feature Engineering
A correlation matrix is visualized to identify relationships between features. CustomerID is dropped, and the dataset is prepared for modeling.

## Modeling
K-Means clustering is applied to different combinations of features, and the elbow method is used to determine the optimal number of clusters (k).

### Results Table

1. Age - Annual Income (k\\$): 4 clusters
2. Age - Spending Score (1-100): 4 clusters
3. Annual Income (k\\$) - Spending Score (1-100): 5 clusters
4. Age - Annual Income (k\\$) - Spending Score (1-100): 6 clusters

## Conclusion
The dataset provides insights into unsupervised learning techniques, offering valuable information for business strategies. Exploratory Data Analysis proves crucial for understanding customer segmentation. The K-Means clustering algorithm, with careful selection of the hyperparameter k, provides a powerful tool for uncovering patterns in the data.
