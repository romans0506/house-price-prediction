## Ames Housing - Linear Regression from Scratch

## Project Overview

The project implements a multivariate linear regression model from scratch to predict house sale prices using the Ames Housing dataset.

The main objective was to understand the mathematical foundations of supervised learning by implementing the training process without relying on a high-level machine learning library.

The project uses:

- Pandas for data loading, exploration, and preprocessing
- Numpy for numerical computation, matrix operations, and implementing the regression algorithm
- Matplotlib for visualizing the training process and model perfomance

The model was trained using gradient descent, with the cost function and gradients implemented manually.

After preprocessing and one-hot encoding, the dataset contains 330 features, with 2,344 samples used for training and 586 samples reserved for testing.

## Results 

The trained model achieved the following results on the test set:

Metric                                                          Results

R^2                                                             0.8975

MAE                                                             $15,693

RMSE                                                            $28,663


The model explains approximately 89.75% of variance in house sale prices on the test set

## Key concepts

This project covers:

- Data preprocessing and missing-value handling
- Categorical feature encoding
- Feature scailing
- Multivariate linear regression
- Mean Squared error cost function
- Gradient computation
- Vectorized NumPy operations
- Gradient descent
- Model evaluation

## Project Status

🚧 Currently in development.

## Goal

Build a regression model that predicts house prices based on property characteristics.
