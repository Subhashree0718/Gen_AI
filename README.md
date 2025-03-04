#Gen_AI 
This repository contains a Python implementation of a simple Linear Regression Estimator that finds the best-fit slope using two different methods:

Brute Force Search (Linear Search)

Gradient Descent

The project demonstrates how to estimate the best slope (m1) for a given dataset with synthetic noisy linear data.

Features

Synthetic Data Generation: Generates noisy linear data based on user-defined parameters.

Brute Force Search: Iterates over a range of slope values and finds the one with the least error.

Gradient Descent Optimization: Uses gradient descent to iteratively refine the slope value.

Visualizations: Plots the dataset, error vs. slope, loss over iterations, and final model fits.

Installation

Make sure you have Python installed. You can install the required dependencies using:

pip install numpy matplotlib

Usage

Run the Python script to execute the linear regression model:

python linear_regression.py

Code Overview

1. Data Generation

The script generates N synthetic data points based on the equation:

y = true_slope * x + true_intercept + noise

where noise is normally distributed random noise.

2. Brute Force Search

The linear_search_best_m1 function searches for the best slope (m1) by iterating through a range of values and computing the mean absolute error.

3. Gradient Descent Optimization

The gradient_descent function applies gradient descent to minimize the loss function and estimate the optimal slope.

4. Visualization

Scatter Plot: Displays the generated dataset and true regression line.

Error vs. Slope Plot: Shows error variations across different slope values in brute force search.

Loss Curve: Tracks the loss over iterations in gradient descent.

Best Fit Comparison: Compares best-fit lines from brute force and gradient descent methods.
