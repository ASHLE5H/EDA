Telco Customer Churn Analysis & Prediction
📌 Overview

This project explores the Telco Customer Churn dataset and builds a machine learning model to predict customer churn.
It includes:

Exploratory Data Analysis (EDA) for understanding customer behavior.

Data preprocessing & feature engineering.

Model building to classify whether a customer will churn or not.

The dataset used is: WA_Fn-UseC_-Telco-Customer-Churn.csv (from IBM Sample Datasets).

📂 Project Structure

Telco-Churn-EDA/

│── notebooks/
│    ├── Telcom_Churn_analysis.ipynb   # EDA & insights
│    ├── Churn_Prediction_Model.ipynb  # Model building
│── models/
│    ├── model.sav                     # Saved ML model
│── data/
│    ├── WA_Fn-UseC_-Telco-Customer-Churn.csv   (optional, or link below)
│── README.md
│── requirements.txt


📊 Dataset

Source: IBM Telco Customer Churn Dataset

Rows: 7043 customers

Features: 21

Target variable: Churn (Yes/No)

🛠️ Steps in the Project
1. Exploratory Data Analysis (EDA)

Distribution of churned vs non-churned customers

Customer demographics analysis (gender, senior citizens, partners, dependents)

Service usage patterns (Internet, Phone, Streaming)

Payment & contract types impact on churn

Correlation heatmaps & insights

2. Data Preprocessing

Handling missing values (TotalCharges)

Encoding categorical variables

Normalization of numerical features

3. Model Building

Tried multiple ML models (Logistic Regression, Random Forest, etc.)

Evaluated using Accuracy, Precision, Recall, F1-score

Saved the best-performing model as model.sav

🚀 How to Run

Clone this repository
git clone https://github.com/your-username/Telco-Churn-EDA.git
cd Telco-Churn-EDA

Install dependencies
pip install -r requirements.txt

Run Jupyter Notebook
jupyter notebook

Open notebooks in /notebooks to explore analysis and model building.

📈 Results

Identified key drivers of churn: contract type, tenure, monthly charges, payment method.

Built a churn prediction model with ~80% accuracy.

📌 Future Work

Deploy model as a Flask/Django web app

Add advanced models (XGBoost, Neural Networks)

Perform hyperparameter tuning for improved accuracy
