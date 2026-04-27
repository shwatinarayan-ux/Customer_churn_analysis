# Customer Churn Prediction Web App

This project predicts whether a customer will churn or not using Machine Learning and Flask.

## Overview
- Built a churn prediction model using telecom dataset
- Created a Flask web app for real-time prediction
- Users can input customer details and get prediction instantly

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Flask
- HTML

## Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Model training (Decision Tree)
- Web-based prediction system

## Project Structure
customer_churn_analysis/
- app.py
- model.shwati
- requirements.txt
- customer_churn_analysis.ipynb
- templates/
  - home.html

## How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Run the app:
python app.py

3. Open in browser:
http://127.0.0.1:5000

## Model Details
- Algorithm: Decision Tree
- Handled imbalance using SMOTEENN
- Evaluated using accuracy, precision, recall

## Key Insights
- Low tenure customers churn more
- High monthly charges increase churn
- Month-to-month contracts have higher churn rate

## Future Improvements
- Improve UI (dropdowns instead of text inputs)
- Add more models
- Deploy online

## Author
Shwati Narayan
