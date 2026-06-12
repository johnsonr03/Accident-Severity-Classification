# Accident Severity Prediction

### Overview
This project aims to predict the severity of US road accidents using a series of experimental Artificial Neural Network architectures. The project pipeline processes vast historical accident records from 2016 to 2023 to forecast incident severity levels. The data preprocessing workflow encompasses addressing missing values via imputation, mitigating outliers through Winsorization, and encoding features. To maximise predictive performance, three increasingly complex ANN models were benchmarked, and the optimal architecture was further refined via hyperparameter optimisation. Accurate severity prediction is critical for traffic management, emergency medical services, and urban planners seeking to proactively optimise resource coordination and strengthen public safety.

The project implements three neural network architectures:
 - Model 1 (Experimental): A baseline, shallow Artificial Neural Network.
 - Model 2 (Experimental): An expanded ANN with additional dense layer and dropout regularisation.
 - Model 3 (Experimental): A complex ANN built with increased hidden layer depth and optimised dropout layers.

### Objectives
 - Comprehensive Preprocessing: Handle missing values, treat outliers using Winsorization, and apply categorical encoding.
 - Exploratory Data Analysis: Extract insights into spatial-temporal accident distributions and environmental correlations.
 - Model Development: Implement and train three distinct Artificial Neural Network architectures.
 - Model Benchmarking: Evaluate performance configurations across three experimental neural networks.
 - Hyperparameter Optimisation: Improve the final model's metrics by tuning hyperparameters with RandomizedSearchCV.

### Notebook Structure
 - Data Loading
 - Data Analysis
 - Data Cleaning
 - Exploratory Data Analysis:
     - Univariate Analysis
     - Bivariate Analysis
     - Multivariate Analysis
 - Data Preprocessing
 - Model Training & Testing:
     - Model 1: Baseline ANN.
     - Model 2: Deepened ANN structure with added dense layer and dropout layers.
     - Model 3: Deepest ANN configuration maximising the number of hidden units and regularisation layers.
 - Hyperparameter Optimisation
 - Result Comparison

### Dataset Information
Dataset: Sobhan Moosavi. (2023). US Accidents (2016 - 2023) [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DS/199387