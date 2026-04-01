# lab4
# 📊 Amazon Sales Data Preprocessing & Analysis

This project demonstrates a complete data preprocessing workflow using Python. The goal is to clean, transform, and prepare the dataset for machine learning and analysis.

---

## 📁 Dataset

The dataset contains information about sales transactions, including:

* Order details (order_id, order_date)
* Product information (product_id, product_category)
* Sales metrics (price, discount, total_revenue)
* Customer behavior (region, payment_method, rating)

---

## 🔧 Steps Performed

### 1. Import Libraries

We used essential Python libraries:

* **Pandas & NumPy** → data manipulation
* **Matplotlib & Seaborn** → visualization

---

### 2. Load Dataset

The dataset was loaded using Pandas and previewed to understand its structure and columns.

---

### 3. Data Quality Assessment

We checked the data types of each column to ensure they match their meaning.

* Converted `order_date` to datetime format for proper time analysis.

---

### 4. Handling Missing Values

* Checked for missing values using `.isna().sum()`
* Introduced artificial missing values for learning purposes
* Applied different strategies:

  * **Removing records** (drop missing rows)
  * **Mean imputation** (replace with average)
  * **Median imputation** (replace with middle value)

---

### 5. Handling Outliers

* Visualized data using a **boxplot**
* Detected outliers using the **IQR method**
* Applied two strategies:

  * **Removing outliers**
  * **Capping values** using percentiles (5%–95%)

---

### 6. Data Transformation (Normalization)

To prepare data for machine learning:

* **Min-Max Scaling** → scales values between 0 and 1
* **Standardization (Z-score)** → centers data around 0

---

### 7. Correlation Analysis

* Used a **heatmap** to check relationships between numerical features
* Determined whether features are strongly related

---

### 8. PCA (Dimensionality Reduction)

* Applied **Principal Component Analysis (PCA)**
* Reduced features while preserving important information
* Evaluated using **explained variance ratio**

---

## 🎯 Objective

The main objective of this project is to:

* Improve data quality
* Prepare data for machine learning models
* Understand preprocessing techniques used in real-world datasets

---


## 📌 Conclusion

This project shows how raw data can be transformed into a clean and structured format ready for analysis and modeling. Each preprocessing step plays an important role in improving model performance and data reliability.

---
