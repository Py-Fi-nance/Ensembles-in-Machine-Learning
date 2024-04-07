# Ensembles-in-Machine-Learning
Theoretical explanation and project forecasting Bitcoin price 

This repository showcases the use of state-of-the-art machine learning models for predicting Bitcoin's closing price in USD. By leveraging ensemble techniques, the tutorial provides a comprehensive approach to forecast cryptocurrency prices with higher accurracy. 

![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![Forks](https://img.shields.io/github/forks/Py-Fi-nance/Ensembles-in-Machine-Learning)](https://github.com/Py-Fi-nance/Ensembles-in-Machine-Learning/network)
[![Stars](https://img.shields.io/github/stars/Py-Fi-nance/Ensembles-in-Machine-Learning)](https://github.com/Py-Fi-nance/Ensembles-in-Machine-Learning/stargazers)

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

## Contributing
We welcome contributions to this project. To contribute:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.


## Contact Information
For any questions or inquiries, please contact support@pyfi.com - Subject: Github Repo Q, Ensembles-in-Machine-Learning.
For a full article walkthrough please visit > https://pyfi.com/blogs/articles/ensembles-in-machine-learning-applications-in-finance < and learn more about PyFi's award winning Python for Finance courses which have been trusted by the top financial institutions in the United States and Canada multiple years running here >> https://www.pyfi.com <<
[![Follow on LinkedIn](https://img.shields.io/badge/Follow%20on-LinkedIn-blue?style=social&logo=linkedin)](https://www.linkedin.com/company/pyfi/)
