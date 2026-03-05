# 📈 Sales Prediction using Python  

## 👩‍💻 About This Project

In this project, I worked on predicting product sales based on advertising expenditure on different platforms such as TV, Radio, and Newspaper.

The main objective was to understand how advertising impacts sales and to build a regression model that can predict future sales.

---

## 🛠 Tools & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset Information

The dataset contains:

- TV advertising budget
- Radio advertising budget
- Newspaper advertising budget
- Sales (Target Variable)

There were no missing values in the dataset.

---

## 🔎 Steps I Performed

### 1️⃣ Data Loading & Cleaning
- Loaded dataset using Pandas
- Checked for missing values
- Cleaned column names
- Removed unnecessary columns if needed

---

### 2️⃣ Feature Preparation
- Separated input features (TV, Radio, Newspaper)
- Selected Sales as the target variable
- Split data into training and testing sets (80% – 20%)

---

### 3️⃣ Model Building
- Used **Linear Regression** model
- Trained the model using training data
- Predicted sales using test data

---

### 4️⃣ Model Evaluation

The model was evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

### 📊 Model Performance

- MAE  : 1.465  
- RMSE : 1.788  
- R² Score : 0.898  

The R² score shows that the model explains around 89% of the variance in sales, which indicates good prediction performance.

---

### 5️⃣ Advertising Impact Analysis

- Created a correlation heatmap to understand relationships between advertising platforms and sales.
- Plotted Actual vs Predicted sales to visualize model accuracy.
- Analyzed feature importance using model coefficients.

From the model coefficients, TV and Radio advertising showed strong positive influence on sales compared to Newspaper advertising.

---

## 📈 Key Observations

- TV advertising has a strong impact on sales.
- Radio advertising also contributes significantly.
- Newspaper advertising has relatively lower influence.
- The linear regression model performs well for this dataset.

---

## ▶️ How to Run This Project

1. Clone the repository  
2. Install required libraries:

   ```
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. Run the Python file:

   ```
   python sales_prediction.py
   ```

## 🎯 Conclusion

This project helped me understand how advertising spending affects sales performance.  
By applying a regression model and analyzing correlations, I was able to build a predictive model with good accuracy.

It was a practical experience in regression modeling and business-oriented data analysis.
