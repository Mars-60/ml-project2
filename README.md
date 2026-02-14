# 🪙 Gold Price Prediction Web App

> A simple machine learning web application that predicts gold prices using a Random Forest model and Streamlit.

This project demonstrates an end-to-end ML workflow — from data preprocessing and model training to building an interactive web app for displaying model performance.

---

## 🧠 Skills & Technologies Demonstrated

**Programming & Libraries**
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Streamlit
- Pillow

**Machine Learning Concepts**
- Data preprocessing
- Feature selection
- Train/Test split
- Random Forest Regression
- Model evaluation using R² score

**Web App**
- Streamlit dashboard

---

## 📊 Dataset

Dataset used: **gld_price_data.csv**

The dataset contains financial indicators used to predict gold prices such as:
- Market indices  
- Currency values  
- Commodity indicators  

**Target variable:**  
`GLD → Gold price`

---

## ✨ Project Workflow

### 1️⃣ Data Loading & Preprocessing
- Loaded dataset using Pandas
- Removed unnecessary columns (Date)
- Split dataset into features (X) and target (Y)

### 2️⃣ Train/Test Split
Data split into:
- 80% Training data
- 20% Testing data

### 3️⃣ Model Training — Random Forest Regressor
Random Forest is used because:
- Handles non-linear relationships well
- Reduces overfitting
- Works well for financial datasets

### 4️⃣ Model Evaluation
Predictions are evaluated using **R² Score**, which measures how well the model explains the variance in gold prices.

### 5️⃣ Streamlit Web App
A simple interactive dashboard was built using Streamlit to:
- Display dataset preview
- Show model performance score
- Provide a basic ML visualization interface
---
Run the app locally to see results in a browser.
