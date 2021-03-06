# USI Machine Learning Projects

The projects are from the Machine Learning course 2019-2020 of USI, Lugano.  
Both Projects were mainly developed using the Keras library, and some scikit-learn.

## Project 1

The first Project is about solving a regression problem for a given dataset.  
The project is composed of 2 Tasks:

1. Use the family of models f(x, theta) = theta_0 + theta_1 * x_1 + theta_2 * x_2 + theta_3 * sin(x_1) * x_2 to fit the data.
2. Consider any family of non-linear models of your choice to address the regression problem, and compare them with the model from Task 1.

The code for each individual Task can be found in the [src](Project1/src) directory. To run the script through a terminal, just type the command
```console
$ python3 file1.py
```


or  
```console
$ python3 file2.py
```


Each script creates a model and saves it in the [deliverable](Project1/deliverable) directory. There, the command  
```console
$ python3 run_model.py
```


can be run to just see the accuracies and errors of each model when evaluated to the test sets.


## Project 2

The second Project is about solving a classification problem for the cifar10 image dataset.  
The project is also composed of 2 Tasks:

1. Create a Convolutional Neural Network classifier for the problem.
2. Hyper parameter tuning: Perform a grid search on the parameters below to find the optimal model, and then compare it with the model from Task 1  
* learning rate: {0.0001, 0.01}  
* number of neurons: {8, 64}



The code for each individual Task can be found in the [src](Project2/src) directory. To train the models, run the script through a terminal with the following command:
```console
$ python3 file1.py
```

or  
```console
$ python3 file2.py
```


Each script creates a model and saves it in the [deliverable](Project2/deliverable) directory. There, the command  
```console
$ python3 run_model.py
```


can be run to just see the comparison (using the T student statistic) of the two models, without having to train them.
