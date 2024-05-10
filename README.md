# CryptoClustering: Unsupervised Learning for Cryptocurrency Analysis
### Overview
CryptoClustering is a Python project aimed at analyzing cryptocurrency market data using unsupervised learning techniques. The project focuses on predicting whether cryptocurrencies are influenced by 24-hour or 7-day price changes through clustering algorithms and dimensionality reduction methods.

### Project Structure
The project follows a structured approach:

1. Data Preparation:
  - Load cryptocurrency market data from a CSV file into a Pandas DataFrame.
  - Normalize the data using StandardScaler() from scikit-learn.
2. Exploratory Data Analysis (EDA):
 - Generate summary statistics and visualizations to understand the dataset's characteristics and distributions.
3. Determining Optimal Clusters:
  - Implement the elbow method to find the optimal number of clusters (k) using the original scaled DataFrame.
4. Clustering Cryptocurrencies:
  - Utilize K-means clustering algorithm to group cryptocurrencies based on market behavior.
  - Visualize clusters using scatter plots.
5. Dimensionality Reduction with PCA:
  - Perform Principal Component Analysis (PCA) to reduce the feature space.
  - Assess explained variance to understand each principal component's contribution.
6. Optimizing Clusters using PCA:
  - Apply the elbow method on PCA-transformed data to determine the optimal number of clusters.
  - Cluster cryptocurrencies based on PCA-transformed data and visualize the results.
7. Visualizing and Comparing Results:
  - Create composite plots to compare elbow curves and cluster visualizations from original data with PCA-transformed data.

### Requirements and Scoring
The project adheres to specific requirements and scoring criteria outlined in the project instructions, including finding the best value for k, clustering analysis, visualization, code organization, and comments.
