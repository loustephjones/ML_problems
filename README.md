# ML_problems

## Q : Bias vs Variance

A: Bias is due to erroneous or overly simplistic assumptions, which can lead to the model underfitting data. Variance is too much complexity in the learning algorithm, which can lead to high sensitivity and an overfit of the data.

## Q: Supervised learning vs Unsupervised Learning

A: Supervised learning has a target - it requires training labeled data. Unsupervised has no target - requires no explicity labeling of data.

## Q: KNN vs k-means clustering

A: KNN is supervised classification, k-means is unsupervised. KNN you already have labeled data that you want to classify an unlabeled point into. k-means is unlabeled data points and a threshold, and the algorithm will learn how to cluster them.

## Q: What is deep learning

A: Deep learning uses neural networks - it uses unsupervised learning algorithms.

## Q: How to handle imbalanced datasets

A: Collect more data, resample the dataset, try a different algorithm.

## Q: When to use classification over regression?

A: Classification produces discrete values - strict categories. Regression gives continuous results that allow you to distinguish differences between individual points. Classification should be used if you want to reflect the category fit of a data point given certain explicit categories.

## Q: Missing or corrupted data in a dataset

A:
isnull() and dropna() to find columns and drop them
