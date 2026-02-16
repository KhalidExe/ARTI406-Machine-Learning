# ARTI406 – Machine Learning 🤖

**University:** Imam Abdulrahman Bin Faisal University (IAU)  
**College:** CCSIT - Computer Science & AI  

## 👤 Student Information
* **Name:** Khalid Waleed Alhilal | **ID:** 2230000788 | **Section:** 8ma02

---

## 📂 Lab 1 Overview & Status

| Lab | Topic | Status | Files |
| :--- | :--- | :--- | :--- |
| **Lab 1** | Exploratory Data Analysis (EDA) | ✅ Completed | `LAB1.ipynb`, `data/laptops.csv` |

---

## 💾 Dataset Description
For this assignment, I selected the **Laptop Prices Dataset** to analyze how different hardware specifications influence the final cost of a device.

* **Target Variable:** `Final Price` (The price of the laptop in Euros).
* **Key Features:**
    * **Brand:** Manufacturer (e.g., Apple, Dell, Lenovo).
    * **RAM:** Memory size (cleaned and converted to integer).
    * **Storage:** Storage capacity and type (SSD/HDD).
    * **Status:** Condition of the device (New vs. Refurbished).
    * **Screen:** Display specifications.

---

## 📗 Implementation Details

### ✅ Step 1: Data Preprocessing
* **Cleaning:** Removed units like 'GB' and 'kg' from `RAM` and `Weight` columns to make them numeric.
* **Type Conversion:** Converted `RAM` and `Weight` to integer/float data types.
* **Sanity Check:** Verified that there were no missing values or duplicates.

### ✅ Step 2: Univariate Analysis
* **Price Distribution:** Plotted a Histogram to visualize the frequency of different price ranges.
* **Outlier Detection:** Used a Boxplot to identify laptops with extremely high prices (Outliers).

### ✅ Step 3: Bivariate Analysis
* **Brand vs. Price:** Analyzed average prices across different brands; found that brands like Razer and Apple are generally more expensive.
* **RAM vs. Price:** Discovered a strong positive correlation (higher RAM = higher Price).
* **Status Impact:** Confirmed that 'New' laptops have a significantly higher average price than 'Refurbished' ones.

### ✅ Step 4: Market & Correlation
* **Market Share:** Visualized the top 5 brands dominating the dataset using a Pie Chart.
* **Correlation Matrix:** Generated a Heatmap to show the relationship strength between numeric features (RAM, Storage, Screen) and Price.

---

## 🚀 How to Run
1. Install requirements: `pip install -r ../requirements.txt`
2. Open `LAB1.ipynb` and run all cells sequentially.