# Unsupervised Learning for Customer Segments

Robert Crowe, August 2016

Exploration and implementation of unsupervised learning to cluster customers 
into segments based on purchase history.

This was done as a project in the Udacity Machine Learning Nanodegree, as a final
project in the unsupervised learning unit.  The project is implemented in Python
using Scikit-Learn (sklearn) as a Jupyter notebook.

The dataset is first examined and a working hypothesis developed regarding the
possible customer segments.  Features are then held out as targets for supervised
learning in order to understand feature relevance.  Correlation between pairs
of features is studied using kernel density esitmation (KDE).  Outliers are then
examined and removed, and variance is examined and explained.

K-Means and Gaussian Mixture Models are compared for use with this dataset and
application, and a Gaussian Mixture Model is found to be a better fit.  Silhouette
scores are calculated, cluster archteypes are identified.  Analysis continues to
complete the clustering.
