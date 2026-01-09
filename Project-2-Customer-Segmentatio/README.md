# Customer Segmentation using K-Means 

This project focuses on customer segmentation using K-Means clustering, an unsupervised machine learning technique. The objective is to group customers based on their income and spending behavior to help businesses understand customer patterns and design targeted marketing strategies.
This project was completed as part of a Data Analytics Internship.

# Project Overview
Customer segmentation is a crucial task in data analytics that helps businesses identify different customer groups and tailor strategies accordingly.
In this project, K-Means clustering is applied to segment customers into meaningful groups based on purchasing behavior.

# Objective
Segment customers into meaningful groups based on income and spending behavior

Identify high-value, regular, and low-value customers

Provide actionable business insights using data-driven clustering

# Dataset
The dataset contains customer-related information such as:

Income

Total spending (MntTotal)

Purchase behavior variables

Basic data cleaning and feature selection were performed before applying clustering.

# Methodology

Data loading and exploration

Data cleaning and preprocessing

Feature selection

Feature scaling using StandardScaler

Elbow Method to determine the optimal number of clusters

Applied K-Means clustering with optimal k = 4

Visualization of customer segments

# Elbow Method (Optimal Clusters)
Based on the elbow method, k = 4 was selected as the optimal number of clusters because the inertia reduction becomes marginal beyond this point.

# Customer Segmentation Visualization
Customers were segmented based on Income vs Total Spending, and clusters were visualized to understand group distribution.

# Cluster Interpretation and Customer Segments
Based on clustering results and visualization, the customer segments can be interpreted as follows:
Cluster 0 – Premium Customers
High-income, high-spending customers who contribute significantly to total revenue.
Cluster 1 – Regular Buyers
Medium-income customers with consistent purchasing behavior.
Cluster 2 – Low-Value Customers
Low-income, low-spending customers with minimal purchase activity.
Cluster 3 – Occasional Buyers
Customers who make infrequent purchases and show irregular buying patterns.

# Results & Insights
Customers were successfully segmented into 4 distinct groups

Clear separation of high-value and low-value customers

The segmentation can help businesses:

Design targeted marketing strategies

Improve customer retention

Optimize revenue generation

# Tools & Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

# Conclusion
Using K-Means clustering, customers were segmented into four meaningful groups based on income and spending behavior. The analysis identified high-value customers, regular buyers, and low-spending segments. This segmentation can help businesses make informed, data-driven marketing and customer retention decisions
