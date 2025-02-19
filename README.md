MACHINE LEARNING PROJECT

## Overview
This project implements various machine learning models for regression analysis, including:
- **Random Forest Regressor**
- **XGBoost Regressor**
- **Manual Linear Regression**
- **Hidden Markov Model (HMM)**

Each model is evaluated using standard metrics such as Mean Squared Error (MSE), R-Squared, Mean Error, Median Error, and Standard Deviation of Errors.

## Features
- **Data Preprocessing:** Scaling and normalization of features.
- **Regression Models:** Implementation and evaluation of different regression techniques.
- **Error Analysis:** Calculation of percentage errors and their statistical analysis.
- **Single Value Prediction:** Allows testing the models on specific data samples.
- **Visualization:** PCA for dimensionality reduction and explained variance analysis.

## Installation
Ensure you have the following dependencies installed:

```bash
pip install numpy pandas scikit-learn matplotlib plotly hmmlearn xgboost
```

## Usage
Run the Jupyter Notebook file to execute different models and analyze the results.

```bash
jupyter notebook "MACHINE LEARNING PROJECT.ipynb"
```

## Model Evaluations
### Random Forest Regressor
- **Mean Percentage Error:** Computed for both training and test sets.
- **Standard Deviation of Percentage Errors:** Measures variance in predictions.
- **R-Squared Score:** Indicates how well the model fits the data.

### XGBoost Regressor
- **Percentage Error Analysis:** Computes average, median, min, and max errors.
- **R-Squared Score:** Evaluates model performance.
- **Single Prediction Analysis:** Compares predicted and actual values.

### Manual Linear Regression
- **Mean Squared Error (MSE):** Measures average squared difference between predicted and actual values.
- **R-Squared Score:** Indicates the proportion of variance explained by the model.
- **Error Statistics:** Mean, median, and standard deviation of errors are computed.

## Example Output
```
Random Forest Regressor Evaluation (Percentage Errors):
Training Set Mean Percentage Error: 0.06%
Training Set Standard Deviation of Percentage Errors: 0.49%
Test Set Mean Percentage Error: 0.16%
Test Set Standard Deviation of Percentage Errors: 1.14%
```

## Contributing
Feel free to submit issues or pull requests to improve the project.
