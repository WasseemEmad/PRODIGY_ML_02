# PRODIGY_ML_02


# **K-Means Clustering Analysis**
This repository contains a Python implementation of the K-Means clustering algorithm applied to customer segmentation data. The goal is to cluster customers based on their annual income, spending score, and age, and identify patterns in customer behavior.

## **Overview**

This project performs clustering analysis on the Mall_Customers dataset using the K-Means algorithm. It covers various steps from data loading and preprocessing to model implementation and visualization of results. The code includes the use of the elbow method to determine the optimal number of clusters, as well as an optional application of Principal Component Analysis (PCA) for dimensionality reduction.

## **Features**

### **Data Loading and Inspection:** 

Loads the customer data and performs initial inspections to identify missing values and data types.

### **Data Standardization:** 

Standardizes features for better clustering performance.

### **Elbow Method:**

Uses the within-cluster sum of squares (WCSS) to determine the optimal number of clusters.

### **K-Means Algorithm:** 

Implements the K-Means clustering algorithm, including helper functions for finding closest centroids, computing new centroids, and initializing centroids.

### **Clustering with K-Means:**

Performs clustering on different sets of features.

### **PCA for Visualization:**

Optionally reduces data dimensions using PCA for better visualization.

### **Results Visualization:** 

Provides plots of clustered data, showing the clusters and centroids.

## **Prerequisites**

### **The following Python libraries are required:**

pandas
numpy
matplotlib
scikit-learn

## **Results**

### **The results include:**

An elbow plot indicating the optimal number of clusters.

Visualizations of clusters formed based on the features selected, with centroids highlighted.
