# Cohort-Analysis-RFM-segmentation-and-customer-clustering

This repository contains jupyter notebook for RFM segmentation and clustering of customers. We aim to use k-means and agglomerative clustering algorithms to cluster the customers. Evaluating of models is done using silhouette score and snake plot to choose the best model.

The code in the notebook was executed using python 3.6; the following python libraries were used throughout the project:

    - numpy
    - pandas
    - matplotlib
    - datetime
    - seaborn
    - sklearn
    - scipy

### Data Source

Online retail dataset is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

link : https://archive.ics.uci.edu/ml/datasets/online+retail

### Project Structure

    - Import data
    - Data cleaning and preparation
    - Explorartory Data Analysis
    - RFM Segmentation
    - K-Means clustering
    - Agglomerative clustering
    - Model Evaluation

### Conclusion

We have compared results from both clustering algorithms. K-Means performed better for clustering the customers considering the silhouette score. Silhouette score is a way to measure how close each point in a cluster is to the points in its neighboring clusters. For evaluation of clusters, we used silhouette score and snake plot.
