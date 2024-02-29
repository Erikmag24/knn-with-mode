This is a simple implementation of the k-nearest neighbors (KNN) classifier with mode. The code defines a KNeighborsClassifier class with methods to fit the model with training data and to predict the classes of test data. The fit method stores the training data, while the predict method calculates distances between test points and training points to make predictions based on the majority class among the nearest neighbors. The errors method calculates the accuracy of the predictions.

The code then runs a loop to train the model with different numbers of neighbors (n_neighbors) ranging from 1 to 99, and records the accuracy for each configuration. Finally, it plots the accuracy versus the number of neighbors used in the KNN algorithm, based on 90 elements for training.

So, the graph illustrates how the accuracy of the KNN classifier varies with different numbers of neighbors used in the algorithm, with 90 elements used for training the model.










![image](https://github.com/Erikmag24/knn-with-mode/assets/147947107/d267505e-03db-4ba1-9da6-07b982ff218c)
