# 📊 Los Angeles Crime Analysis & Predictive Modeling

## 📆 Project Details
📅 **Date:** September 2024  
👨‍💻 **Author:** Nirmalkumar Thirupallikrishnan Kesavan, Mohammed Ibrahim LNU  
🏛️ **Institution:** Northeastern University, Boston MA  

## 🖥️ Tech Stack
- **Programming Language:** Python 🐍
- **Libraries:** Pandas, Matplotlib, Seaborn, NumPy, Statsmodels
- **Machine Learning:** ARIMA (Time-Series Forecasting)
- **Data Sources:** LA Crime Dataset (2020-Present)

## 📌 Project Overview
This project explores crime trends in Los Angeles from 2020 to 2024 using **data analytics, visualization, and predictive modeling**. We analyze crime patterns across time, locations, and demographics, examining the impact of COVID-19 on crime rates and using the **ARIMA model** for forecasting future crime trends.

🔍 **Key Insights:**
- A **25% crime reduction** was observed during COVID-19 lockdowns.
- **Vehicle theft** is the most common crime (110,804 cases).
- Crime is highest in **Central LA** (~70,000 incidents).
- Predictive modeling suggests **continued decline** in crime rates through 2025.

---

## 📂 Project Structure
```
📁 Los_Angeles_Crime_Analysis
 ├── 📊 Data Preprocessing
 ├── 📈 Exploratory Data Analysis (EDA)
 ├── 🔍 Crime Trends & Visualization
 ├── 🤖 Predictive Modeling (ARIMA Forecasting)
 ├── 📄 Report & Findings
```

---

## 📊 Data Processing & Methodology

### 📥 1. Data Acquisition
- The dataset was obtained from **Los Angeles crime reports (2020-Present)** in CSV format.
- Loaded using `pandas` into a structured DataFrame.

### 🔍 2. Data Inspection
- Used `.head()` to preview data.
- Checked data types using `.dtypes`.
- Verified missing values and inconsistencies.

### 🧹 3. Data Cleaning
- **Handled missing values:**
  - Filled categorical nulls with 'Unknown'.
  - Dropped highly incomplete columns (e.g., `Crm Cd 3, Crm Cd 4`).
  - Used mean imputation for numerical columns.
- **Removed duplicates** using `duplicated()`.
- **Converted time formats** to ensure accurate time-series analysis.

---

## 📈 Exploratory Data Analysis (EDA)

### 📊 Overall Crime Trends
- Crime peaked in **2022 (235,152 cases)** before declining in **2023 & 2024**.
- A **steep decline** in crime rates in early 2024.

### 📅 Seasonal Crime Patterns
- Crime was **highest in January** and gradually declined towards December.
- Most crimes occurred on **Fridays & Saturdays**.

### 🔎 Crime Type Analysis
- **Top 5 common crimes:**
  1. **Vehicle Theft** (110,804 cases)
  2. **Battery - Simple Assault** (74,688 cases)
  3. **Burglary from Vehicle** (61,324 cases)
  4. **Identity Theft** (48,392 cases)
  5. **Vandalism** (42,108 cases)
- **Theft-related crimes** dominate the dataset.

### 📍 Regional Crime Analysis
- **Highest crime rates:** Central LA, 77th Street, Pacific, Southwest, Hollywood.
- **Lowest crime rates:** Mission, Hollenbeck, Foothill.

### ⚠️ Correlation Analysis
- **No strong correlations** between crime types and victim age.
- **Latitude and longitude** had expected negative correlation (-1.00).

### 📉 Impact of COVID-19
- **Crime dropped by 25%** during lockdown periods.
- **Waves 1 & 2 saw the biggest crime reductions**, while **Wave 3 saw a sharp increase**.

---

## 🤖 Predictive Modeling (ARIMA Forecasting)
- Used **ARIMA (1,1,1)** to predict crime trends.
- Forecasted crime reduction **from 6,777 (Oct 2024) to 5,768 (Sep 2025)**.
- **Projected a 14.89% decline** in crime rates using ARIMA modeling.
- **Confidence interval widens over time**, reflecting increasing uncertainty.
- Used **ARIMA (1,1,1)** to predict crime trends.
- Forecasted crime reduction **from 6,777 (Oct 2024) to 5,768 (Sep 2025)**.
- **Confidence interval widens over time**, reflecting increasing uncertainty.

### 🔮 Future Crime Trend Forecast
![Crime Forecasting](Crime%20Forecasting%20Visualization%20(1).png)

---

## 📜 Full Report
📄 Read the full **Los Angeles Crime Analysis and Predictive Modeling Report** [here](Los%20Angeles%20Crime%20Analysis%20and%20Predictive%20Modeling-%20Project%20Report%20(1).pdf).

---

## ⭐ Contribute & Connect
💡 If you find this useful, star ⭐ this repo!  

🔗 LinkedIn: [Nirmalkumar Thirupallikrishnan Kesavan](https://www.linkedin.com/in/nirmalkumartk/)  
🔗 GitHub: [NirmalKumar31](https://github.com/NirmalKumar31)  

📩 **For questions, feel free to reach out!** 🚀

