# Customer Churn Prediction Web 

A Machine Learning-powered web application that predicts whether a telecom customer is likely to churn based on customer behavior and service usage patterns.

This project combines Data Analysis, Machine Learning, and Flask Web Development to provide real-time churn prediction through a simple web interface.

---

# Project Overview

Customer churn is one of the biggest challenges in the telecom industry. Companies lose customers due to competition, pricing, and service-related issues. Predicting churn helps businesses take preventive actions and improve customer retention.

In this project:

- Telecom customer data was analyzed using Exploratory Data Analysis (EDA)
- A Machine Learning model was trained to predict customer churn
- A Flask web application was developed for real-time predictions
- Users can enter customer details and instantly get prediction results

---

# Features

- Customer churn prediction using Machine Learning
- Flask-based web application
- Real-time prediction system
- User-friendly HTML interface
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Decision Tree Classification model
- Handling imbalanced data using SMOTEENN
- Model saving and loading

---

# Tech Stack

## Programming Language
- Python

## Libraries & Frameworks
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Flask
- Matplotlib
- Seaborn

## Frontend
- HTML
- CSS

---

# Problem Statement

Telecom companies face high customer churn rates, leading to revenue loss. The goal of this project is to build a predictive system that identifies customers who are likely to leave the service.

This helps businesses:
- Improve customer retention
- Reduce revenue loss
- Understand customer behavior
- Build targeted retention strategies

---

# Dataset Information

The dataset contains telecom customer details such as:

- Gender
- Senior Citizen status
- Partner/Dependents
- Tenure
- Internet Service
- Monthly Charges
- Total Charges
- Contract Type
- Payment Method
- Churn Status

## Dataset Files

- `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- `tel_churn.csv`
- `first_telc.csv`

---

# Machine Learning Workflow

## 1. Data Collection
Imported telecom customer churn dataset.

## 2. Data Cleaning
Performed:
- Null value handling
- Data type conversion
- Duplicate removal
- Feature formatting

## 3. Exploratory Data Analysis (EDA)
Analyzed:
- Churn distribution
- Contract type impact
- Monthly charges vs churn
- Tenure vs churn
- Internet service behavior

Visualization libraries used:
- Matplotlib
- Seaborn

## 4. Data Preprocessing
Applied:
- Label Encoding
- Feature Scaling
- Train-Test Split

## 5. Handling Imbalanced Dataset
Used **SMOTEENN** technique to balance churn classes and improve model performance.

## 6. Model Training
Trained a **Decision Tree Classifier** model using Scikit-learn.

## 7. Model Evaluation
Evaluated using:
- Accuracy
- Precision
- Recall
- Confusion Matrix
- Classification Report

## 8. Model Deployment
Integrated trained model into a Flask web application.

---

# Project Structure

```bash
customer_churn_analysis/
│
├── app.py
├── README.md
├── requirements.txt
├── churn_model.pkl
│
├── notebooks/
│   ├── churn_eda.ipynb
│   ├── churn_model.ipynb
│   └── customer_churn_analysis.ipynb
│
├── datasets/
│   ├── WA_Fn-UseC_-Telco-Customer-Churn.csv
│   ├── tel_churn.csv
│   └── first_telc.csv
│
├── templates/
│   └── home.html
│
├── static/
│
└── screenshots/
```

---

# Web Application

The Flask web app allows users to:

- Enter customer information
- Submit customer details
- Get instant churn prediction results

## Prediction Output

The system predicts:

- Customer Will Churn
or
- Customer Will Not Churn

---

# Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

---

## 2. Navigate to Project Folder

```bash
cd customer-churn-prediction
```

---

## 3. Create Virtual Environment (Optional)

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 5. Run Flask Application

```bash
python app.py
```

---

## 6. Open in Browser

```bash
http://127.0.0.1:5000
```

---

# Sample Workflow

1. Open the web application
2. Enter customer details
3. Click Predict
4. View churn prediction result instantly

---

# Model Details

| Model | Decision Tree Classifier |
|-------|--------------------------|
| Problem Type | Classification |
| Dataset Type | Telecom Customer Data |
| Imbalance Handling | SMOTEENN |
| Framework | Scikit-learn |

---

# Key Insights from EDA

- Customers with low tenure are more likely to churn
- Month-to-month contract users show higher churn rates
- Higher monthly charges increase churn probability
- Customers with long-term contracts are more stable
- Fiber optic users showed relatively higher churn

---

# Future Improvements

- Improve UI/UX design
- Replace text fields with dropdown menus
- Add probability score for prediction
- Deploy using Render or Railway
- Add multiple ML models for comparison
- Add authentication system
- Convert into full dashboard using Streamlit or React

---

# Screenshots

Add project screenshots inside the `screenshots/` folder.

Example:

```md
## Home Page
![Home Page](screenshots/homepage.png)

## Prediction Result
![Prediction Result](screenshots/result.png)
```

---

# Requirements

Example `requirements.txt`

```txt
flask
pandas
numpy
scikit-learn
imbalanced-learn
matplotlib
seaborn
```

---

# Learning Outcomes

Through this project, you practiced:

- Data preprocessing
- Exploratory Data Analysis
- Classification algorithms
- Handling imbalanced datasets
- Model deployment using Flask
- Building ML-powered web applications
- End-to-end Machine Learning workflow

---

# Author

**Shwati Narayan**

B.Tech Data Science Student  
Interested in Machine Learning, Data Analytics, and Web Development

---

# License

This project is for educational and learning purposes.
