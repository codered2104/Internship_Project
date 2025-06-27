# 🛍️ Customer Lifetime Value (LTV) Prediction

This project focuses on predicting the **Lifetime Value (LTV)** of customers based on their historical purchase data using machine learning. It is part of a 2-week internship project to demonstrate skills in data analysis, feature engineering, and model building.

## 📌 Objective

To build a machine learning model that estimates the potential lifetime value of a customer to support marketing and customer retention strategies.

---

## 📂 Project Structure

project/
├── project.ipynb # Jupyter Notebook with code and visualizations
├── model.pkl # Trained Random Forest model
├── data.csv # Input data used for modeling
├── predictions.csv # (Optional) Predicted LTV values
├── internship_project.pdf # Final 2-page report
└── README.md # Project documentation (this file)

---

## 🧠 Tools & Technologies Used

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn (RandomForestRegressor)  
- Seaborn, Matplotlib  
- Pickle (for model persistence)

---

## 🔍 Steps Performed

1. **Data Loading & Cleaning**  
2. **Feature Engineering**  
   - Recency, Frequency, Monetary Value, AOV  
3. **Model Training**  
   - Random Forest Regressor  
4. **Evaluation**  
   - MAE, RMSE, R² Score  
5. **Customer Segmentation**  
   - Based on predicted LTV  
6. **Model Saving & Prediction Export**

---

## 📊 Results

- Model Evaluation:  
  - MAE: 1793.1012666543006  
  - RMSE: 10157.88416544955  
  - R² Score: -0.007221381972055907

- Customers segmented into **High**, **Medium**, and **Low** value tiers.

---

## 📝 Report

The full internship report is included in the repository as [`internship_project.pdf`](./internship_project.pdf), covering:

- Introduction  
- Tools Used  
- Project Pipeline  
- Model Performance  
- Conclusion  

---

## ✅ Acknowledgements

This project was completed as part of a **Data Analyst Internship** under the guidance and structure provided in the internship project document.

