# CryptoClustering

Crypto Clustering Assignment
This repository contains the code and instructions for the Crypto Clustering assignment. In this assignment, we will explore clustering techniques to analyze and group cryptocurrencies based on their market data.

Instructions
Follow the instructions below to complete the assignment:

Rename the Crypto_Clustering_starter_code.ipynb file as Crypto_Clustering.ipynb.

Load the crypto_market_data.csv file into a DataFrame. This file contains the market data for cryptocurrencies.

Get the summary statistics and plot the data to have an initial understanding of its structure.

Prepare the Data:

Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
Find the Best Value for k Using the Original Scaled DataFrame:

Use the elbow method to find the best value for k by computing the inertia with different values of k.
Plot a line chart with the inertia values to visually identify the optimal value for k.
Answer the question: What is the best value for k?
Cluster Cryptocurrencies with K-means Using the Original Scaled Data:

Initialize the K-means model with the best value for k.
Fit the K-means model using the original scaled DataFrame.
Predict the clusters to group the cryptocurrencies using the original scaled DataFrame.
Create a scatter plot to visualize the clusters.
Optimize Clusters with Principal Component Analysis (PCA):

Perform PCA on the original scaled DataFrame to reduce the features to three principal components.
Retrieve the explained variance to determine the information attributed to each principal component.
Answer the question: What is the total explained variance of the three principal components?
Create a new DataFrame with the PCA data and set the "coin_id" index as the index for the new DataFrame.
Find the Best Value for k Using the PCA Data:

Use the elbow method on the PCA data to find the best value for k.
Plot a line chart with the inertia values to visually identify the optimal value for k.
Answer the question: What is the best value for k when using the PCA data? Does it differ from the best k value found using the original data?
Cluster Cryptocurrencies with K-means Using the PCA Data:

Initialize the K-means model with the best value for k.
Fit the K-means model using the PCA data.
Predict the clusters to group the cryptocurrencies using the PCA data.
Create a scatter plot to visualize the clusters.
Answer the question: What is the impact of using fewer features to cluster the data using K-Means?
