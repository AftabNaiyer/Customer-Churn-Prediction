# Customer Churn Prediction 📊

This project analyzes customer churn in the telecom sector using machine learning techniques. The goal is to identify factors influencing customer churn and build a predictive model to help businesses retain valuable customers.

## 🚀 Project Overview

- **Industry:** Telecom
- **Objective:** Predict customer churn based on customer demographics, service usage, and account information.
- **Dataset:** WA_Fn-UseC_-Telco-Customer-Churn.csv
- **Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Imbalanced-learn

## 📁 Project Structure

```
Customer-Churn-Prediction/
│── data/
│   ├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Raw dataset
│── notebooks/
│   ├── customer_churn_analysis.ipynb  # Jupyter Notebook for data analysis and model building
│── models/
│   ├── customer_churn_model.pkl  # Trained ML model
│   ├── encoders.pkl  # Encoders for categorical variables
│── README.md  # Project documentation
│── requirements.txt  # Required Python libraries
│── .gitignore  # Files to exclude from GitHub
```

## 🔧 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Churn-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Customer-Churn-Prediction
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 🔍 Data Processing Steps

1. **Data Cleaning:** Handle missing values and correct data types.
2. **Exploratory Data Analysis (EDA):** Visualize trends and correlations.
3. **Feature Engineering:** Encode categorical variables and handle class imbalances using SMOTE.
4. **Model Training:** Train and evaluate different machine learning models.
5. **Model Evaluation:** Use accuracy, precision, recall, and confusion matrix for assessment.

## 📊 Results & Insights
- Identified key factors contributing to customer churn.
- Achieved **84% accuracy** using the best-performing model.
- Customers with month-to-month contracts and high tenure had a higher likelihood of churning.




---


