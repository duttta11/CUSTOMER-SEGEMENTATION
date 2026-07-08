# Customer Segmentation using K-Means Clustering

## Overview
This project segments customers into distinct groups based on their **annual spending** and **purchase frequency**, using K-Means clustering. The goal is to identify meaningful customer segments (e.g., high-value frequent buyers vs. occasional big spenders) that could help a business target marketing strategies more effectively.

## Dataset
- Features used: **Annual Spending**, **Purchase Frequency**


## Approach
1. **Data Cleaning** — handled missing values and checked for duplicate/inconsistent entries
2. **Finding Optimal Clusters** — used the elbow method (plotting inertia vs. number of clusters) to decide on the right value of K
3. **Applying K-Means** — fit the model using the chosen K and assigned each customer to a cluster
4. **Visualization** — plotted the clusters (spending vs. frequency) to visually interpret each segment

## Results
- Number of clusters found:3
- Cluster interpretation (fill in based on your actual output), for example:
  - Cluster 1: High spending, high frequency → loyal high-value customers
  - Cluster 2: High spending, low frequency → occasional big spenders
  - Cluster 3: Low spending, low frequency → low-engagement customers

*(Add a screenshot of your cluster scatter plot here — this is the most convincing part of the README)*


## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn



## What I Learned
- How sensitive K-Means is to feature scaling, and why standardizing spending and frequency was necessary before clustering
- How to use the elbow method to justify the number of clusters instead of guessing
- How to translate cluster outputs into actual business-relevant customer segments, not just numbers on a plot

