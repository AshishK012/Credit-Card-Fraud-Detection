# Credit Card Fraud Detection

## Overview
This project focuses on detecting credit card fraud using machine learning techniques. It aims to distinguish between genuine and fraudulent transactions by analyzing a dataset containing various transaction features.

## Problem Statement
Credit card fraud is a growing concern with the rapid increase in online transactions. This project addresses the need for efficient and secure methods to detect fraud using data mining and statistical techniques.

## Dataset
The dataset used in this project includes the following features:

- **Time**: The number of seconds elapsed between this transaction and the first transaction in the dataset.
- **V1 to V28**: The principal components obtained from PCA (Principal Component Analysis) to protect user identities and sensitive features.
- **Amount**: The transaction amount.
- **Class**: The class label where 0 indicates a genuine transaction and 1 indicates a fraudulent transaction.

## Tasks Performed
1. **Load the Dataset**: Using the pandas module to load the dataset.
2. **Missing Value Analysis**: Checking for and handling missing values in the dataset.
3. **Transaction Analysis**:
   - Calculate the number of genuine and fraudulent transactions.
   - Calculate the percentage of fraudulent transactions.
4. **Data Visualization**: Visualize the distribution of genuine and fraudulent transactions using a bar graph.
5. **Normalization**: Normalize the `Amount` column and store the values in a new `NormalizedAmount` column.
6. **Data Splitting**: Split the dataset into training and testing sets with a 70:30 ratio.
7. **Model Training**: Train two models - a Decision Tree and a Random Forest classifier - on the training set.
8. **Model Predictions**: Compare predictions from both models.
9. **Model Evaluation**: Compare the accuracy and performance metrics of both models.

## Usage

### Prerequisites
Ensure you have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these packages using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
