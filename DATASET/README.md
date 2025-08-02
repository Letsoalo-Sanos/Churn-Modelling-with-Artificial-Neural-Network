#  Customer Churn Dataset

This dataset contains customer information from a fictional bank and is used for building machine learning models to **predict customer churn** — whether a customer will leave the bank or not.

---

##  Dataset Summary

- **File Name**: `Churn_Modelling.csv`(available on kaggle)
- **Total Rows**: 10,000
- **Total Columns**: 14
- **Target Variable**: `Exited` (1 = customer churned, 0 = customer retained)

---

##  Column Descriptions

| Column Name         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `RowNumber`         | Row index (not useful for modeling)                                         |
| `CustomerId`        | Unique ID assigned to each customer                                         |
| `Surname`           | Customer's last name (can be dropped for modeling)                          |
| `CreditScore`       | Credit score of the customer                                                |
| `Geography`         | Country of the customer (`France`, `Germany`, `Spain`)                      |
| `Gender`            | Gender of the customer (`Male`, `Female`)                                   |
| `Age`               | Age of the customer                                                         |
| `Tenure`            | Number of years the customer has stayed with the bank                       |
| `Balance`           | Account balance                                                             |
| `NumOfProducts`     | Number of bank products the customer is using                               |
| `HasCrCard`         | Does the customer have a credit card? (1 = Yes, 0 = No)                     |
| `IsActiveMember`    | Is the customer an active member? (1 = Yes, 0 = No)                         |
| `EstimatedSalary`   | Estimated annual salary                                                     |
| `Exited`            | **Target variable**: 1 = customer left the bank, 0 = customer stayed        |

---




