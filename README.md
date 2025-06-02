# 🔍 Customer Churn Prediction Using Random Forest

This project uses a machine learning approach to predict **customer churn** — that is, whether a customer will stop using a company's services. A **Random Forest Classifier** is used due to its strong performance on classification tasks and ability to handle both categorical and numerical data.

---

## 🚀 Project Overview

Customer churn is a major concern in subscription-based businesses. The ability to predict churn allows companies to proactively engage at-risk customers and reduce revenue loss. In this project:

- We built a **binary classification model** to predict churn.
- The data is cleaned, analyzed, and preprocessed.
- A **Random Forest** model was trained and evaluated.

---

## 📊 Dataset Description

The dataset includes the following features:

| Feature             | Description                                          |
|---------------------|------------------------------------------------------|
| `Age`               | Age of the customer                                  |
| `Gender`            | Gender of the customer                               |
| `Tenure`            | Number of months the customer has stayed             |
| `Usage Frequency`   | How often the customer uses the product/service      |
| `Support Calls`     | Number of customer support interactions              |
| `Payment Delay`     | Number of days delayed in payment                    |
| `Subscription Type` | Categorical feature representing the plan            |
| `Contract Length`   | Length of the customer's contract in months          |
| `Total Spend`       | Total money spent by the customer                    |
| `Last Interaction`  | Days since the last customer interaction             |
| `Churn`             | Target variable (0 = Not churned, 1 = Churned)       |

✅ Class Distribution:  
- Churn = 0 (Not Churned): **52.63%**  
- Churn = 1 (Churned): **47.37%**  
✅ No class imbalance — good for accurate model training.

---

## 🛠 Project Workflow

### 1. **Data Loading**
- The dataset was loaded using `pandas.read_csv()`

### 2. **Exploratory Data Analysis (EDA)**
- Summary statistics using `df.describe()`
- Value counts and visualizations to understand distributions

### 3. **Data Preprocessing**
- Missing value handling (if any)
- Encoding categorical variables (`Gender`, `Subscription Type`)
- Feature scaling using `StandardScaler` (for numerical features)
- Train-Test Split (e.g., 80% train, 20% test)

### 4. **Model Building: Random Forest**
- Random Forest Classifier from `sklearn.ensemble`
- Fit on training data

### 5. **Model Evaluation**
- Accuracy, confusion matrix, and classification report
- Feature importance plot

### 6. **Exporting the Model**
- Model saved using `joblib.dump()` for reuse in deployment

---

## 📈 Model Performance

| Metric             | Score         |
|--------------------|---------------|
| Training Accuracy  | 100%          |
| Testing Accuracy   | 99.94%        |

- ✅ High accuracy on both train and test sets
- ✅ No sign of overfitting
- ✅ Reliable model due to balanced classes and clean features

### 🔍 Feature Importance
Feature importance was visualized to understand which features most impact churn.

---
## Contact & Contributions

I welcome feedback and collaboration.  
Feel free to connect:

- GitHub: [https://github.com/omkar1872](https://github.com/omkar1872)  
- LinkedIn: [https://linkedin.com/in/omkar1872](https://www.linkedin.com/in/omkar1872/)  
- Email: chomkar1872@gmail.com



