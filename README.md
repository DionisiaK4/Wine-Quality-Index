# Wine-Quality-Index

## Project Overview

This project was developed as part of the "Introduction to Machine Learning and MLOps" lab lecture in the Software Engineering in Practice course at the Athens University of Economics and Business (AUEB).

It focuses on leveraging machine learning models to predict the quality of red wine using various features of the wine, such as alcohol content, pH, residual sugar, and other chemical properties. The models used in this example are for both classification (predicting wine quality as a discrete label) and regression (predicting wine quality as an integer value).



## Dataset

The dataset used in this project is the Wine Quality Dataset from the UCI Machine Learning Repository. You can download it from [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009/data). 

It contains various chemical properties of red wine and a quality score (from 0 to 10)
- The features are 11 and include: Fixed acidity, Volatile acidity, Citric acid, Residual sugar, Chlorides, Free sulfur dioxide, Total sulfur dioxide, Density, pH, Sulphates, Alcohol

- The target variable is: quality of the wine as an integer value between 0 and 10.


## Models


### Models Selection

**Regression Models**: to predict wine quality as an integer value.
1. Linear Regression
2. Random Forest Regressor

**Classification Models**: to predict wine quality as a categorical class(low, medium, high quality). To convert the numeric quality values of the dataset into categorical classes, we discretized them into three bins (0–4, 4–6, and 6–10) based on their frequency distribution.

1. Logistic Regression
2. Random Forest Classifier


<br>

### Models Evaluation

For the **regression** task, we use the following performance metrics:
- Mean Squared Error
- R-squared Score


For the **classification** task, we use the following performance metrics:
- Accuracy
- Precision
- Recall
-F1-score

## Getting Started

### Prerequisites

To run this notebook, you'll need the following:
- Python 3.6 or later
- VScode
- The following Python packages: `pandas`, `sklearn`

<br>

### Installation

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/DionisiaK4/Wine-Quality-Index.git
   ```
2. Install the required Python packages using:
   ```
   pip install pandas scikit-learn
   ```
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009/data) and place it in main directory as the other files under the name `winequality-red.csv`.

<br>

### Running the Notebook

You suggest running the notebook using VScode for simplicity.

1. Navigate to the cloned repository's directory.
2. Open the `Wine Quality ML Practical Example.ipynb` notebook.
4. Run the cells in order to execute the separate parts of code.