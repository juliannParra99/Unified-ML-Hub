# Classification Model: Iris dataset

## Purpose

This code builds a machine learning model to classify iris species. The Iris dataset contains measurements of four physical characteristics of 150 irises, along with their species labels. The goal is to build a model that can accurately predict the species of an iris given its measurements.


## Data Summary

The Iris dataset contains the following information:

Number of instances: 150
Features: 4 numerical input features, 1 categorical output feature
Feature names: sepal length, sepal width, petal length, petal width
Class names: setosa, versicolor, virginica
## Input Features

The input features are:

sepal length: The length of the sepal in centimeters
sepal width: The width of the sepal in centimeters
petal length: The length of the petal in centimeters
petal width: The width of the petal in centimeters
## Output Features

The output features are the iris species:

setosa: A small iris with short petals and sepals
versicolor: A medium-sized iris with medium-length petals and sepals
virginica: A large iris with long petals and sepals

## Additional Information

Model Building: The model is built using a support vector machine (SVM) classifier. The SVM is trained on a training set of 75% of the data, and its performance is evaluated on a test set of 25% of the data.
Model Performance: The SVM achieves an accuracy of 95% on the test set.



## Other Datasets to Try the Project

They can be loaded using the following functions:


[`load_diabetes`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html#sklearn.datasets.load_diabetes "sklearn.datasets.load_diabetes")(*[, return_X_y, as_frame, scaled]): Load and return the diabetes dataset (regression).

[`load_digits`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html#sklearn.datasets.load_digits "sklearn.datasets.load_digits")(*[, n_class, return_X_y, as_frame]) : Load and return the digits dataset (classification).

[`load_linnerud`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_linnerud.html#sklearn.datasets.load_linnerud "sklearn.datasets.load_linnerud")(*[, return_X_y, as_frame]): Load and return the physical exercise Linnerud dataset.

[`load_wine`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html#sklearn.datasets.load_wine "sklearn.datasets.load_wine")(*[, return_X_y, as_frame]): Load and return the wine dataset (classification).

[`load_breast_cancer`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html#sklearn.datasets.load_breast_cancer "sklearn.datasets.load_breast_cancer")(*[, return_X_y, as_frame]): Load and return the breast cancer wisconsin dataset (classification)


Source: [`sci-learn.org`](https://scikit-learn.org/stable/datasets/toy_dataset.html#toy-datasets "sci-learn.org")