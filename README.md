# Parameter Optimization of SVM

## About SVM and Parameter Optimization

* Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.
* Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 
* We can perform this task using GridSearchCV for optimizing these parameters.
* In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository : 
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of rows: 10129

Number of Attributes: 16

## Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.85 | Poly | 6.64 | 2.23 |
| 2 | 0.96 | Linear | 7.73 | 8.34 |
| 3 | 0.97 | Linear | 9.81 | 6.96 |
| 4 | 0.93 | Poly | 1.95 | 8.12 |
| 5 | 0.95 | Poly | 2.67 | 7.78 |
| 6 | 0.94 | Linear | 0.56 | 2.29 |
| 7 | 0.88 | Poly | 2.09 | 9.99 |
| 8 | 0.96 | Linear | 0.68 | 9.94 |
| 9 | 0.93 | Poly | 5.51 | 9.36 |
| 10 | 0.94 | Poly | 2.49 | 3.90 |

## Convergence Graph
![graph](https://github.com/namishjindal/Parameter-Optimization-SVM/blob/main/Convergence_Graph.png)
