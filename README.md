📌 Red Wine Quality Prediction Using Machine Learning
🧠 Project Overview

This machine learning project predicts the quality of red wine using the well-known Red Wine Quality dataset from UCI Machine Learning / Kaggle. The goal is to analyze physicochemical properties (like acidity, alcohol, pH, etc.) and use them to estimate how good a wine is (quality score or class).

📦 Dataset

Source: Wine Quality Dataset (red wine) from UCI ML Repository / Kaggle.

Size: ~1,599 records with 11 chemical feature inputs and one target (quality).

Features include:

Fixed acidity

Volatile acidity

Citric acid

Residual sugar

Chlorides

Free/Total sulfur dioxide

Density

pH

Sulphates

Alcohol

Target: Quality score (scale ~0–10)

📌 Key Sections in This Repo
📊 1. Exploratory Data Analysis (EDA)

Inspect data distribution, null values.

Visualize feature relationships (plots, heatmaps).

Understand correlation with quality.

🛠️ 2. Data Preprocessing

Handle missing values or duplicates.

Scale / normalize features.

Convert target into a binary label (e.g., Good vs Bad) or multi-class.

🤖 3. Model Building

Test several machine learning models:

Logistic Regression

Decision Tree

Random Forest

SVM

XGBoost (often high performing)
Evaluate using metrics such as Accuracy, Precision, Recall, F1-Score.

📈 4. Model Evaluation

Compare models using confusion matrix and classification reports.

Choose the best model based on performance.

Visualize results.
