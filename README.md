# 🔍 Customer Churn Prediction Using Random Forest (Web App)

This project predicts **customer churn** using a machine learning model based on the **Random Forest Classifier**. It includes end-to-end data analysis, model training, and deployment via an interactive web app built with Gradio and hosted on Hugging Face Spaces.

---

## 🌐 Live Web App

👉 [Access the Churn Prediction Web App](https://huggingface.co/spaces/Omkar1872/churn-Prediction-App)

---

## 🚀 Project Overview

Customer churn is a major concern for subscription-based businesses. The ability to predict churn enables companies to retain customers and reduce revenue loss. In this project:

- A **binary classification model** was built to predict churn.
- The dataset was cleaned, analyzed, and preprocessed.
- A **Random Forest Classifier** was trained and evaluated.
- The final model was deployed as a web app for real-time predictions.

---

## 📊 Dataset Description

| Feature             | Description                                          |
|---------------------|------------------------------------------------------|
| `Age`               | Age of the customer                                  |
| `Gender`            | Gender of the customer                               |
| `Tenure`            | Number of months the customer has stayed             |
| `Usage Frequency`   | Frequency of product/service usage                   |
| `Support Calls`     | Number of customer support interactions              |
| `Payment Delay`     | Number of days payment was delayed                   |
| `Subscription Type` | Type of customer plan                                |
| `Contract Length`   | Duration of the customer's contract                  |
| `Total Spend`       | Total amount spent                                   |
| `Last Interaction`  | Days since last interaction                          |
| `Churn`             | Target variable (0 = Not churned, 1 = Churned)       |

✅ **Class Distribution**  
- Not Churned (0): 52.63%  
- Churned (1): 47.37%  
No class imbalance — great for model performance.

---

## 🔧 Project Workflow

### 1. **Data Loading**
- Loaded with `pandas.read_csv()`

### 2. **Exploratory Data Analysis (EDA)**
- Summary stats, value counts, visualizations

### 3. **Data Preprocessing**
- Handled missing values  
- Encoded categorical features (e.g., `Gender`, `Subscription Type`)  
- Feature scaling using `StandardScaler`  
- Train-test split (e.g., 80/20)

### 4. **Model Building**
- Trained a **Random Forest Classifier** using `sklearn.ensemble`

### 5. **Model Evaluation**
- Accuracy, confusion matrix, classification report  
- Feature importance visualization

### 6. **Model Deployment**
- Exported model using `joblib`  
- Built web app with Gradio  
- Deployed on Hugging Face Spaces

---

## 📈 Model Performance

| Metric             | Score         |
|--------------------|---------------|
| Training Accuracy  | 100%          |
| Testing Accuracy   | 99.94%        |

✅ High accuracy  
✅ No overfitting  
✅ Balanced dataset and effective features

---

## 🧠 Feature Importance

Feature importance was visualized to understand key drivers of churn. This helps in making actionable business decisions.

---

## 🧪 Tech Stack

- **Python**
- **Pandas, NumPy, Scikit-learn**
- **Gradio (for UI)**
- **Hugging Face Spaces (for deployment)**
- **Joblib (for model saving)**

---

## 💻 How to Run Locally

```bash
git clone https://github.com/omkar1872/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
python app.py

Feel free to connect:

- GitHub: [https://github.com/omkar1872](https://github.com/omkar1872)  
- LinkedIn: [https://linkedin.com/in/omkar1872](https://www.linkedin.com/in/omkar1872/)  
- Email: chomkar1872@gmail.com



