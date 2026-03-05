# 🚗 Car Price Prediction using Machine Learning  


---
## 📖 Project Overview

This project aims to predict the selling price of used cars using machine learning techniques.  
The model is trained on various car features such as fuel type, transmission type, kilometers driven, present price, and manufacturing year.

The objective is to build a regression model that can accurately estimate resale value based on historical car data.

---

## 🎯 Objectives

- Perform data preprocessing and cleaning
- Convert categorical data into numerical format
- Train regression models for price prediction
- Evaluate model performance using metrics
- Identify important features affecting car prices
- Generate business insights from the model

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset Information

The dataset contains details about used cars, including:

- Car Name
- Year
- Selling Price (Target Variable)
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

---

## 🔍 Project Workflow

### 1️⃣ Data Loading
- Imported dataset using Pandas
- Checked dataset structure and summary

### 2️⃣ Data Preprocessing
- Checked for missing values
- Removed null values
- Encoded categorical variables using One-Hot Encoding

### 3️⃣ Train-Test Split
- Split data into 80% training and 20% testing
- Used random_state for reproducibility

### 4️⃣ Model Building

Two models were trained:

- Linear Regression
- Random Forest Regressor

### 5️⃣ Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

Random Forest performed better compared to Linear Regression.

---

## 📊 Results

| Model | R² Score |
|-------|----------|
| Linear Regression | ( 0.599702348194532) |
| Random Forest | (0.9673373873539192) |

Random Forest achieved better performance due to its ability to capture non-linear relationships.

---

## 📈 Feature Importance

Feature importance analysis revealed that:

- Present Price strongly influences Selling Price
- Manufacturing Year affects resale value
- Kilometers Driven impacts depreciation
- Fuel Type and Transmission also play a role

---

## 💡 Business Insights

- Cars with higher present price generally have higher resale value.
- Newer cars tend to sell at better prices.
- Lower mileage vehicles have higher market demand.
- Automatic transmission cars may influence resale trends.

---

## 🚀 How to Run This Project

1. Clone the repository
2. Install required libraries:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Python script:
   ```
   python car_price_prediction.py
   ```

---

## 📌 Conclusion

This project demonstrates the practical application of regression models in predicting used car prices.  
The Random Forest model provided better accuracy and can be used for real-world car price estimation systems.

---


