# House_pricing_prediction
This repository contains code and resources for predicting house prices using machine learning with a focus on the XGBoost algorithm. The project aims to develop a robust model capable of accurately estimating house prices based on various features. The implementation includes data preprocessing, model training, evaluation, and prediction.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Notebooks](#notebooks)
  - [1. Data Processing](#1-data-processing)
  - [2. Data Splitting](#2-data-splitting)
  - [3. Model Training](#3-model-training)
  - [4. Model Evaluation](#4-model-evaluation)
- [Evaluation Metrics](#evaluation-metrics)
- [Contribution](#contribution)
- [License](#license)

## Introduction

The goal of this project is to develop a machine learning model capable of accurately predicting house prices based on various features. The XGBoost (eXtreme Gradient Boosting) algorithm is used for its effectiveness in handling structured data and providing high prediction accuracy.

## Installation

1. Clone the repository:


$ git clone (Copy link of project from the repository)

$ cd House_pricing_prediction


2. Install the required dependencies:


$ pip install -r requirements.txt


## Usage

To use this project, ensure you have the necessary modules installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost

These modules can be installed via pip:
(If sometimes there is error in graph visualization, try updating the matplotlib library)

$ pip install numpy pandas matplotlib seaborn scikit-learn xgboost

## Notebooks

The project is divided into four notebooks, each focusing on a specific aspect of the house pricing prediction process:

### 1. Data Processing

This notebook covers the preprocessing steps such as data cleaning, handling missing values, feature engineering, and data transformation.

### 2. Data Splitting

In this notebook, the dataset is split into training and testing sets to prepare for model training and evaluation.

### 3. Model Training

The model training notebook implements the XGBoost algorithm to train the machine learning model using the processed data.

### 4. Model Evaluation

This notebook evaluates the trained model's performance using evaluation metrics such as R squared error (R2 Score) and Mean Absolute Error (MAE).

## Evaluation Metrics

Two evaluation metrics are used to assess the performance of the model:

1. R squared error (R2 Score): Measures the proportion of the variance in the dependent variable that is predictable from the independent variables.
2. Mean Absolute Error (MAE): Represents the average of the absolute differences between the predicted and actual house prices.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

