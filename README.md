## 🌍 Global E-Commerce Purchase Amount Prediction Using Machine Learning
#### 📌 Project Summary

This project aims to predict customer purchase amounts using historical global e-commerce data. By applying advanced feature engineering, target transformation, and multiple regression models, the project delivers accurate revenue predictions and actionable business insights.

The solution is designed to simulate real-world e-commerce analytics use cases such as demand forecasting, pricing strategy, and customer value estimation.

## 🧩 Business Context

In global e-commerce platforms, purchase behavior varies significantly across:
* Customers
* Locations
* Product categories
* Time periods
* Traditional forecasting approaches struggle due to:
* Highly right-skewed transaction data
* Mixed numerical and categorical features
* Non-linear relationships between variables

This project addresses these challenges using machine learning-based predictive modeling.

## 🎯 Project Objectives

Predict purchase amounts with higher accuracy

Reduce prediction error (MAE & MAPE)

Handle skewness and variance in transaction values

Compare multiple regression models

Translate model performance into business insights

## 🧠 End-to-End Solution Architecture
Raw Data
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis (EDA)
   ↓
Correlation & Feature Selection
   ↓
Feature Engineering
   ↓
Model Training & Evaluation
   ↓
Business Insights

## 🔍 Detailed Project Workflow
1️⃣ Data Cleaning & Preprocessing

Removed duplicate records

Handled missing and inconsistent values

Corrected data types for numerical and categorical variables

Detected and treated outliers impacting model performance

📌 Outcome: Clean, consistent dataset suitable for statistical and ML analysis.

2️⃣ Exploratory Data Analysis (EDA)

Analyzed purchase amount distribution

Identified heavy right-skewness in the target variable

Studied customer behavior patterns across features

Visualized trends and relationships

📌 Insight: Purchase amount distribution violated normality assumptions, motivating transformation.

3️⃣ Correlation Analysis

Computed correlation between numerical variables

Identified influential predictors

Reduced redundant features

Controlled multicollinearity

📌 Benefit: Improved model interpretability and stability.

4️⃣ Feature Engineering

Feature Scaling applied to numerical variables

One-Hot Encoding used for categorical variables

Log Transformation applied to the dependent variable (Purchase Amount)

📌 Key Breakthrough:
Log transformation reduced skewness and variance, significantly improving prediction accuracy.

5️⃣ Machine Learning Models Used

The following regression models were trained and evaluated:

Linear Regression

Decision Tree Regression

Random Forest Regression

Gradient Boosting Regression

XGBoost Regression

Each model was evaluated using business-aligned metrics.

6️⃣ Model Evaluation Metrics

MAE (Mean Absolute Error)

MAPE (Mean Absolute Percentage Error)

## 📉 Result:
Post log transformation:

MAE reduced significantly

MAPE improved to a more business-acceptable range

Ensemble and boosting models captured complex patterns better

## 📊 Key Results & Insights

Log transformation had a greater impact than model complexity

Ensemble models outperformed baseline regression

Predictions aligned more closely with actual purchase behavior

Reduced error improved real-world forecasting reliability

## 🛠️ Tech Stack & Tools
Programming & Libraries

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

XGBoost

Techniques

Regression Modeling

Feature Engineering

Predictive Analytics

Error Optimization

## 📁 Repository Structure
├── data/
│   └── ecommerce_data.csv
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Feature_Engineering.ipynb
│   ├── 03_Model_Training.ipynb
│
├── src/
│   └── model_pipeline.py
│
├── requirements.txt
└── README.md

## 🚀 How to Run the Project
Step 1: Clone the Repository
git clone https://github.com/your-username/global-ecommerce-purchase-prediction.git

Step 2: Install Dependencies
pip install -r requirements.txt

Step 3: Run Notebooks

Open Jupyter Notebook and execute notebooks in sequence for full workflow understanding.

## 📈 Business Use Cases

Revenue forecasting

Customer lifetime value estimation

Pricing and promotion optimization

Demand planning and inventory strategy

Data-driven decision making

## 🔮 Future Enhancements

Hyperparameter tuning using GridSearchCV

SHAP values for explainability

Model deployment using Flask / FastAPI

Real-time prediction API

Dashboard integration using Power BI / Tableau

## 📚 Key Learnings

Data preprocessing drives model success

Target transformation is critical for skewed financial data

Business-aligned metrics matter more than raw accuracy

ML models must be evaluated from a business impact perspective

## 👤 Author

Deepak Behera
MBA – Business Analytics | PGDM – Finance

Skills:
SQL | Python | Machine Learning | Power BI | Statistical Analysis | Business Analytics
