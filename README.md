# Bank Customer Churn Prediction (Machine Learning)

## 🎯 Project Overview
Built an end-to-end **Supervised Machine Learning** classification model to predict whether a bank customer will leave the bank (`Exited = 1`) or stay (`Exited = 0`). Identifying high-risk customers early enables banks to take proactive retention measures.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn (`RandomForestClassifier`, `train_test_split`, `accuracy_score`, `confusion_matrix`, `classification_report`)

## ⚙️ Workflow & Methodology
1. **Data Cleaning & Feature Selection:** Removed irrelevant identifier columns (`RowNumber`, `CustomerId`, `Surname`) to prevent model bias.
2. **Feature Encoding:** Converted categorical text data into numerical format using binary mapping (`Gender`) and **One-Hot Encoding** (`Geography`).
3. **Train-Test Split:** Split the 10,000-customer dataset into **80% Training** and **20% Testing** sets.
4. **Model Training & Evaluation:** Trained a **Random Forest Classifier** achieving **86.75% accuracy** on unseen test data.

## 📊 Key Results & Business Insights
- **Model Accuracy:** **86.75%** (correctly predicted 1,735 out of 2,000 test customers).
- **Key Churn Drivers:** Feature importance analysis revealed that **Customer Age**, **Account Balance**, and **Number of Products** are the strongest predictors of customer churn.
