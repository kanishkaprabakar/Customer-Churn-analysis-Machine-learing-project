Customer Churn Prediction – ML & Data Analytics Project

📌 Project Overview

This project predicts whether a customer will churn (leave the service) using a Machine Learning model.
It also provides data analytics insights through a dashboard and allows users to upload CSV files to get predictions via a web app.

The system integrates:

Machine Learning model for churn prediction

Streamlit web application for user interaction

Power BI dashboard for data visualization and analytics

🎯 Objectives

Predict customer churn using ML algorithms

Provide probability of churn for each customer

Enable CSV upload for real-time predictions

Visualize churn insights using Power BI

🚀 Features

Upload customer dataset (CSV)

View dataset preview

Predict churn (0 = No, 1 = Yes)

Display churn probability

Download prediction results as CSV

Interactive Power BI dashboard for analytics

🧠 Machine Learning

Model used: (e.g., Random Forest / Logistic Regression)

Input: Customer features dataset

Output:

Churn Prediction (0/1)

Churn Probability

📊 Data Analytics

Power BI dashboard includes:

Total customers

Churn vs Non-churn count

Churn distribution by features

Key insights for decision making

🛠️ Tech Stack

Python

Scikit-learn

Pandas, NumPy

Streamlit (Web App)

Power BI (Dashboard)

Git & GitHub

📂 Project Workflow

Data preprocessing

Model training & evaluation

Save trained model

Build Streamlit web app

Upload CSV → Predict churn

Download results

Visualize insights in Power BI

▶️ How to Run the Project
# Clone repository
git clone <your-repo-link>

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run app.py
📥 Input

Upload a CSV file containing customer data with required features.

📤 Output

The app generates:

Customer ID

Churn Prediction (0/1)

Churn Probability

Downloadable CSV file

📁 Project Structure
├── app.py                 # Streamlit web app
├── model.pkl              # Trained ML model
├── dataset.csv            # Sample dataset
├── requirements.txt       # Dependencies
├── README.md              # Project documentation





📌 Future Improvements

Deploy the app online

Add more ML models for comparison

Real-time data integration

Advanced dashboard insights
