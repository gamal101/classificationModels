# classificationModels
# Airline Delay Cause Classification

## Description

This project focuses on classifying airline carriers into specific categories based on various features related to flight delays. The dataset used is `Airline_Delay_Cause.csv`, which contains information about flights, delays, and cancellations.

## Installation

Ensure you have Python and the following packages installed:

- `pandas`
- `scikit-learn`
- `seaborn`
- `matplotlib`

You can install the required packages using pip:

bash
pip install pandas scikit-learn seaborn matplotlib
Usage
Load the Dataset

Update the file path in the script to point to Airline_Delay_Cause.csv.

Preprocess the Data

The script performs the following preprocessing steps:

Drops rows with missing values.
Filters data to include only specific carriers ('OO' and 'DL').
Split the Data

The data is split into training and testing sets using a 75-25 split.

Train and Evaluate Models

RandomForestClassifier: Trains a Random Forest model and evaluates it using a classification report and confusion matrix.
LogisticRegression: Trains a Logistic Regression model on the Iris dataset and provides predictions, probabilities, and accuracy.
Results
RandomForestClassifier:

Classification Report: Provides precision, recall, and F1-score for each class.
Confusion Matrix: Visualizes the performance of the classifier using a heatmap.
LogisticRegression:

Predictions: Shows predictions for sample data.
Prediction Probabilities: Provides the probability estimates for each class.
Accuracy Score: Displays the accuracy of the model on the dataset.
Visualizations
Confusion Matrix: A heatmap representation of the confusion matrix is used to visualize classification performance.
