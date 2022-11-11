# myopia_clusters
This is my solution to homework 20 for data bootcamp.

# The Challenge
I have been tasked with trying to see if there are any possible distinct groups of patients that my fellow data team can use to analyze for any predictions for myopia. To do this I will first prepare the data for use in unsupervised learning models. I will then use PCA as a dimensionality reduction. Using my PCA-reduced data I will use a t-SNE plot and K-Means elbow curve to see if there are any group clusters my team can use for the analysis.



# Recommendation
Looking at the t-SNE scatter plot there appear to be 6 clusters, 5 outside clusters around a center cluster, and the elbow curve never really flattens out but could be slowing down around 7. Since neither model is clear in the number of clusters I would recommend not clustering the patients.
