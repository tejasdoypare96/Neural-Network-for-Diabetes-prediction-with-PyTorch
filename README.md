# Neural Network for Diabetes Prediction with PyTorch

This project implements a neural network for predicting diabetes using a dataset of patient health metrics. The model is built using **PyTorch** and achieves accurate predictions by leveraging various neural network architectures and techniques like data augmentation and hyperparameter tuning.


## Overview

The goal of this project is to predict whether a patient has diabetes based on several medical factors such as glucose level, BMI, age, etc. The neural network was developed using **PyTorch** and different model weights were saved for further comparisons and improvements.

### Features:
- Data preprocessing (normalization, handling missing values)
- Neural network implementation using PyTorch
- Model training and evaluation
- Saving and loading model weights
- Comparison of multiple models (improved models using different strategies)
- Visualization of training loss and accuracy

## Dataset

The dataset used in this project is the **Diabetes Dataset** available in the `dataset/diabetes_dataset.csv` file. It contains the following columns:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (0 for no diabetes, 1 for diabetes)

### Dataset Preprocessing
The following steps were applied to the dataset before training:
- **Normalization**: Scaling the data for optimal model performance.
- **Handling Missing Values**: Replacing or imputing missing values in the dataset.

## Model Architecture

The model is a simple fully connected feedforward neural network. The architecture consists of:
- Input layer: Takes in the feature set (8 features)
- Hidden layers: Two hidden layers with ReLU activation
- Output layer: A single output neuron with a sigmoid activation function, which predicts the probability of having diabetes.

