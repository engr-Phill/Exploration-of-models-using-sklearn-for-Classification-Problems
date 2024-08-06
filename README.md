# Machine Learning Model Comparison Project for classification problems

This project aims to deepen my understanding of the strengths and weaknesses of different machine learning models. By working on this project, I became familiar with popular industry tools and techniques for evaluating model performance.

## Project Overview

The project involves the following key steps:
1. **Loading Datasets:** The datasets used in this project are 'Ionosphere', 'Steel Plates Fault', and 'Banknote Authentication'.
2. **Model Selection:** Various classifiers are used, including K Neighbors Classifier, GaussianNB, Logistic Regression, Decision Tree, Gradient Boosting, Random Forest, and Multi-layer Perceptron (MLP).
3. **Hyperparameter Tuning:** For each classifier, different hyperparameters are tested to find the best performing model.
4. **Evaluation:** The models are evaluated based on their mean test errors across the datasets.
5. **Summary Tables:** Summary tables are created to present the lowest mean test errors and the corresponding hyperparameter values for each classifier and dataset.
6. **Analysis of Models** This is a PDF that describes what information can be gaind from the result tables. [My Analysis of Models](https://github.com/engr-Phill/Exploration-of-models-using-sklearn-for-Classification-Problems/blob/main/Analysis%20of%20Models.pdf)

## Datasets

The project utilizes the following datasets:
- **Ionosphere:** A dataset used for binary classification of radar returns from the ionosphere.
- **Steel Plates Fault:** A dataset for detecting faults in steel plates.
- **Banknote Authentication:** A dataset used to classify whether banknotes are authentic or not.

## Classifiers and Hyperparameters

The classifiers and their hyperparameters used in this project are:
- **K Neighbors Classifier** n_neighbors
- **GaussianNB** var_smoothing
- **Logistic Regression:** Regularization parameter (C)
- **Decision Tree:** Maximum depth
- **Gradient Boosting:** Number of boosting stages, learning rate, and maximum depth
- **Random Forest:** Number of trees, maximum depth
- **MLP Classifier:** Learning rate, regularization term, hidden layer sizes

## Results

The project outputs two main summary tables:
1. **Lowest Mean Test Errors:** This table lists the lowest mean test errors achieved by each classifier for each dataset.
2. **Corresponding Hyperparameter Values:** This table provides the hyperparameter values corresponding to the lowest mean test errors for each classifier and dataset.

## How to Run the Project

1. Ensure you have the required libraries installed:
   ```sh
   pip install numpy pandas scikit-learn
