AI/ML Internship Tasks — DevelopersHub
This repository contains my work for Task 1, Task 2, and Task 3 from the AI/ML Engineering Internship at DevelopersHub Corporation.

Intern Name: Ali Ghouse

🌸 Task 1: Exploring and Visualizing the Iris Dataset
Goal:
Understand the Iris flower dataset by looking at the data and creating simple graphs.

Dataset:

Comes with the Seaborn library

Columns: Sepal length, Sepal width, Petal length, Petal width, Species

What I Did:

Opened the dataset using Pandas

Checked size, column names, and sample rows

Looked at basic statistics

Made:

Scatter plots

Histograms

Box plots

Tools Used: Python, Pandas, Seaborn, Matplotlib

📈 Task 2: Predict Future Stock Prices
Goal:
Predict the next day’s closing price for a stock.

Dataset:

From Yahoo Finance (yfinance)

Stock: Apple (AAPL) — last 2 years

Features: Open, High, Low, Volume

Target: Next day’s Close price

What I Did:

Downloaded stock data

Created a column for the next day’s closing price

Trained a Random Forest Regressor

Compared predicted vs actual prices

Calculated Mean Squared Error (MSE)

Tools Used: Python, Pandas, Matplotlib, yfinance, Scikit-learn

❤️ Task 3: Heart Disease Prediction
Goal:
Predict if a person has heart disease based on health details.

Dataset:

From Kaggle: Heart Disease UCI Dataset

Target:

1 = Heart disease

0 = No heart disease

What I Did:

Opened the dataset

Split into training (80%) and testing (20%)

Trained two models:

Logistic Regression

Decision Tree

Checked:

Accuracy

Classification Report

Confusion Matrix

ROC Curve & AUC

Found important features using Decision Tree

Results:

Model	Accuracy	AUC
Logistic Regression	XX%	X.XX
Decision Tree	XX%	X.XX

Replace XX% and X.XX with your results.

Tools Used: Python, Pandas, Matplotlib, Scikit-learn

📂 Files
Task1_Iris_Exploration.ipynb

Task2_StockPrediction.ipynb

Task3_HeartDisease.ipynb

heart.csv (for Task 3)
