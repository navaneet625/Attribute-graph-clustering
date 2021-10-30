# Attributed Graph Clustering via Adaptive Graph Convolution

For this task we, implement the Clustering method mentioned in this[paper](https://arxiv.org/pdf/1906.01210)

In this project we mainly focus on Graph conolution via adaptive and for better clustering result foucsed based on Intra cluster distance.

There are two ways for computing intra_cluster distance:
1) squared 2-norm distance: square_dist(predict_labels, feature)
2) 2-norm distance: dist(predict_labels, feature)
3) In the notebook all observation based on euclidean distance(2-norm) 

We recommend to use squared 2-norm distance, since squared 2-norm distance is usually more faster than 2-norm distance.

As the data features are nonnegative (the filtered features are also nonnegative).
