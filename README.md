# 👥 Customer Data Preprocessing & Feature Engineering

## 📌 Problem Statement

This project focuses on cleaning and preparing a **customer dataset** containing:

* Missing values
* Duplicate records
* Categorical variables (city, gender)
* Numerical features (age, annual income)

The goal is to preprocess the dataset before applying machine learning models.

---

## 🧹 Task 1 — Data Cleaning

* Imputed missing values:

  * `age` → median
  * `city` → mode
* Removed duplicate records

---

## 🔤 Task 2 — Encoding

* Applied **One-Hot Encoding** to `city`
* Applied **Label Encoding** to `gender`

---

## 📊 Task 3 — Feature Scaling

Scaled numerical columns:

* `age`
* `annual_income`

Methods used:

* **Min-Max Scaling**
* **Standardization**

---

## ⚖️ When to Use Scaling Methods

* **Min-Max Scaling**: Used when values need to be in a fixed range (0–1), especially for neural networks.
* **Standardization**: Preferred when data contains outliers or when algorithms assume normally distributed data.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 📂 How to Run

```bash
pip install -r requirements.txt
```

Open the notebook and run all cells.

---

## ✅ Output

* Cleaned dataset
* Encoded categorical variables
* Scaled numerical features

---

## 📌 Author

Your Name
