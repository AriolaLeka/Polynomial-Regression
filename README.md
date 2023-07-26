# Polynomial Regression using PyTorch

This repository contains the implementation of polynomial regression using PyTorch. The goal of the project was to estimate a polynomial function from a dataset using linear regression. The dataset was generated with a known polynomial and Gaussian noise.

## Project Overview

polynomial fitting.py: Python script containing the code for data generation, visualization, and polynomial regression implementation.

## Data Generation

The data was generated following a known polynomial function with added Gaussian noise. The training dataset consists of 500 data points, while the validation dataset contains 500 data points.

## Polynomial Regression

PyTorch is used to perform polynomial regression. The model was implemented using the torch.nn.Linear module with the bias flag set to True. Gradient descent is used to optimize the model parameters and found suitable hyperparameters (learning rate and number of iterations) to achieve low training and validation losses.

## Results

The training and validation losses were plotted as a function of gradient descent iterations. It was also visualized the estimated polynomial function based on the trained model.

## Bonus - Coefficient Evolution

As a bonus, the evolution of each coefficient of the polynomial was plotted as a function of gradient descent iterations.
Certainly! Here's a section that describes how other people can run the code using the provided `.py` file:

## Running the Code

To run the polynomial regression code, you will need Python and the following libraries installed:

- NumPy
- Matplotlib
- PyTorch

### Installation

1. Install Python: If you don't have Python installed, you can download it from the official website (https://www.python.org/downloads/) and follow the installation instructions.

2. Install Required Libraries: Open a terminal or command prompt and run the following commands to install the required libraries:

   ```bash
   pip install numpy matplotlib torch
   ```

### Running the Code

1. Download the Code: Download the `polynomial fitting.py` file from this repository and place it in a directory of your choice.

2. Execute the Code: Open a terminal or command prompt, navigate to the directory where the `main.py` file is located, and run the following command:

   ```bash
   python polynomial fitting.py
   ```

   This will execute the code and generate the training and validation datasets, perform polynomial regression, and plot the results.

3. Adjust Hyperparameters (Optional): If you want to experiment with different hyperparameters, you can modify the `learning_rate` and `num_iterations` variables in the `main.py` file to suit your preferences.

4. Visualize Results: After the code execution, the training and validation loss plots will be displayed, and you can observe the estimated polynomial function based on the trained model.

Please note that the code assumes you have the necessary libraries installed. If you encounter any issues, make sure to install the required libraries using the provided instructions.
