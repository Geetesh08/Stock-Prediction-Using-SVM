# Stock Market Prediction using Support Vector Machines (SVM)

This project utilizes Support Vector Machines (SVM) for predicting stock market trends based on historical data. SVM is a powerful algorithm capable of handling classification tasks, making it suitable for predicting stock prices.

## Introduction

Predicting stock market trends is crucial for investors to make informed decisions. This project explores the use of machine learning techniques, specifically SVM, to analyze historical stock market data and forecast future price movements.

## Dataset

The dataset used in this project (`RELIANCE.NS.csv`) contains historical stock prices of Reliance Industries Limited (RELIANCE.NS) and includes features such as open, high, low, close prices, and volume. The dataset is preprocessed to handle missing values and prepare it for training the SVM model.

## Implementation

The implementation of the project involves the following steps:

1. **Data Loading and Preprocessing**: Loading the dataset, setting the date column as the index, and preprocessing the data to create predictor variables.

2. **Splitting Data**: Splitting the dataset into training and testing sets to train and evaluate the SVM model.

3. **Model Training**: Training an SVM model using the training data to predict future stock prices.

4. **Model Evaluation**: Evaluating the performance of the trained model on the test data using appropriate metrics.

5. **Strategy Implementation**: Implementing a trading strategy based on the predicted signals to calculate strategy returns.

6. **Results Visualization**: Visualizing the performance of the strategy by plotting cumulative returns.

## Dependencies

- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib

