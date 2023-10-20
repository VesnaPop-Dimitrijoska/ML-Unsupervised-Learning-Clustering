# Project Title:
ML Unsupervised Learning model - Clustering on Earthquakes dataset
#
---
# Project Description:
This is Unsupervised Learning model - Clustering on Earthquakes dataset containing Earthquakes locations from all over the world. This dataset does not contain other features, just coordinates of the earthquakes, so that is why exploratory data analysis is left out from the assignment.
#
---
# Table of Contents:
  1. Data Preprocessing 
  2. Model Training - Agglomerative Clustering
  3. Model Training - DBScan Clustering
  4. Model Training - KMeans Clustering
  5. Model Evaluation
  6. Conclusion and Results
---
#

# RESULTS:
### DBScan Clustering model with grid parameters
DBScan model that was tested gave satisfiying results, clear boundaries between clusters, without overlapping clusters. This model generaly have problem with different density of the clusters, so this is why there are many outliers in the plot. The model only cluster data with same density, so the rare clusters were seen as outliers.  

---
### Agglomerative Clustering model with grid parameters
Agglomerative Clustering model gave satisfiying Silhouette score with 15 clusters, clear boundaries between clusters, without overlapping clusters.    
In my opinion this is the best model for this kind of clustering problem, because it doesn't have prefered shape as kMeans, and it is not affected by the density as DBScan.

---
### kMeans model with grid parameters accorging to Elbow method    
In general Silhouette score is satisfying for kMeans, since I didn't expect that it would cluster the data properly, beacause kMeans can't fit irregular cluster patterns.    


#
# License
MIT License
#
