# Wine Quality Clustering
**Brief Problem Statement:** Wine Quality Classification using Clustering  

Wine quality is influenced by chemical properties such as acidity, sulfur dioxide levels, and its alcohol content.
So in this Project, I used clustering to group wines into quality levels based on their chemical composition using:  
1. K-means 
2. Hierarchical clustering  
  
and compared their performance and the resulting clusters.

**Findings:**

Both K-Means and Hierarchical Clustering were applied to the Wine dataset.  
The optimal number of clusters was determined to be 3 by using both methods using the Elbow Method and Silhouette Scores to get a score with lower error and good cohesion  
The Silhouette Score for K-Means Clustering with 3 clusters was 0.31  
The Silhouette Score for Hierarchical Clustering with 3 clusters was 0.31  
Comparing the distribution among the features and their scores they appear simillar in performance  

**Limitations:**

Both K-Means and Hierarchical Clustering were applied to the Wine dataset.  
K-Means clustering assumeing spherical clusters which may not perform well if the clusters have different shapes  
Hierarchical Clustering can be computationally expensive for larger datasets    

**Potential Improvements:**

Experimenting with different clustering methods.  
Perform feature selection or dimensionality reduction like PCA before clustering.    
Explore different scaling methods like MinMaxScaler and see how they impact results      
