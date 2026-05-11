Financial Fraud Detection (Work in Progress)

This project focuses on building a machine learning model to detect fraudulent financial transactions using structured transaction data.

Project Status

This project is currently under development.
Some components are still being optimized, including:

Handling missing values (NaN)
Feature engineering improvements
Model performance tuning (precision/recall balance)
Pipeline optimization with SMOTE and encoding
Dataset Features

The dataset includes:

Transaction details (amount, timestamp)
Behavioral metrics (velocity score, spending deviation)
Device and location data
Fraud labels
⚙️ Current Approach
Data preprocessing using pipelines
Handling categorical variables with OneHotEncoder
Imbalanced data handling using SMOTE
Model: Random Forest Classifier
Hyperparameter tuning with RandomizedSearchCV
📉 Current Challenges
Low precision for fraud detection
Imbalanced dataset (~3-4% fraud cases)
High computational cost during training
🚀 Next Steps
Improve feature engineering (behavioral patterns)
Try alternative models (XGBoost, LightGBM)
Optimize threshold tuning
Reduce training time
🛠️ Tech Stack
Python
Pandas / NumPy
Scikit-learn
Imbalanced-learn
📌 Notes

This project is part of my learning journey in Data Science and Machine Learning applied to financial fraud detection.

Feel free to explore and suggest improvements!
