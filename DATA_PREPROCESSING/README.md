# Data Preprocessing for Customer Churn Prediction

This notebook outlines the data preprocessing steps required before training a machine learning model on a customer churn dataset. Proper preprocessing ensures that the model receives clean, normalized, and machine-readable input for improved performance.

---

## Steps Covered

### 1. Importing the Dataset
- Loaded the dataset using `pandas.read_csv()`
- Separated the independent features `X` and target variable `y`

### 2. Encoding Categorical Data
- Applied **Label Encoding** to the `Gender` column
- Used **OneHotEncoding** on the `Geography` column to avoid ordinal bias
- Dropped one dummy variable (via `drop='first'`) to avoid the dummy variable trap

### 3. Splitting the Dataset
- Split the dataset into **Training Set (80%)** and **Test Set (20%)** using `train_test_split` from `sklearn.model_selection`

### 4. Feature Scaling
- Applied **Standardization** using `StandardScaler` to scale all numeric features
- This step ensures that all features contribute equally to model training

---

## Tools and Libraries Used

| Library         | Purpose                        |
|----------------|--------------------------------|
| Pandas          | Data loading and manipulation |
| NumPy           | Array operations               |
| Scikit-learn    | Encoding, scaling, splitting   |

---


