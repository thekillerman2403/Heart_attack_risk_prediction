# ❤️ Heart Attack Risk Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting the **risk of heart attack** using supervised machine learning techniques. By analyzing patient health parameters, the model classifies whether an individual is at risk, helping demonstrate how data-driven methods can support **early medical risk assessment**.

The project is implemented entirely in **Python** using a **Google Colab notebook**, making it easy to reproduce and extend.

---

## 🎯 Objectives
- Understand and analyze medical health data related to heart disease
- Perform data preprocessing and exploratory data analysis (EDA)
- Build and evaluate machine learning classification models
- Compare model performance using standard evaluation metrics
- Interpret results to understand key contributing health factors

---

## 🧠 Dataset Description
The dataset consists of clinical and demographic attributes such as:
- Age
- Sex
- Chest pain type
- Blood pressure
- Cholesterol level
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate achieved
- Exercise-induced angina
- Target variable (Heart attack risk)

> **Target:**  
> `1` → High risk of heart attack  
> `0` → Low / No risk

---

## 🔧 Technologies & Libraries Used
- **Python**
- **Google Colab**
- **NumPy** – numerical operations  
- **Pandas** – data manipulation  
- **Matplotlib & Seaborn** – data visualization  
- **Scikit-learn** – ML models and evaluation  

---

## 🛠️ Methodology
1. **Data Loading & Cleaning**
   - Handled missing values
   - Checked data types and distributions

2. **Exploratory Data Analysis (EDA)**
   - Feature distribution analysis
   - Correlation heatmaps
   - Class balance inspection

3. **Feature Selection & Scaling**
   - Identified relevant attributes
   - Standardized features where required

4. **Model Building**
   - Trained machine learning classifiers
   - Split data into training and testing sets

5. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion matrix

---

## 📊 Results
- The trained model demonstrates **good predictive performance** on unseen data
- Certain features like **age, chest pain type, and cholesterol levels** significantly influence predictions
- Evaluation metrics indicate the model is suitable for **binary risk classification**

---
