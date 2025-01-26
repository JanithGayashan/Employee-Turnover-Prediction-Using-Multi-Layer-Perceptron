# Employee-Turnover-Prediction-Using-Multi-Layer-Perceptron

Employee Leave Prediction Using NYSE Dataset

Project Overview

This project involves analyzing the NYSE Employee Dataset to predict whether an employee will leave the organization. The dataset is sourced from Kaggle and contains various features related to employee demographics, performance, and job satisfaction. The project demonstrates a data mining process, from preprocessing to building and evaluating a binary classification model using a Multi-Layer Perceptron (MLP).

Dataset

Source: Kaggle - Employee Dataset

Objective: Predict employee turnover (binary classification).

Key Features

Preprocessing:

Q-Q Plots and Histograms to analyze feature distributions.

Transformations applied to normalize data if required.

Feature encoding for categorical variables (one-hot/label encoding).

Scaling and standardization of features.

Discretization of continuous features, if necessary.

Model Development:

Built an MLP model for binary classification.

Used binary cross-entropy loss with a sigmoid activation function for output.

Experimental Techniques:

Tested different weight initialization methods (Random, Xavier, He).

Experimented with activation functions (ReLU, Sigmoid, Tanh, Leaky ReLU).

Performed hyperparameter tuning using a trial-and-error approach.

Evaluation:

Assessed model performance using metrics like Accuracy, Precision, Recall, F1-score, and ROC-AUC.

Tested the model at varying threshold values to analyze classification trade-offs.

Results

The MLP model achieved high performance in predicting employee turnover.

Key insights and visualizations are included in the notebook.