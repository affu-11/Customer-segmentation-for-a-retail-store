# Customer-segmentation-for-a-retail-store

# Objective

The objective of this project is to perform customer segmentation for a retail store using the Mall Customers Dataset. By applying K-Means clustering, the goal is to divide customers into distinct groups based on:

1.Age

2.Annual Income

3.Spending Score

This helps businesses understand customer behavior, identify premium shoppers vs budget customers, and design personalized marketing strategies.

# About the Dataset

Name: Mall Customers Dataset (Kaggle)

Rows: 200 customers

Columns:

CustomerID – Unique ID for each customer

Gender – Male / Female

Age – Customer’s age

Annual Income (k$) – Annual income in thousands

Spending Score (1-100) – Score assigned by the mall based on purchasing behavior and spending nature

The dataset is clean, balanced, and widely used for customer segmentation case studies.

Process Followed bold text

# Data Understanding & Cleaning

Loaded dataset, checked missing values, standardized column names.

Exploratory Data Analysis (EDA)

Visualized Age, Income, and Spending Score distributions using Seaborn + Plotly.

Observed that customers vary widely across income and spending patterns.

# Feature Selection & Scaling

Chose 3 key features: Age, Annual Income, Spending Score.

Applied StandardScaler to normalize them for clustering.

Choosing Number of Clusters (k)

Used Elbow Method (WCSS curve) and Silhouette Score to find the optimal k.

Found k = 5 to be a suitable choice.

# K-Means Clustering

Trained KMeans with k=5 clusters.

Assigned each customer a cluster label.

# Visualization

Created 2D scatter plots (Income vs Spending).

Created 3D interactive plots (Age vs Income vs Spending).

Generated a heatmap summary of cluster averages.

Cluster Analysis

Interpreted each cluster to define meaningful customer segments (e.g., Premium Spenders, Budget Customers, etc.).
