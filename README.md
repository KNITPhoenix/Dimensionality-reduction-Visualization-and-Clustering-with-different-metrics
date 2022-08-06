# Dimensionality-reduction-Visualization-and-Clustering-with-different-metrics

## Dataset
Dataset we are dealing with here is 20Newsgroup dataset. The 20 Newsgroups data set is a collection of approximately 20,000 newsgroup documents, partitioned (nearly) evenly across 20 different newsgroups. In this project, we are going to use a subset of this dataset to learn a bit about unsupervised learning methods in machine learning.
We calculate tf-idf scores in the starting.

![alt text](https://github.com/KNITPhoenix/Dimensionality-reduction-Visualization-and-Clustering-with-different-metrics/blob/main/tfidf.png?raw=true)

## Dimensionality reduction
We use the following for dimensionality reduction one by one:

- Sparsity
- SVD
- UMAP

## Visualization
For the visualization purpose, we use babyplots, which exquisitily work on jupyter notebook. So don't try it on colab. It is a 3D map, that shows clusters very clearly.

##K-Means Clustering
KMeans is to find the optimum number of clusters to use for clustering. Here, based on our training data, we know that there are 7 clusters in the dataset. However, we want to find the number of optimum clusters solely based on our data. We then use the best cluster number to calculate the silhouette score. We also use the same metric to evaluate the best number of cluster.
