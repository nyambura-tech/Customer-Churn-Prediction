# Customer Segmentation using K-Means

## Overview
This project applies K-Means clustering to segment mall customers based on annual income and spending score. The goal is to identify customer groups that can support targeted marketing strategies.

## Dataset
- Mall Customer Segmentation Dataset (Kaggle)

## Features Used
- Annual Income 
- Spending Score 

## Project Workflow

### 1. Data Loading and Preprocessing
- Load dataset
- Handle missing values if present
- Select relevant features

### 2. Feature Scaling
- Standardize features using `StandardScaler`

### 3. Finding Optimal Clusters
- Apply Elbow Method
- Evaluate using Silhouette Score

### 4. Model Training
- Train K-Means clustering model

### 5. Visualization
- Plot customer segments
- Display cluster centroids

## Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Results

The project successfully grouped customers into clusters based on purchasing behavior and income patterns, helping identify different customer segments for business decision-making.
