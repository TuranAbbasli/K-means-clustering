# K-means-clustering
Development of k-means algorithm from scratch

### Data:
The algorithm has been tested on the Iris dataset, which contains three distinct categories.

### Algorithm
Since the number of different categories was known, the application of the elbow method was unnecessary; the number of clusters was set to three.
1. Initialize Centroids: Three random instances from the dataset were chosen and set as initial centroid values.
2. Create Clusters: K empty clusters were created initially. Then, by iterating through the dataset, each instance was added to the appropriate cluster by finding the closest centroid.
3. Recenter: After the initial clusters were created, the average of the data points was calculated and set as the new centroid value.

Through the iteration of the create_cluster and recenter functions, clusters were optimized until no change in the value of centroids was observed.
