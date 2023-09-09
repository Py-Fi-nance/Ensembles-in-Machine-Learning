# Ensembles-in-Machine-Learning
Theoretical explanation and project forecasting Bitcoin price 

This repository contains an in-depth analysis of the Ensembles in Machine Learning Models using Bitcoin stock price data. 

![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![Forks](https://img.shields.io/github/forks/Py-Fi-nance/Linear-Trends-and-Linear-Regression)](https://github.com/Py-Fi-nance/Ensembles-in-Machine-Learning/network)
[![Stars](https://img.shields.io/github/stars/Py-Fi-nance/Linear-Trends-and-Linear-Regression)](https://github.com/Py-Fi-nance/Ensembles-in-Machine-Learning/stargazers)

## Table of Contents
- [Prerequisites](#prerequisites)
- [Steps](#steps)
  * [Data Acquisition](#data-acquisition)
  * [Data Preprocessing](#data-preprocessing)
  * [Model Selection & Tuning](#model-selection--tuning)
  * [Visualization](#visualization)
  * [Performance Evaluation](#performance-evaluation)
  * [Predicting Future Data](#predicting-future-data)
- [Key Features](#key-features)
- [Contributing](#contributing)
- [Contact Information](#contact-information)

## Prerequisites
1. Install the required Python packages:
   ```bash
   pip install openbb scikit-learn xgboost matplotlib numpy

## Steps
### Data Acquisition
Use the openbb module to fetch historical Bitcoin data against the USDT (Tether) from the bitcoincom exchange.
### Data Preprocessing
Split the dataset into training and testing subsets, ensuring that the test data remains chronologically after the training data to simulate real-world forecasting scenarios.
### Model Selection & Tuning
Utilize the GridSearchCV to find the best hyperparameters for multiple models: Random Forest, AdaBoost, XGBoost.
Use ensemble techniques such as Stacking and Voting Regressors to combine predictions from individual models and potentially improve accuracy.
### Visualization
Plot the true values vs. predicted values for each model to visually understand model performance.
Feature importance visualization is provided for tree-based models (Random Forest & XGBoost) to understand the key drivers of Bitcoin's price.
![Line Graph](https://github.com/Py-Fi-nance/Ensembles-in-Machine-Learning/blob/main/1.png)
### Performance Evaluation
Use the Mean Absolute Percentage Error (MAPE) metric to compare the forecasting accuracy of each model. The model with the lowest MAPE value typically offers better generalization for future data.
### Predicting Future Data
Use the best model to predict the closing price of Bitcoin for the next available date in the dataset.
## Key Features
Ensemble Techniques: This approach leverages ensemble methods like Bagging, Boosting, Stacking and Voting Regressors, combining different individual models to improve prediction accuracy.
Hyperparameter Tuning: Through GridSearchCV, the code ensures that the best possible hyperparameters are selected for each model, optimizing model performance.
Advanced Models: Use of sophisticated models like XGBoost and ensemble models showcases a state-of-the-art approach to forecasting.
## Data Visualization
A key aspect of this project is the use of advanced visualization techniques to understand the data's structure and relationships. Scatter plots, histograms, residual plots, and more are utilized.


## Predictive Modeling
We employ Linear Regression, a robust statistical modeling technique, to predict median housing prices based on various features such as median income, housing median age, average rooms, etc.
## Contributing
We welcome contributions to this project. To contribute:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.


## Contact Information
For any questions or inquiries, please contact support@pyfi.com - Subject: Github Repo Q, Linear-Trends-and-Linear-Regression.
For a full article walkthrough please visit > https://www.pyfi.com/blog < where you'll also be able to pick up a complimentary copy of the complete, Volume I text of our Machine Learning Edge Blueprint, a $49 value. This text will walk you through everything you need to get started coding Python for Finance
[![Follow on LinkedIn](https://img.shields.io/badge/Follow%20on-LinkedIn-blue?style=social&logo=linkedin)](https://www.linkedin.com/company/pyfi/)
