# Dry Bean Clustering Analysis (K-Means & DBSCAN)

This project explores clustering techniques on the Dry Bean Dataset using unsupervised machine learning.

## Objective
The goal of this project was to investigate whether natural groupings exist within the Dry Bean dataset based on morphological features extracted from bean images.

## Dataset
Dry Bean Dataset from the UCI Machine Learning Repository.

The dataset contains:
- 13,611 samples
- 16 numerical features
- 7 bean varieties

## Methods Used
Two clustering algorithms were implemented:

### K-Means
- Used the Elbow Method and Silhouette Score to determine the optimal number of clusters.
- Optimal cluster number identified: **k = 3**

### DBSCAN
- Density-based clustering method.
- Parameters tuned using the k-distance graph.

## Tools & Technologies
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Results
- K-Means produced meaningful clusters with a Silhouette Score of **0.309**
- Davies–Bouldin Index: **1.101**
- DBSCAN identified one dominant cluster with several noise points.

## Key Learning
This project demonstrated that centroid-based clustering (K-Means) performed better than density-based clustering (DBSCAN) for this high-dimensional agricultural dataset.

## Author
Chiemelie Ubah  
MSc Data Science – University of Salford
