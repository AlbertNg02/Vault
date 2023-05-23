
Hierarchical Clustering (Bottom-up, agglomorative)

Each point starts off as its own cluster ( We know pairwise distances)
- Merge two closest clusters
- Repeat until only one cluster remains
- Given clusters of items Ci and Cj how do you compare dist (Ci, Cj)




Pair wise -----> N ^ 2


Centroids - distance between the means of the clusters -> ONLY WORK ON NUMERIC DATA
Single Link (Min) - smallest distance between a poitn in Ci and one point in Cj -> LOCAL DATA CONCREAT LONG CHAINS
Complete link (Max). = largest distance between a pointin Ci and one in Cj -> SENSITIVE TO OUTLIERS
Group Average: average distance between point in Ci and Cj -> between local and global