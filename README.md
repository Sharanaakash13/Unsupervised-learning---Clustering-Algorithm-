# Unsupervised learning Clustering Algorithm

* The code performs unsupervised learning using clustering on a wine dataset. The dataset contains the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

* The code first imports the necessary libraries, including numpy, pandas, and sklearn. It then loads the wine dataset, which was obtained from the UCI Machine Learning Repository. The dataset is explored and visualized, including checking for missing values, detecting outliers, and checking for correlation between features. The dataset is pre-processed by removing correlated features, standardizing the data using the StandardScaler function from Sklearn.

* The KMeans algorithm is used for clustering the dataset. The optimal number of clusters is determined using the elbow method. The resulting clusters are then visualized using a scatter plot. Finally, the performance of the algorithm is evaluated using the silhouette score.

* Overall, this code provides a example of how to perform clustering on a real-world dataset using Python and Scikit-learn.
