# Customer Churn Prediction Web App

A Machine Learning-powered web application that predicts whether a telecom customer is likely to churn based on customer behavior and service usage patterns.

This project combines data analysis, machine learning, and web development using Flask to deliver real-time churn predictions through a simple user interface.

Project Overview

Customer churn is one of the biggest challenges in the telecom industry. Companies lose revenue when customers stop using their services. Predicting churn early helps businesses take preventive actions and improve customer retention.

In this project:

Telecom customer data was analyzed using Exploratory Data Analysis (EDA)
A Machine Learning model was trained to predict churn
A Flask web application was built for real-time predictions
Users can enter customer details through a web interface and instantly check churn probability
Features
Customer churn prediction using Machine Learning
Flask-based web application
User-friendly HTML interface
Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Decision Tree Classification model
Handling imbalanced data using SMOTEENN
Real-time prediction system
Model serialization using Pickle/Joblib
Tech Stack
Programming Language
Python
Libraries & Frameworks
Pandas
NumPy
Scikit-learn
Imbalanced-learn
Flask
Matplotlib
Seaborn
Frontend
HTML
CSS
Problem Statement

Telecom companies face high customer churn rates due to increasing competition. The objective of this project is to build a predictive system that identifies customers who are likely to leave the service.

The prediction helps businesses:

Improve customer retention
Reduce revenue loss
Create personalized retention strategies
Understand churn behavior patterns
Dataset Information

The dataset contains telecom customer details such as:

Gender
Senior Citizen status
Partner/Dependents
Tenure
Internet Service
Monthly Charges
Total Charges
Contract Type
Payment Method
Churn Status
Dataset Files
WA_Fn-UseC_-Telco-Customer-Churn.csv
tel_churn.csv
first_telc.csv
Machine Learning Workflow
1. Data Collection

Imported telecom customer churn dataset.

2. Data Cleaning

Performed:

Null value handling
Data type conversion
Duplicate removal
Feature formatting
3. Exploratory Data Analysis (EDA)

Analyzed:

Churn distribution
Contract type impact
Monthly charges vs churn
Tenure vs churn
Internet service behavior

Visualization libraries used:

Matplotlib
Seaborn
4. Data Preprocessing

Applied:

Label Encoding
Feature Scaling
Train-Test Split
5. Handling Imbalanced Dataset

Used SMOTEENN technique to balance churn classes and improve model performance.

6. Model Training

Trained a Decision Tree Classifier model using Scikit-learn.

7. Model Evaluation

Evaluated using:

Accuracy
Precision
Recall
Confusion Matrix
Classification Report
8. Model Deployment

Integrated trained model into a Flask web application.

Project Structure
customer_churn_analysis/
│
├── app.py
├── README.md
├── requirements.txt
├── model.shwati
│
├── churn_eda.ipynb
├── churn_model.ipynb
├── customer_churn_analysis.ipynb
│
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── tel_churn.csv
├── first_telc.csv
│
├── templates/
│   └── home.html
│
└── static/
Web Application

The Flask web app allows users to:

Enter customer information
Submit customer details
Get instant churn prediction result
Prediction Output

The system predicts:

Customer Will Churn
or
Customer Will Not Churn
Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/customer-churn-prediction.git
2. Navigate to Project Folder
cd customer-churn-prediction
3. Create Virtual Environment (Optional)
Windows
python -m venv venv
venv\Scripts\activate
Mac/Linux
python3 -m venv venv
source venv/bin/activate
4. Install Dependencies
pip install -r requirements.txt
5. Run Flask Application
python app.py
6. Open in Browser
http://127.0.0.1:5000
Sample Workflow
Open the web application
Enter customer details
Click Predict
View churn prediction result instantly
Model Details
Model	Decision Tree Classifier
Problem Type	Classification
Dataset Type	Telecom Customer Data
Imbalance Handling	SMOTEENN
Framework	Scikit-learn
Key Insights from EDA
Customers with low tenure are more likely to churn
Month-to-month contract users show higher churn rates
Higher monthly charges increase churn probability
Customers with long-term contracts are more stable
Fiber optic users showed relatively higher churn
Future Improvements
Add better UI/UX design
Replace text fields with dropdown menus
Add probability score for prediction
Deploy using Render or Railway
Add multiple ML models for comparison
Add authentication system
Convert into full dashboard using Streamlit or React
Screenshots

You can add screenshots here after uploading images to GitHub.

Example:

## Home Page
![Home Page](screenshots/homepage.png)

## Prediction Result
![Prediction](screenshots/result.png)
Requirements

Example requirements.txt:

flask
pandas
numpy
scikit-learn
imbalanced-learn
matplotlib
seaborn
Learning Outcomes

Through this project, you practiced:

Data preprocessing
Exploratory Data Analysis
Classification algorithms
Handling imbalanced datasets
Model deployment using Flask
Building ML-powered web applications
End-to-end Machine Learning workflow

Author
Shwati Narayan
