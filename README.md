# Customer Churn Prediction with Artificial Neural Network

This project uses an **Artificial Neural Network (ANN)** to predict **customer churn** for a bank. Churn prediction helps companies identify customers who are likely to leave, enabling them to take proactive measures to retain them.

---

## Dataset

- **Source**: `Churn_Modelling.csv`
- **Target Variable**: `Exited` (1 = customer left, 0 = customer stayed)
- **Features** include:
  - Customer demographics (e.g., Geography, Gender, Age)
  - Account information (e.g., Balance, Tenure, Credit Score)
  - Active status (e.g., IsActiveMember)

---

##  Technologies Used

| Tool / Library       | Purpose                            |
|----------------------|------------------------------------|
| Python               | Programming Language               |
| Pandas               | Data manipulation                  |
| NumPy                | Numerical operations               |
| Scikit-learn         | Preprocessing and model evaluation |
| TensorFlow / Keras   | Building and training ANN          |
| Matplotlib / Seaborn | Data visualization                 |

---

## Data Preprocessing

- **Step 1**: Extract features (`X`) and target (`y`)
- **Step 2**: Encode categorical data
  - Label Encoding: Gender
  - OneHotEncoding: Geography
- **Step 3**: Feature Scaling using `StandardScaler`
- **Step 4**: Train-test split (80% train, 20% test)

---

## Model Architecture

Implemented using **Keras Sequential API**:
```python
model = Sequential()
model.add(Dense(units=6, activation='relu', input_dim=11))
model.add(Dense(units=6, activation='relu'))
model.add(Dense(units=1, activation='sigmoid'))

