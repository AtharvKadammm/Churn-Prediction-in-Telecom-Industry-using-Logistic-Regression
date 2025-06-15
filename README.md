# 👨🏻‍💻 Churn Prediction in Telecom Industry using Logistic Regression

## 📖 Overview

This project focuses on predicting customer churn in the telecom industry using machine learning techniques, primarily Logistic Regression. Telecom companies lose millions due to customer churn every month. With increasing competition, predicting customer attrition has become crucial for retaining valuable subscribers.

By analyzing customer behavior, billing information, subscription details, and usage patterns, the model identifies key factors influencing churn. The aim is to assist telecom providers in proactive retention strategies and customer experience improvements.

---

## 📊 Problem Statement

> According to European Business Review, telecommunication providers lose close to $65 million monthly due to customer churn. This project builds a predictive model to classify whether a customer is likely to churn, enabling telecom companies to:

- Optimize subscription plans.
- Target at-risk customers.
- Improve customer service quality.
- Increase profitability.

---

## 🔧 Techniques Used

- Exploratory Data Analysis (EDA)
- Data Preprocessing & Cleaning
- Feature Engineering
- Label Encoding
- Logistic Regression (Supervised Classification)
- Model Evaluation: Confusion Matrix, Accuracy, Precision, Recall, F1-score

---

## 📂 Dataset

- The dataset includes billing history, subscription plans, usage metrics, network consumption, and contract details.
- Files used:
  - `churn-bigml-20.csv`
  - `churn-bigml-80.csv`

---

## 🔬 Model Pipeline

1️⃣ Load and clean data  
2️⃣ Encode categorical features  
3️⃣ Perform EDA and correlation analysis  
4️⃣ Build logistic regression model  
5️⃣ Evaluate model performance  
6️⃣ Interpret feature importance

---

## 📈 Results

- Built a baseline Logistic Regression model.
- Achieved initial accuracy with interpretable results.
- Identified key drivers of churn: contract type, service quality, monthly charges, and tenure.

---

## 💡 Key Learnings

- Logistic Regression works well for early churn modeling.
- Contract length and payment type strongly influence churn likelihood.
- Data quality and feature engineering are critical for model performance.

---

## 💻 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Project Structure

- churn-bigml-20.csv  (Dataset part 1)
- churn-bigml-80.csv  (Dataset part 2)
- Churn Prediction in Telecom Industry using Logistic Regression.ipynb  (Main notebook)
- README.md  (Project documentation)

## 🚀 Future Improvements

- Apply advanced models: Random Forest, XGBoost, Ensemble Models.
- Perform hyperparameter tuning.
- Handle class imbalance with SMOTE.
- Deploy model via Flask/Streamlit for business use.

---

## 🔗 Useful Resources

- [European Business Review](https://www.europeanbusinessreview.com)
- [BigML Churn Dataset](https://bigml.com/user/churn-data)

---

## 🙌 Author

Atharv Kadam

---

⭐ **If you like this project, please consider giving it a star!**
