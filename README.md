# Text Classification using Unsupervised Learning

This repository contains the implementation of k-means clustering algorithm and Principal Component Analysis (PCA) for the classification of parties involved in patent litigation as organization, individual or unknown.

## Implementation
This is an unsupervised classification problem which can be solved by the clustering technique. First, we preprocess the data and try to extract some common features which can be used to distinguish data. Since these features might be correlated to each other, so we will perform Principal Component Analysis (PCA) which will return the uncorrelated vectors and also reduce the dimension of our feature space. Then, we can plot the output in two-dimensional space and expect to see distinct clusters. Now, we can apply the k-means clustering algorithm to form the clusters and label them according to our output labels.

It is divided into the following sections:
* Getting the necessary libraries & data
* Preprocessing the data
* Performing feature engineering to extract features
* Training a model to perform PCA and clustering
