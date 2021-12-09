# adaptive-distance-knn

This project was undertaken as the Final Project for MATH540 Statistical Learning at Nazarbayev University.

## Description
K-nearest-neighbors (K-NN) is a simple but intuitive method of performing classification. However, it treats all points in the same manner and does not distinguish between boundary and non-boundary cases. In this project, we attempt to improve the results of simple K-NN by selectively performing nearest neighbor classification in one case and performing K-NN with adaptive distance in the other case. With the new distance measure, we try to make points that are in regions of the same-class points closer, while making points in mixed regions further from the testing point. In general, the performance of the proposed method is comparable to the baseline K-NN.

## Requirements
The code was written in Python 3. The following libraries are needed: `numpy`, `pandas`, `matplotlib`, `sklearn`.

## Running
The codes can be found at the `adaptive_knn.ipynb` notebook. All cells can be sequentially run. 
