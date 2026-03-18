# 🌍 Global Payment Speed Inequality Analysis

## 📌 Overview

This project analyzes global disparities in electronic payment processing times using World Bank Enterprise Survey data.

The goal is to understand:

* How fast businesses receive payments across countries
* Whether global payment systems are improving
* The level of inequality in financial infrastructure

---

## 📊 Dataset

* **Source**: World Bank Enterprise Surveys
* **Indicator**: Days to receive the main type of electronic payment
* **Coverage**: 125 economies (2021–2025)
* **Unit**: Days

🔗 https://data360.worldbank.org/en/indicator/WB_ES_T_BREADY_FIN29

Licensed under **CC BY 4.0**

---

## ⚙️ Methodology

### 1. Data Cleaning

* Removed metadata rows (e.g., "CCYY")
* Selected relevant columns:

  * Country
  * Year
  * Payment days

### 2. Aggregation

* Grouped data by country and year
* Calculated mean payment time

### 3. Analysis

* Global trend visualization
* Country ranking (fastest vs slowest)
* Distribution analysis (histogram)
* Outlier detection (boxplot)
* Inequality measurement (IQR)

---

## 📈 Key Findings

### 🚀 Global Trend

Payment processing times are decreasing globally, indicating improvements in digital financial systems.

---

### ⚖️ Inequality

Payment speed is highly uneven across countries.

* Most countries: **0.5–2 days**
* Outliers: **5–17+ days**

---

### 🧠 Interpretation

This suggests:

* Strong digital infrastructure in some countries
* Significant structural inefficiencies in others

---

## 📊 Example Visualizations

* Global trend line
* Distribution histogram
* Boxplot (outliers)
* Country rankings

---

## 🧠 Key Insight

> While most countries process payments quickly, a small number of countries experience extreme delays, highlighting global inequality in financial infrastructure.

---

## ⚠️ Limitations

* Data is self-reported by firms
* Coverage varies across countries
* Some extreme values may reflect reporting bias

---

## 🚀 Future Work

* Integrate GDP, internet usage, and banking data
* Build predictive models
* Create a global “Payment Efficiency Index”

---

## 👨‍💻 Author

Burak ARI

---
