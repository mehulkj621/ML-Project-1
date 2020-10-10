# ML-Project-1
Social-Networks-Ads based on KNN
Logistic Regression
Logistic regression is a classification algorithm used to assign observations to a discrete set of classes. Unlike linear regression which outputs continuous number values, logistic regression transforms its output using the logistic sigmoid function to return a probability value which can then be mapped to two or more discrete classes.

K Nearest Neighbors:
The k-NN algorithm is among the simplest of all machine learning algorithms. The input consists of the k closest training examples in the feature space while the output depends on whether k-NN is used for classification or regression:

In k-NN classification, the output is a class membership. An object is classified by a majority vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the class of that single nearest neighbor.

In k-NN regression, the output is the property value for the object. This value is the average of the values of its k nearest neighbors.

KNN works well with a small number of input variables (p), but struggles when the number of inputs is very large.


Our Goal is to predict whether a person will be able to buy a car depending upon his age and his salary.

Using Logistic Regression we achived an accuracy of - 0.875

Using K Nearest Neighbours we achived an accuracy of - 0.9166666666666666
