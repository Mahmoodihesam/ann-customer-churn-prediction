# Customer churn prediction using an Artificial Neural Network (ANN).

A machine learning project for predicting customer churn using an Artificial Neural Network (ANN) built with TensorFlow and Keras.

## Project Overview
Customer churn prediction is a classification problem where the goal is to identify customers who are likely to leave a company.

In this project, an Artificial Neural Network is trained to predict whether a customer will churn based on demographic and account-related features.

## Dataset
The project uses the Churn_Modelling.csv dataset.
The dataset contains information such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Membership Status
- Estimated Salary

The target variable is:

- Exited — whether the customer left the company

## Data Preprocessing

The following preprocessing techniques were applied:

- Label Encoding
- One-Hot Encoding
- Train/Test Split
- Missing Value Imputation
- Feature Scaling using StandardScaler

## Model Architecture

The Artificial Neural Network consists of:

Input layer
- Hidden Layer 1 — 6 neurons, ReLU activation
- Hidden Layer 2 — 6 neurons, ReLU activation
- Output Layer — 1 neuron, Sigmoid activation
## Training Configuration

- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Batch Size: 32
- Epochs: 100

## Results

The trained ANN achieved an accuracy of approximately:

86.9%

Model performance was evaluated using a confusion matrix and classification metrics.

## Technologies
- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib
