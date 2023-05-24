# Churn Rate Prediction Project

![Churn Rate](churn_rate_image.png)

Welcome to the Churn Rate Prediction project! This repository contains the code and resources for predicting customer churn, dissatisfaction, and inactivity for an online shop or product variety using linear regression algorithm and Long Short-Term Memory (LSTM) models.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data](#data)
6. [Model Architecture](#model-architecture)
7. [Evaluation](#evaluation)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

Customer churn, dissatisfaction, and inactivity are critical factors that can significantly impact the success and growth of any online business. This project aims to leverage machine learning techniques, specifically linear regression and LSTMs, to predict these actions accurately. By identifying customers who are likely to churn or become dissatisfied, businesses can proactively take measures to retain them and improve their experience.

## Project Overview

The Churn Rate Prediction project combines both traditional linear regression and LSTM models to achieve accurate predictions. The linear regression algorithm is used to capture the relationships between various features and the target variables, while the LSTM models leverage the temporal dependencies in sequential data to make predictions.

This repository provides the following key components:

- **Linear Regression Model**: Contains the code for building and training a linear regression model to predict churn rate, dissatisfaction, and inactivity.
- **LSTM Model**: Includes the code for constructing and training LSTM models to capture temporal patterns and predict customer behavior.
- **Data Preprocessing**: Contains scripts and utilities for preprocessing the data, handling missing values, scaling features, and preparing the data for model training.
- **Evaluation Metrics**: Includes functions to evaluate the performance of the models using appropriate metrics such as accuracy, precision, recall, and F1-score.
- **Notebooks**: Contains Jupyter notebooks demonstrating the step-by-step implementation of the models and their evaluation on example datasets.

## Installation

To use this project locally, follow these steps:

1. Clone this repository:

```bash
git clone https://github.com/your-username/Churn-Rate-Prediction.git
```

2. Navigate to the project directory:

```bash
cd Churn-Rate-Prediction
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To train and evaluate the models on your own dataset, follow the steps below:

1. Prepare your data by following the instructions provided in the [Data](#data) section.
2. Modify the relevant configuration files or scripts to customize the model settings, such as hyperparameters, input features, and target variables.
3. Execute the training script to train the models:

```bash
python train.py
```

4. Evaluate the trained models using the evaluation script:

```bash
python evaluate.py
```

5. Adjust the models, data preprocessing steps, or hyperparameters as needed to improve performance.

## Data

To train the churn rate prediction models, you need labeled datasets that include features relevant to customer behavior, churn, dissatisfaction, and inactivity. The datasets should be preprocessed and formatted properly before training the models.

In this repository, we provide an example dataset named `customer_data.csv`, which you can use to explore the code and test the implementation. However, for best results, we recommend using your own domain-specific data to train the models.

The `customer_data.csv` file should have the following columns:

- `customer_id`: A unique identifier for each customer.
- `age`: The age of the customer
