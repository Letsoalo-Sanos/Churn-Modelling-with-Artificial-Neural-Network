# Machine Learning for Customer Churn Prediction

This phase of the project focuses on building and training a **machine learning model** to predict whether a customer will churn (leave the bank) based on their account activity and demographics.

The selected model is an **Artificial Neural Network (ANN)** built using the Keras API in TensorFlow.

---

## Objective

To build a supervised binary classification model that can:

- Accurately identify customers who are likely to leave the bank
- Help the bank take proactive actions to reduce churn

---

## Model Architecture

The model is implemented using the **Keras Sequential API**:

```python
model = Sequential()
model.add(Dense(units=6, activation='relu', input_dim=11))
model.add(Dense(units=6, activation='relu'))
model.add(Dense(units=1, activation='sigmoid'))
```
