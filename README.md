# House Price Prediction using Machine Learning

## Project Overview

This project predicts house prices using Machine Learning. It uses the Boston House Price dataset and the XGBoost Regressor algorithm.

The project performs data analysis, correlation analysis, model training, prediction, model evaluation, and visualization of actual versus predicted prices.

## Objectives

- Load and understand the house price dataset
- Perform basic data analysis
- Check missing values and dataset statistics
- Analyze correlations between features
- Split data into training and testing sets
- Train an XGBoost Regression model
- Predict house prices
- Evaluate model performance
- Visualize actual and predicted prices

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Project Workflow

Dataset
→ Data Loading
→ Data Analysis
→ Correlation Analysis
→ Train-Test Split
→ XGBoost Regression
→ Prediction
→ Model Evaluation
→ Visualization

## Machine Learning Model

The project uses XGBRegressor (XGBoost Regressor).

The data is divided into:
- 80% training data
- 20% testing data

## Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)

## Visualizations

- Correlation heatmap
- Actual Prices vs Predicted Prices scatter plot

## Project Structure

```text
House-Price-Prediction/
├── house_price.py
├── requirements.txt
└── README.md
```

## How to Run

### 1. Open the project folder

```bash
cd House-Price-Prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the project

```bash
python house_price.py
```

## Dataset

The Python program loads the Boston House Price dataset using `fetch_openml()`.

## Author

Vaibhavi Patil

TY B.Sc. Artificial Intelligence and Machine Learning
