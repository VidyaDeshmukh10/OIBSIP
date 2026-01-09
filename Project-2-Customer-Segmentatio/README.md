# Customer Segmentation using K-Means Clustering

# Project Overview
This project focuses on customer segmentation using K-Means clustering, an unsupervised machine learning technique.
The objective is to group customers based on their income and spending behavior to help businesses understand customer patterns and design targeted marketing strategies.
This project was completed as part of a Data Analytics Internship project.

# Objective
Segment customers into meaningful groups based on purchasing behavior
Identify high-value, regular, and low-value customers
Provide actionable business insights using data-driven clustering

# Dataset
The dataset contains customer-related information such as:
Income
Total spending (MntTotal)
Purchase behavior variables
Demographic attributes
Basic data cleaning and feature selection were performed before clustering.

# Methodology
Data Loading & Exploration
Loaded dataset and explored structure and features
Data Cleaning & Feature Selection
Removed unnecessary features
Selected relevant numerical variables for clustering
Feature Scaling
Standardized data using StandardScaler
Elbow Method
Used inertia values to determine the optimal number of clusters
K-Means Clustering
Applied K-Means with optimal k = 4
Visualization
Visualized clusters using Income vs Spending

# Elbow Method (Optimal Clusters)
Based on the elbow method, k = 4 was selected as the optimal number of clusters because the reduction in inertia becomes marginal beyond this point.

# Customer Segmentation Visualization
The scatter plot below shows customer clusters based on Income and Total Spending (MntTotal).

# Cluster Interpretation and Customer Segments
Based on the clustering results and visualization, the customer segments can be interpreted as follows:
Cluster 0 – Premium Customers
High-income, high-spending customers who contribute significantly to total revenue.
Cluster 1 – Regular Buyers
Medium-income customers with consistent purchasing behavior.
Cluster 2 – Low-Value Customers
Low-income, low-spending customers with minimal purchase activity.
Cluster 3 – Occasional Buyers
Customers who make infrequent purchases and show irregular buying patterns.

# Conclusion
Using K-Means clustering, customers were successfully segmented into 4 distinct groups based on income and spending behavior.
This segmentation helps businesses:
Identify high-value customers
Improve customer retention
Design targeted marketing strategies
Optimize business decision-making
# Tools & Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab
