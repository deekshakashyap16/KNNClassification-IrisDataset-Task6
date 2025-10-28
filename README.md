# Task 6: K-Nearest Neighbors (KNN) Classification — Iris Dataset

This repository contains my implementation of the K-Nearest Neighbors (KNN) algorithm using the Iris dataset. The goal was to understand how KNN works, experiment with different values of K, and visualize how it classifies data.

What did I do?

#### Data Preprocessing

Dropped the unnecessary Id column and label-encoded the Species column.
Normalized the features using MinMaxScaler since KNN relies on distance, and features on different scales can distort results.

#### Training the KNN Model

Trained a KNeighborsClassifier with k = 5.
Achieved 100% accuracy on the test set — not surprising, since the Iris dataset is simple and perfectly separable.
The confusion matrix and classification report showed no misclassifications.

#### Experimenting with Different K Values

Tested K values from 1 to 10 and plotted their accuracies.
Accuracy remained 1.0 across all values, confirming that the dataset is clean and easy to classify.

#### Visualizing Decision Boundaries

Plotted the decision regions using Petal Length and Petal Width.
The visualization clearly showed how KNN separates the three species into distinct zones.

### Tools and Libraries

Pandas, NumPy,Scikit-learn, Matplotlib and Seaborn