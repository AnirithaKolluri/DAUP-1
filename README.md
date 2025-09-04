# Airplane Price Prediction

## 📌 Course Information
This is my **3-2 Semester Project** for the course **DAUP (Data Analysis Using Python)**.  
The project focuses on applying data analysis and machine learning techniques to predict airplane prices using structured tabular data.

---

## 🎯 Project Title
**Airplane Price Prediction using Machine Learning Models**

---

## 📖 Project Description
The project aims to predict airplane prices based on multiple technical and operational parameters such as manufacturing year, engine type, passenger capacity, range, fuel consumption, and maintenance costs.  
The dataset was preprocessed, analyzed, and visualized to identify key factors influencing airplane prices. Multiple machine learning models were implemented and evaluated to achieve accurate predictions.  

---

## 🏆 Project Goals
- Perform **data preprocessing** (handling missing values, encoding, scaling).
- Conduct **Exploratory Data Analysis (EDA)** using statistical and visualization techniques.
- Train and evaluate different **regression models** for price prediction.
- Compare models based on accuracy and error metrics.
- Identify the **best-performing model** for airplane price prediction.

---

## 📊 Dataset Information
- Dataset Type: **Regression** (predicting continuous airplane prices).  
- Source: Public aviation records compiled into structured tabular format.  
- Features: Aircraft age, passenger capacity, operational range, fuel consumption per hour, maintenance cost per hour, engine type, number of engines, manufacturing year, sales region, etc.  
- Rows: ~1,000+ records  
- Preprocessing steps included column renaming, handling missing values, and feature encoding.

---

## 🛠️ Tools and Libraries Used
- **Python**  
- **Pandas**, **NumPy** – Data handling and preprocessing  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning models and evaluation  
- **Jupyter Notebook** – Implementation and documentation  

---

## 📈 Results
Three machine learning regression models were trained and evaluated:

- **Linear Regression**  
  - MAE: 50,741,962.01  
  - R² Score: **0.91**

- **Random Forest Regressor**  
  - MAE: 20,496,300.38  
  - R² Score: **0.97**

- **Gradient Boosting Regressor**  
  - MAE: 18,850,337.37  
  - R² Score: **0.98**

✅ **Best Model:** Gradient Boosting (Highest accuracy with R² = 0.98 and lowest error)  

---

## 🔗 Kaggle Dataset
The dataset used in this project is available here:  
[Airplane Price Dataset – Kaggle](https://www.kaggle.com/datasets/tanishqqqq/air-plane-price-dataset)

---
