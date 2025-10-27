## Obesity_levels_AAI

## 📄 Overview
This project focuses on predicting obesity levels based on personal, lifestyle, and dietary attributes using various machine learning algorithms.
The goal is to analyze health patterns and classify individuals into categories such as Underweight, Normal Weight, Overweight, and Obese using Artificial Intelligence techniques.

## 🎯 Objectives
Understand the relationship between lifestyle factors (exercise, food habits, etc.) and obesity.
Build ML models to predict obesity levels accurately.
Compare multiple algorithms to identify the best-performing one.
Visualize key insights using data visualization libraries.

## 📊 Dataset
Source: UCI / Kaggle – Obesity Levels Dataset
Description: The dataset contains demographic, lifestyle, and dietary attributes.
Number of Records: ~2,000 samples
Features:
Gender, Age, Height, Weight
Family History of Overweight
Frequent Consumption of High-Calorie Food
Frequency of Physical Activity
Water Intake, Technology Use, Transportation
Obesity Level (Target Variable)

## 🧩 Project Workflow
## 1️⃣ Data Preprocessing
Loaded dataset using Pandas
Handled missing values and categorical encoding
Performed feature scaling using StandardScaler
Split data into training and testing sets

## 2️⃣ Exploratory Data Analysis (EDA)
Visualized distributions and correlations using:
matplotlib, seaborn
Detected patterns between BMI, activity, and obesity level
Checked feature importance and class imbalance

## 3️⃣ Model Building
Trained multiple supervised learning models, including:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
XGBoost / Gradient Boosting

## 4️⃣ Model Evaluation
Evaluated models based on:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Visualizations for model comparison and ROC curves are included in the notebook.

## 🧠 Results & Insights
Best Model: Random Forest Classifier (or whichever achieved highest accuracy)
Accuracy: ~95–98% (depending on tuning)
Key Insight: Lifestyle habits such as physical activity and calorie consumption are highly correlated with obesity levels.
