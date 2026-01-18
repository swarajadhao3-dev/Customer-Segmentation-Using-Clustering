# Customer Segmentation Using Clustering
## Overview

This project focuses on customer segmentation using unsupervised machine learning techniques to group wholesale customers based on purchasing behavior. The objective is to identify distinct customer segments that can help businesses improve marketing strategies and inventory planning.

The project applies K-Means and Hierarchical Clustering along with feature scaling, optimal cluster selection, and dimensionality reduction for visualization.

## Dataset

The project uses the Wholesale Customers Dataset from the UCI Machine Learning Repository.

### Features Used

Fresh

Milk

Grocery

Frozen

Detergents_Paper

Delicassen

Categorical features such as Channel and Region were removed to ensure accurate distance-based clustering.

## Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib

## Project Workflow

Loaded and explored the dataset

Removed categorical features

Scaled numerical features using StandardScaler

Selected optimal number of clusters using the Elbow Method

Applied K-Means and Hierarchical Clustering

Visualized clusters using PCA and dendrograms

### Clustering Techniques

K-Means clustering is used as a centroid-based algorithm to group customers based on purchasing patterns. Hierarchical clustering is applied using Ward’s method to build a cluster hierarchy.

## Results and Insights

The clustering approach successfully segmented customers into distinct groups based on their purchasing behavior. Each cluster represents a unique customer profile that can be used for business analysis and strategy development.

## How to Run

Open the notebook in Google Colab or Jupyter Notebook

Install required libraries

Run the notebook cells sequentially

## Future Improvements

Evaluate clustering using Silhouette Score

Apply DBSCAN clustering

Add detailed business interpretation of clusters

Build an interactive dashboard

## Author

Swara Jadhao

Github : https://github.com/swarajadhao3-dev
