# Employee-Turnover-Prediction-Using-Multi-Layer-Perceptron

## Employee Leave Prediction Using NYSE Dataset

### Project Overview

This project involves analyzing the NYSE Employee Dataset to predict whether an employee will leave the organization. The dataset is sourced from Kaggle and contains various features related to employee demographics, performance, and job satisfaction. The project demonstrates a data mining process, from preprocessing to building and evaluating a binary classification model using a Multi-Layer Perceptron (MLP).

## Dataset

- Source: Kaggle - Employee Dataset

- Objective: Predict employee turnover (binary classification).

## Key Features
1. **Preprocessing**:
   
   1.1. Q-Q Plots and Histograms to analyze feature distributions.  

   1.2. Transformations applied to normalize data if required.  

   1.3. Feature encoding for categorical variables (one-hot/label encoding).  

   1.4. Scaling and standardization of features.  

   1.5. Discretization of continuous features, if necessary.  

3. **Model Development**:
   
   2.1. Built an MLP model for binary classification.  

   2.2. Used binary cross-entropy loss with a sigmoid activation function for output.  

5. **Experimental Techniques**:

   3.1. Tested different weight initialization methods (Random, Xavier, He).  

   3.2. Experimented with activation functions (ReLU, Sigmoid, Tanh, Leaky ReLU).  

   3.3. Performed hyperparameter tuning using a trial-and-error approach.

7. **Evaluation**:

   4.1. Assessed model performance using metrics like Accuracy, Precision, Recall, F1-score, and ROC-AUC.

   4.2. Tested the model at varying threshold values to analyze classification trade-offs.

## Results

- The MLP model achieved high performance in predicting employee turnover.
- Key insights and visualizations are included in the notebook.
