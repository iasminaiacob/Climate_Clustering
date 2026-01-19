# Climate Clustering

This project explores **global climate pattern discovery** using unsupervised machine learning techniques.  
By collecting historical weather data for major cities around the world and applying clustering algorithms, we identify **data-driven climate zones** based on temperature and precipitation patterns.

The analysis is implemented in a single Jupyter Notebook: `climate_clustering.ipynb`.

---

## Overview

- Fetches historical climate data for major world cities
- Cleans and standardizes weather features
- Applies multiple clustering algorithms
- Evaluates clustering quality using standard metrics
- Visualizes discovered climate zones on a world map

---

## Methods Used

### Data Sources
- **Natural Earth**: Global city locations and population data  
- **Open-Meteo Archive API**: Historical weather data

### Features
Typical climate features include:
- Average temperature
- Maximum temperature
- Minimum temperature
- Precipitation

### Clustering Algorithms
- K-Means
- Agglomerative Clustering
- DBSCAN

### Evaluation Metrics
- Silhouette Score
- Davies–Bouldin Index

### Dimensionality Reduction
- PCA (Principal Component Analysis) for visualization and structure analysis

---

## Visualization

- Discovered climate clusters plotted on a world map
- Color-coded clusters for intuitive geographic interpretation
- PCA plots for cluster separability

---

## Tech Stack

- Python 3
- pandas
- numpy
- scikit-learn
- geopandas
- matplotlib
- requests
