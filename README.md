Dataset available at: [Kaggle: Default of Credit Card Clients Dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset?select=UCI_Credit_Card.csv)

---

### Dataset Summary

* **Title**: Default of Credit Card Clients Dataset
* **Source**: UCI Machine Learning Repository
* **Records**: 30,000 credit card clients
* **Features**: 24 input variables + 1 target variable
* **File**: `UCI_Credit_Card.csv`
* **Country**: Taiwan
* **Timeframe**: April–September 2005
* **License**: CC0: Public Domain

---

### Feature Overview

* **Demographics**:

  * `SEX`: Gender (1 = male, 2 = female)
  * `EDUCATION`: Education level (1 = graduate school, 2 = university, 3 = high school, 4 = others)
  * `MARRIAGE`: Marital status (1 = married, 2 = single, 3 = others)
  * `AGE`: Age in years

* **Financial Data**:

  * `LIMIT_BAL`: Amount of given credit (NT dollars)
  * `BILL_AMT1` to `BILL_AMT6`: Bill statement amounts for the past 6 months
  * `PAY_AMT1` to `PAY_AMT6`: Amounts paid in the past 6 months

* **Payment History**:

  * `PAY_0` to `PAY_6`: Repayment status from April to September 2005 (e.g., -1 = pay duly, 1 = one month delay, etc.)

* **Target Variable**:

  * `default.payment.next.month`: Indicates default payment status for the next month (1 = default, 0 = no default)

---
This dataset is widely utilized for credit risk modeling and classification tasks.
---
