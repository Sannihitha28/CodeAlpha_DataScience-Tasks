# 📊 Unemployment Analysis in India using Python  

## 👩‍💻 About This Project

In this project, I analyzed unemployment data in India to understand trends over time, regional differences, and the impact of the Covid-19 period.

The main goal was to clean the dataset, explore patterns, and visualize unemployment changes using Python.

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Dataset Information

The dataset contains:

- Region (State name)
- Date
- Frequency (Monthly)
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area (Rural / Urban)

---

## 🔎 Steps I Performed

### 1️⃣ Data Loading & Understanding
- Loaded dataset using Pandas
- Checked first few rows
- Used `.info()` to understand data types
- Checked for missing values
- Cleaned column names

---

### 2️⃣ Data Cleaning
- Removed extra spaces in column names
- Converted the `Date` column into datetime format
- Sorted the dataset by date for proper time analysis

---

### 3️⃣ Overall Unemployment Trend
- Plotted unemployment rate over time
- Observed fluctuations across different months and years

---

### 4️⃣ Covid-19 Impact Analysis
- Filtered data between 2019 and 2021
- Plotted unemployment rate during this period
- This helped visualize how unemployment changed during Covid

---

### 5️⃣ Regional Analysis
- Calculated average unemployment rate for each region
- Identified states with higher and lower unemployment
- Visualized results using a bar chart

Some states showed consistently higher unemployment compared to others.

---

### 6️⃣ Monthly / Seasonal Trend Analysis
- Extracted month from Date column
- Calculated average unemployment by month
- Created a bar chart to observe seasonal patterns
- Created a heatmap (Region vs Month) for better comparison

This helped in identifying which months generally had higher unemployment.

---

## 📈 Key Observations

- Unemployment fluctuates significantly over time.
- Certain states show consistently higher unemployment rates.
- There was noticeable variation during the Covid period.
- Some months tend to have higher unemployment compared to others.

---

## ▶️ How to Run This Project

1. Clone the repository
2. Install required libraries:

   ```
    pip install pandas matplotlib seaborn
   ```

3. Run the Python file:

   ```
    python unemployment_analysis.py
   ```

---


## 🎯 Conclusion

This project helped me understand how unemployment varies across time and regions in India.  
Through visualization and grouping techniques, I was able to identify trends and patterns in the dataset.

It was a good practical experience in data cleaning, time-series analysis, and visualization using Python.
