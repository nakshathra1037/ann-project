# Binary Classification Using Artificial Neural Network (ANN)

## Overview

This project implements an Artificial Neural Network (ANN) to classify data into two classes using supervised learning.

## Technologies Used

- Python
- Scikit-learn
- NumPy

## Dataset

- **Dataset:** Make Moons
- **Source:** Generated using Scikit-learn
- **Samples:** 500
- **Classes:** 2

The dataset contains two interleaving half-moon shapes and is generated automatically by the program.

## Model

The project uses an `MLPClassifier`, a neural network model available in Scikit-learn.

## How It Works

1. Generate the dataset using `make_moons`.
2. Split the data into training and testing sets.
3. Standardize the input features.
4. Train the ANN model.
5. Predict the class labels for test data.
6. Evaluate the model using classification metrics.

## Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report

## Installation

Install the required library:

```bash
pip install scikit-learn
