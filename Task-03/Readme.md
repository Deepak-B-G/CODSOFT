# IRIS FLOWER CLASSIFICATION

This repository contains Python code for analyzing the famous Iris dataset using various data visualization techniques and applying Agglomerative Hierarchical Clustering algorithm for clustering the data.

## Overview

The Iris dataset is a classic dataset used in pattern recognition. It contains measurements of various Iris flowers, including sepal length, sepal width, petal length, petal width, and species.

## Data Exploration

### Basic Information

The dataset contains 150 entries with 5 columns:
- sepal_length: Sepal length in centimeters (float64)
- sepal_width: Sepal width in centimeters (float64)
- petal_length: Petal length in centimeters (float64)
- petal_width: Petal width in centimeters (float64)
- species: Species of Iris flower (object)

### Frequency Distribution of Species

The dataset is balanced, with each species (Iris-setosa, Iris-versicolor, and Iris-virginica) having 50 entries.

### Visualization

#### Histograms
- Distribution of Petal Length, Petal Width, and Sepal Length by Species

#### Boxplot
- Boxplot of Sepal Length by Species

#### Pairplot
- Pairplot showing pairwise relationships and distributions of features by Species

#### Correlation Heatmap
- Heatmap showing the correlation between features in the dataset

## Agglomerative Hierarchical Clustering

### Clustering
Agglomerative Hierarchical Clustering was performed to cluster the data into three distinct groups based on the features. Centroids of each cluster are also visualized.

## Additional Visualizations

- Scatter plot of clusters in 2D space

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Run the Python script `iris_analysis.py`.

## Conclusion

The Iris dataset analysis provides insights into the distribution of features among different Iris species. Agglomerative Hierarchical Clustering successfully clusters the data into three distinct groups based on the features, and centroids of each cluster are visualized. Feel free to explore the code and visualizations further!

