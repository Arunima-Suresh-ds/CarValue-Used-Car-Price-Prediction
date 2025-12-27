
## CarValue -Used-Car-Price-Prediction



![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-FF9800)
![Models](https://img.shields.io/badge/Models-RandomForest%20%7C%20XGBoost-673AB7)
![Domain](https://img.shields.io/badge/Domain-Automotive%20Analytics-009688)
![Status](https://img.shields.io/badge/Status-Completed-2E7D32)

> End-to-end machine learning solution for predicting used car resale prices using advanced regression models and data-driven insights.

---

##  Project Overview
This project focuses on predicting the **selling price of used cars** using machine learning regression techniques.  
The dataset contains various car attributes such as manufacturing year, kilometers driven, fuel type, transmission, ownership history, and brand.

The goal is to analyze how these factors influence car prices and to build robust regression models that can accurately estimate the selling price of a used car.

---

##  Problem Statement
Used car prices vary significantly based on multiple factors such as age, mileage, fuel type, brand, and ownership.  
Manually estimating a fair resale value can be subjective and inaccurate.

This project aims to:
- Identify the most important factors affecting car prices
- Build machine learning models to predict selling prices accurately
- Compare different regression algorithms using evaluation metrics

---

###  Key Features
- `name` – Full car name (brand + model)
- `brand` – Extracted brand name from car name
- `year` – Manufacturing year
- `km_driven` – Total distance driven
- `fuel` – Fuel type (Petrol, Diesel, CNG, etc.)
- `seller_type` – Dealer or Individual
- `transmission` – Manual / Automatic
- `owner` – Ownership status
- `selling_price` – Target variable (price in INR)

---

##  Data Preprocessing
- Removed duplicate records
- Handled missing values
- Extracted **brand** from car name
- Created **Car_Age** feature from year
- Encoded categorical variables
- Performed feature scaling where required
- Applied log transformation on target variable to handle skewness

---

## Exploratory Data Analysis (EDA)
- Distribution analysis of selling prices
- Relationship between price and:
  - Car age
  - Kilometers driven
  - Fuel type
  - Transmission
  - Brand
- Correlation heatmap for numerical features
- Brand-wise average selling price analysis

---

##  Models Implemented
The following regression models were trained and evaluated:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost Regressor  

---

##  Model Evaluation Metrics
Models were evaluated using:
- **R² Score**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

---

##  Results
- Tree-based ensemble models performed significantly better than linear models
- Feature engineering and target transformation improved performance
- XGBoost and Random Forest achieved the highest R² scores
- Brand, car age, and kilometers driven were the most influential features

---

##  Tools & Technologies
- **Programming Language:** Python  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn  
  - xgboost  

---

##  Future Improvements
- Use larger and more diverse datasets
- Add location-based features
- Implement advanced hyperparameter tuning
- Try stacking and ensemble blending
- Deploy the model using Flask or FastAPI

---

##  Conclusion
This project demonstrates how machine learning can be used to predict used car prices effectively.  
With proper preprocessing, feature engineering, and model tuning, ensemble models can achieve strong predictive performance on real-world datasets.

---
