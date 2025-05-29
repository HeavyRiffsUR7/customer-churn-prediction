# Customer Churn Prediction using Machine Learning
This project builds a Machine Learning pipeline to predict customer churn based on real-world telecommunications data. It prioritizes recall, ensuring that customers likely to leave are successfully identified for retention efforts.

## Key Highlights
End-to-end pipeline: from cleaning and feature engineering to model evaluation and deployment.

Emphasis on recall to reduce false negatives.

Logistic Regression selected after comparing multiple models (SVM, KNN, RandomForest, etc.).

Custom decision threshold to boost recall from 78% to 86%.

Final model packaged in a reusable Scikit-learn pipeline.

## Dataset Features
The dataset contains 21 features such as:

Demographics (gender, senior citizen, dependents)

Services subscribed (Internet, Streaming, TechSupport)

Contract and payment details

Target variable: Churn (Yes/No)

## Tools & Libraries
Python · Pandas · NumPy · Scikit-learn · Seaborn · Matplotlib




