# Smai_project
Attributed Graph Clustering via Adaptive Graph Convolution

There are two ways for computing intra_cluster distance:
1) squared 2-norm distance: square_dist(predict_labels, feature)
2) 2-norm distance: dist(predict_labels, feature)
3) In the notebook all observation based on euclidean distance(2-norm) 

We recommend to use squared 2-norm distance, since squared 2-norm distance is usually more faster than 2-norm distance.


As the data features are nonnegative (the filtered features are also nonnegative), the similarity matrix W is the kernel matrix XX^T. 
