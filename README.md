# Wine Quality Prediction

This project aims to predict the quality of wine based on various chemical properties using machine learning algorithms. The wine dataset consists of both red and white wine data, with different features representing chemical properties. The goal is to classify wine into two categories: **'Good Quality'** (quality ≥ 7) and **'Bad Quality'** (quality < 7).

## Background

Wine quality assessment has traditionally been a subjective process based on expert tasters. However, with the availability of chemical data, it is now possible to automate this process using data-driven techniques. This project explores the use of machine learning to develop a model that can predict the quality of wine based on its chemical properties.

The dataset used in this project is a popular dataset available from the UCI Machine Learning Repository. It consists of two separate datasets: one for red wines and another for white wines. Each entry in the dataset corresponds to a wine sample, with features such as fixed acidity, volatile acidity, citric acid, residual sugar, and more, which are used to predict the quality of the wine.

## Problem Statement

The goal of this project is to build a classifier that can predict whether a wine is of "Good Quality" or "Bad Quality" based on its chemical properties. Specifically:

- **Good Quality**: Wines with a quality rating of 7 or higher.
- **Bad Quality**: Wines with a quality rating of less than 7.

## How This Helps Winemakers

The ability to accurately predict wine quality through data-driven methods can be highly beneficial for winemakers. By understanding the chemical properties that most influence wine quality, producers can:

- **Enhance Production**: Adjust their wine production processes based on predictive insights to improve overall quality.
- **Save Costs**: Identify subpar batches early in the production process, allowing for timely adjustments or reallocations to prevent unnecessary waste.
- **Consistency**: Achieve more consistent quality across batches by better understanding the key factors that affect wine quality.
- **Market Differentiation**: Winemakers can use data-driven insights to position their products more effectively in the competitive wine market by consistently delivering high-quality products.

## Models Used

The project uses the following machine learning models to classify wine quality:

1. **Logistic Regression**: A statistical model used for binary classification problems.
2. **Support Vector Machine (SVM)**: A supervised learning model used for classification tasks.
3. **Decision Tree**: A decision-making model that splits the data into subsets based on feature values.
4. **K-Nearest Neighbors (KNN)**: A simple, yet effective classification algorithm based on the proximity of data points.

### Hyperparameter Tuning
For each model, hyperparameter tuning is performed using `GridSearchCV` to find the best set of parameters that yield the highest accuracy. This ensures that the models perform optimally on the given dataset.

## Dataset

The dataset used in this project consists of two CSV files: one for red wines (`winequality-red.csv`) and another for white wines (`winequality-white.csv`). Each file contains the following features:

- **fixed acidity**: Fixed acidity content of the wine.
- **volatile acidity**: Volatile acidity content of the wine.
- **citric acid**: Citric acid content.
- **residual sugar**: Residual sugar content.
- **chlorides**: Chloride content.
- **free sulfur dioxide**: Free sulfur dioxide content.
- **total sulfur dioxide**: Total sulfur dioxide content.
- **density**: Density of the wine.
- **pH**: pH level.
- **sulphates**: Sulphates content.
- **alcohol**: Alcohol content.
- **quality**: Quality rating (integer scale from 0 to 10).

The dataset is used to predict whether a wine's quality is good or bad.

## Installation

To run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/wine-quality-prediction.git
cd wine-quality-prediction
