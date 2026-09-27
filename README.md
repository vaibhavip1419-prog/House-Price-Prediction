

# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using **Machine Learning**. The project uses the Boston House Price dataset and applies the **XGBoost Regressor** algorithm to predict house prices.

The project also performs data analysis and visualization to understand the relationship between different features and house prices.

## 🎯 Objectives

* Load and understand the house price dataset.
* Perform basic data analysis.
* Check missing values and dataset statistics.
* Analyze correlations between different features.
* Split the data into training and testing datasets.
* Train an XGBoost Regression model.
* Predict house prices.
* Evaluate model performance.
* Compare actual and predicted prices using visualization.

## 🛠️ Technologies Used

* **Python**
* **NumPy** – Numerical operations
* **Pandas** – Data handling and analysis
* **Matplotlib** – Data visualization
* **Seaborn** – Heatmap and visualization
* **Scikit-learn** – Data splitting and evaluation metrics
* **XGBoost** – Machine learning regression model

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
DataFrame Creation
   ↓
Data Analysis
   ↓
Correlation Analysis
   ↓
Train-Test Split
   ↓
XGBoost Regression
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Actual vs Predicted Visualization
```

## 🤖 Machine Learning Model

The project uses **XGBRegressor (XGBoost Regressor)** for house price prediction.

The data is divided into:

* **80% Training Data**
* **20% Testing Data**

The model is trained using the training data and then tested using unseen test data.

## 📊 Model Evaluation

The following evaluation metrics are used:

### R² Score

Measures how well the model explains the variation in the target values.

### Mean Absolute Error (MAE)

Measures the average absolute difference between the actual and predicted values.

## 📈 Visualization

A scatter plot is created to compare:

* **Actual Prices**
* **Predicted Prices**

A correlation heatmap is also used to understand relationships between dataset features.

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── house_price.py
├── requirements.txt
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd House-Price-Prediction
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Python file

```bash
python house_price.py
```

## 📌 Dataset

The project code loads the Boston House Price dataset using `fetch_openml()`.

## 👩‍💻 Author

**Vaibhavi Patil**

TY B.Sc. Artificial Intelligence and Machine Learning
