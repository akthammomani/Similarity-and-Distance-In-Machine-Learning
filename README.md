# Similarity and Distance Metrics for Data Science and Machine Learning

## Introduction

Many of the Supervised and Unsupervised machine learning models such as K-Nearest Neighbor and K-Means depend upon the distance between two data points to predict the output. Therefore, the metric we use to compute these distances plays an important role in these particular models.

A good distance metric helps in improving the performance of Classification, Clustering, and Information Retrieval process significantly. In this article, we will discuss different Distance Metrics and how do they help in Machine Learning Modelling.

## 1. Euclidean Distance Metric:

The “Euclidean Distance” between two objects is the distance you would expect in “flat” or “Euclidean” space; it’s named after Euclid, who worked out the rules of geometry on a flat surface.
The Euclidean is often the “default” distance used in e.g., K-nearest neighbors (classification) or K-means (clustering) to find the “k closest points” of a particular sample point. The “closeness” is defined by the difference (“distance”) along the scale of each variable, which is converted to a similarity measure. This distance is defined as the Euclidian distance.

Mathematically, it’s calculated using Pythagoras’ theorem. The square of the total distance between two objects is the sum of the squares of the distances along each perpendicular co-ordinate.

## 2. Manhattan Distance Metric:

Manhattan distance is a metric in which the distance between two points is the sum of the absolute differences of their Cartesian coordinates. In a simple way of saying it is the total sum of the difference between the x-coordinates and y-coordinates.
This Manhattan distance metric is also known as Manhattan length, rectilinear distance, L1 distance or L1 norm, city block distance, Minkowski’s L1 distance, taxi-cab metric, or city block distance.

Applications of Manhattan distance metric include:

  * Regression analysis: It is used in the linear regression to find a straight line that fits a given set of points
  * Compressed sensing: In solving an underdetermined system of linear equations, the regularisation term for the parameter vector is expressed in terms of Manhattan distance. This approach appears in the signal recovery framework called compressed sensing
  * Frequency distribution: It is used to assess the differences in discrete frequency distributions.
  
  
## 3. Cosine Similarity: 

Cosine similarity calculates similarity by measuring the cosine of angle between two vectors.

Mathematically speaking, Cosine similarity is a measure of similarity between two non-zero vectors of an inner product space that measures the cosine of the angle between them. The cosine of 0° is 1, and it is less than 1 for any angle in the interval (0,π] radians. It is thus a judgment of orientation and not magnitude: two vectors with the same orientation have a cosine similarity of 1, two vectors oriented at 90° relative to each other have a similarity of 0, and two vectors diametrically opposed have a similarity of -1, independent of their magnitude.
The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.











