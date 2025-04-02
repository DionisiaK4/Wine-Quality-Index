# Wine-Quality-Index

This project focuses on building machine learning models to predict the quality of red wine using various features of the wine, such as alcohol content, pH, residual sugar, and other chemical properties. The models are designed for both classification (predicting wine quality as a discrete label) and regression (predicting wine quality as a continuous value).


## Project Overview

The goal of this project is to develop and evaluate machine learning models to predict the quality of red wine. We use the Wine Quality Dataset from the UCI Machine Learning Repository, which contains attributes such as acidity, alcohol content, and sulphates, to predict the wine quality.

The project includes the following components:

Data Preprocessing: Handling missing values, scaling, encoding categorical data.

Exploratory Data Analysis (EDA): Analyzing the data to identify trends and patterns.

Model Training: Using both classification (for predicting quality as a class) and regression (for predicting quality as a numeric value) models.

Model Evaluation: Evaluating model performance using metrics such as accuracy, precision, recall (for classification) and RMSE, MAE (for regression).


## Dataset
The dataset used in this project is the Wine Quality Dataset from the UCI Machine Learning Repository. It contains various chemical properties of red wine and a quality score. The features include:

Fixed acidity,
Volatile acidity,
Citric acid,
Residual sugar,
Chlorides,
Free sulfur dioxide,
Total sulfur dioxide,
Density,
pH,
Sulphates,
Alcohol

The target variable is:

Quality: An integer value between 0 and 10 representing the quality of the wine.


## Usage

### Data Preprocessing: Load and clean the dataset, handling missing values and scaling features.

### Exploratory Data Analysis (EDA): Use matplotlib and seaborn to visualize relationships between features and the target variable.

### Model Training:

**Classification**: Train classification models (e.g., Decision Tree, Random Forest, Logistic Regression, etc.) to predict wine quality as a categorical class.

**Regression**: Train regression models (e.g., Linear Regression, Random Forest Regressor, XGBoost, etc.) to predict wine quality as a continuous value.

### Model Evaluation: Evaluate both classification and regression models using appropriate metrics (accuracy, precision, recall, F1-score for classification and RMSE, MAE for regression).


## Models
The following models are implemented in this project:

### Classification Models:

Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)

### Regression Models:

Linear Regression

Each model is evaluated using cross-validation and various performance metrics.


## Evaluation

For the classification task, we use the following metrics:

**Accuracy
Precision
Recall
F1-score**

For the regression task, we evaluate the model using:

**Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R-squared score**
