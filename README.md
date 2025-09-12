AI/ML Internship Tasks — DevelopersHub
This repository contains my work for Task 1, Task 2,  Task 3,Task 4 and Task 6 from the AI/ML Engineering Internship at DevelopersHub Corporation.

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
Task 4 — Health Chatbot

Description:
In this task, I developed a safe conversational health assistant. The chatbot uses a small chat-tuned language model to respond to user health-related queries in natural language. It also includes conversation memory, allowing it to understand context from the last few turns. A safety layer was added to ensure the chatbot does not provide diagnoses, prescriptions, or unsafe advice. Instead, it gives general information and always appends a safety disclaimer directing the user to professional help or emergency services if required.

Key Features:

Built using HuggingFace transformers pipeline.

Maintains short-term memory (remembers last 5 user–bot exchanges).

Filters unsafe queries (diagnosis, medicine, self-harm).

Always outputs “I’m not a doctor. General info only. Contact emergency services if urgent.”

Example queries: causes of headaches, avoiding dehydration, healthy habits.

📌 Task 6 — House Price Prediction

Description:
In this task, I developed a machine learning regression model to predict house prices based on features like square footage, number of bedrooms, bathrooms, and city. The project demonstrates a full ML workflow: data preparation, preprocessing, model training, evaluation, visualization, and saving trained models for later use.

Key Features:

Dataset: synthetic data generated (or user-provided data.csv).

Preprocessing: numerical scaling + categorical encoding (cities).

Models: Linear Regression (baseline) and Gradient Boosting Regressor (advanced).

Evaluation: MAE (Mean Absolute Error) and RMSE (Root Mean Squared Error).

Visualization: scatter plot of actual vs predicted prices.

Artifacts: trained models saved as .joblib files for reuse.

Custom prediction example: house with 2000 sqft, 3 bedrooms, 2 bathrooms in Karach

📂 Files
Task1_Iris_Exploration.ipynb

Task2_StockPrediction.ipynb

Task3_HeartDisease.ipynb


