# Data Preprocessing for Customer Churn Prediction

This notebook outlines the data preprocessing steps required before training a machine learning model on a customer churn dataset. Proper preprocessing ensures that the model receives clean, normalized, and machine-readable input for improved performance.

---

## Steps Covered

### 1. Importing the Dataset

- Loaded the dataset using `pandas.read_csv()`

### 2. 🔤 Encoding Categorical Data

- Applied **Label Encoding** to the `Gender` column
- Used **OneHotEncoding** on the `Geography` column to avoid ordinal bias

---

## Tools and Libraries Used

| Library      | Purpose                       |
| ------------ | ----------------------------- |
| Pandas       | Data loading and manipulation |
| NumPy        | Array operations              |
| Scikit-learn | Encoding, scaling             |

---
