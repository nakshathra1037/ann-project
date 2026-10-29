# ann-project
Binary Classification Using Artificial Neural Network (ANN)

📌 Project Overview

This project demonstrates binary classification using an Artificial Neural Network (ANN) implemented with Scikit-learn's MLPClassifier.

The model uses the Make Moons dataset, a sample dataset containing two classes with a nonlinear pattern. The goal is to train the ANN to classify data points into class 0 or class 1.

🎯 Objectives

Understand the basic working of an Artificial Neural Network.

Generate a sample dataset for binary classification.

Preprocess the data using feature scaling.

Train an ANN model using Scikit-learn.

Evaluate the model using accuracy, a confusion matrix, and a classification report.

🛠️ Technologies Used

Python

Scikit-learn

NumPy

Machine Learning

Artificial Neural Network (MLP)

📂 Dataset

This project uses Scikit-learn's built-in make_moons() function to generate the dataset.

Number of samples: 500

Number of features: 2

Number of classes: 2

Noise: 0.2

Random state: 42

The dataset does not require a separate download.

⚙️ Project Workflow

Generate the Make Moons dataset.

Split the dataset into training and testing sets using an 80:20 ratio.

Standardize the features using StandardScaler.

Create an ANN model using MLPClassifier with one hidden layer containing 10 neurons.

Train the model using the training data.

Predict the classes of the test data.

Evaluate the model using accuracy, a confusion matrix, and a classification report.

🧠 Model Details

Algorithm: Multi-Layer Perceptron (MLP)

Input features: 2

Hidden layers: 1

Neurons in hidden layer: 10

Maximum iterations: 2000

Output classes: 0 and 1

📊 Evaluation Metrics

The model is evaluated using the following metrics:

Accuracy: Measures the proportion of correct predictions.

Confusion Matrix: Shows the correct and incorrect predictions for each class.

Classification Report: Displays precision, recall, F1-score, and support for each class.

The actual evaluation results are printed when the program runs.

💻 Installation

Make sure Python is installed on your system.

Install the required library:

pip install scikit-learn

▶️ How to Run

Clone or download this repository.

Open the project folder in VS Code or a terminal.

Run the Python file:

python ann_classification.py

Replace ann_classification.py with your actual Python filename if it is different.

📁 Project Structure

ANN-Project/
├── ann_classification.py
└── README.md

📌 Expected Output

The program displays:

Model accuracy

Confusion matrix

Classification report containing precision, recall, F1-score, and support

The exact values may vary if the dataset or model parameters are changed.

📚 Learning Outcome

This project provides a beginner-friendly introduction to ANN-based binary classification, data preprocessing, model training, and performance evaluation using Scikit-learn.

👩‍💻 Author

Nakshathra
