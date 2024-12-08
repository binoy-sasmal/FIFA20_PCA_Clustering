# FIFA 20 Player Analysis with PCA and Clustering

## Overview
This project analyzes FIFA 20 player data using Principal Component Analysis (PCA) and K-means clustering to identify distinct player archetypes and patterns in player attributes. The analysis helps understand player characteristics, similarities, and natural groupings within the dataset.

## Features
- Data cleaning and preprocessing of FIFA 20 player attributes
- Exploratory Data Analysis (EDA) with visualizations
- Dimensionality reduction using PCA
- Player clustering using K-means
- Cluster analysis and visualization
- Comprehensive statistical analysis of player attributes


## Project Structure
```
FIFA20_PCA_Clustering/
├── data/
│   └── players_20.csv
├── notebook/
│   └── FIFA20_PCA_Clustering_Project.ipynb
│   └── fifa20_clusters.csv (generated)
└── README.md
 
```

## Analysis Pipeline
1. **Data Preprocessing**
   - Removal of irrelevant columns
   - Handling missing values
   - Feature standardization

2. **Exploratory Data Analysis**
   - Distribution analysis of key attributes
   - Correlation analysis
   - Statistical summaries

3. **Principal Component Analysis**
   - Dimensionality reduction
   - Variance analysis
   - Component selection

4. **Clustering Analysis**
   - Optimal cluster determination using elbow method and silhouette scores
   - K-means clustering
   - Cluster visualization and interpretation

## Results
The analysis produces:
- Reduced dimensional representation of player attributes
- Player clusters based on similar characteristics
- Visualizations of player distributions and relationships
- Statistical summaries of player clusters

## Output
The project generates a CSV file (`fifa20_clusters.csv`) containing the original data with cluster assignments for further analysis.


## Acknowledgments
- FIFA 20 dataset from Kaggle
