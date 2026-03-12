# ARTI406 – Machine Learning 🤖

**University:** Imam Abdulrahman Bin Faisal University (IAU)  
**College:** CCSIT - Computer Science & AI  

## 👤 Student Information
* **Name:** Khalid Waleed Alhilal | **ID:** 2230000788 | **Section:** 8ma02

---

## 📂 Lab 2 Overview & Status

| Lab | Topic | Status | Files |
| :--- | :--- | :--- | :--- |
| **Lab 2** | Data Quality Assessment & Preprocessing | ✅ Completed | `LAB2.ipynb`, `data/laptops.csv` |

---

## 💾 Dataset Description
Continuing with the **Laptop Prices Dataset** from Lab 1. In this lab, the focus shifts from exploration to **cleaning and preprocessing** the data to make it machine-learning-ready.

* **Target Variable:** `Final Price` 
* **Key Numeric Features Processed:** `RAM`, `Storage`, `Screen`, `Final Price`.

---

## 📗 Implementation Details

### ✅ Task 1: Identify Data Quality Issues
* Scanned the dataset for missing values, duplicate records, and checked data types to ensure consistency.

### ✅ Task 2: Apply Missing Value Strategy
* **Strategy:** Median Imputation.
* **Reasoning:** The median is highly robust against outliers compared to the mean, making it the safest mathematical choice for hardware attributes.

### ✅ Task 3: Detect and Handle Outliers
* **Method:** Used the Interquartile Range (IQR) method.
* **Action:** Identified extreme values in the `Final Price` column (high-end/luxury laptops) and capped them at the upper bound to prevent model distortion.

### ✅ Task 4: Normalization & Scaling
* **Min-Max Scaling:** Applied to the `Storage` feature to compress its range strictly between 0 and 1.
* **Z-score Standardization:** Applied to the `RAM` feature to center the distribution around a mean of 0 with a standard deviation of 1.

### ✅ Task 5: PCA & Explained Variance
* Applied Principal Component Analysis (PCA) to the standardized numeric features to reduce dimensionality.
* Interpreted the **Explained Variance Ratio** to understand how much dataset information is captured by the first two Principal Components (PC1 and PC2).

---

## 🚀 How to Run
1. Ensure dependencies are installed via the root `requirements.txt`.
2. Open `LAB2.ipynb` and run all cells sequentially.