# 🏠 House Price Prediction System

This project implements a machine learning pipeline to predict house prices based on various categorical and numerical features from a housing dataset. It uses data preprocessing, exploratory data analysis (EDA), encoding, and multiple regression models to build an accurate predictive system.

---

## 📂 Project Overview

The notebook covers the full data science workflow:

- Data Loading from external CSV
- Exploratory Data Analysis (EDA)
- Handling Categorical Features (OneHotEncoding)
- Missing Value Treatment
- Feature Scaling (if applied)
- Dataset Splitting (Train/Test)
- Model Training and Evaluation

---

## 📊 Dataset

The dataset is based on historical housing data and includes features like:

- `MSZoning`, `LotConfig`, `BldgType`, `Exterior1st`
- `LotArea`, `YearBuilt`, `TotalBsmtSF`, `GrLivArea`
- And the target: `SalePrice`

🗂️ You can download the dataset here:  
[HousePricePrediction.xlsx](https://github.com/KasiR07/Housing-Price-Prediction/raw/main/HousePricePrediction.xlsx)

---

## 🧠 Algorithms Used

- **Linear Regression**
- **Random Forest Regressor**
- **Support Vector Machine (SVM)**

Model performance was evaluated using appropriate regression metrics such as MAE, RMSE, and R² score.

---

## 🛠️ Technologies & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook / Google Colab

---

## 📈 Visualizations

Categorical feature distributions were visualized using bar plots, helping to understand the dominant classes and data skewness in features like zoning, building type, and exterior materials.

<img width="1862" height="504" alt="image" src="https://github.com/user-attachments/assets/0a3e2632-ce6f-4e9b-86fa-db22fa73ce0b" />


---
