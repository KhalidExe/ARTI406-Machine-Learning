# ARTI406 – Machine Learning 🤖

**University:** Imam Abdulrahman Bin Faisal University (IAU)  
**College:** CCSIT - AI  

## 👤 Student Information
* **Name:** Khalid Waleed Alhilal | **ID:** 2230000788 | **Section:** 8ma02

---

## 📂 Labs Overview & Status

| Lab | Topic | Status | Location |
| :--- | :--- | :--- | :--- |
| **Lab 1** | EDA & Data Exploration | ✅ Completed | [📂 View Lab 1](./Lab1/) |
| **Lab 2** | Data Quality Assessment & Preprocessing | ✅ Completed | [📂 View Lab 2](./Lab2/) |
| **Lab 3** | (Upcoming Topic) | ⏳ Pending | - |

---

## 📗 Implementation Details

### ✅ Lab 2: Data Quality Assessment & Preprocessing
* **Dataset:** Laptop Prices Dataset (Continued).
* **Missing Values:** Addressed missing data using **Median Imputation** for numeric columns and **Mode Imputation** for categorical columns (like GPU/Storage type).
* **Outlier Handling:** Detected and capped extreme values in the `Final Price` column using the **Interquartile Range (IQR)** method.
* **Normalization & Scaling:** Applied **Min-Max Scaling** to `Storage` and **Z-score Standardization** to `RAM`.
* **Dimensionality Reduction:** Applied **PCA (Principal Component Analysis)** on numerical features and analyzed the Explained Variance Ratio.

### ✅ Lab 1: Exploratory Data Analysis (EDA)
* **Dataset:** Laptop Prices Dataset (Specifications & Prices).
* **Cleaning:** Handled missing values, cleaned RAM/Weight columns, and standardized data types.
* **Visualization:** Analyzed Price distribution, Brand market share, and correlation between RAM/Storage and Price.
* **Tools:** Used Pandas for manipulation, Matplotlib & Seaborn for plotting.