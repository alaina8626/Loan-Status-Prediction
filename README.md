# Loan Status Prediction using Machine Learning

This project predicts whether a loan application will be **approved or rejected** based on applicant information such as income, loan amount, credit history, employment status, and education.  
It aims to help financial institutions automate loan approval decisions using data-driven insights.

## 🔍 Project Overview
- **Objective:** Build a machine learning model to predict loan approval status.  
- **Dataset:** Public dataset containing demographic and financial details of applicants.  
- **Approach:**  
  1. Data Cleaning and Preprocessing (handling null values, encoding categorical variables)  
  2. Exploratory Data Analysis (EDA) with visualizations  
  3. Feature Selection and Correlation Analysis  
  4. Model Training and Evaluation using various algorithms  
  5. Model Comparison to identify the best-performing model  

## 🧠 Technologies Used
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Tools:** Jupyter Notebook / Google Colab  

## ⚙️ Implementation Steps
1. **Load and Explore Data** – Read dataset and understand variable types.  
2. **Data Preprocessing** – Handle missing data, encode categorical values, and normalize numeric columns.  
3. **Visualization & EDA** – Analyze relationships between features using heatmaps, bar charts, and scatter plots.  
4. **Model Building** – Train and compare:
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  
5. **Evaluation Metrics** – Accuracy, Precision, Recall, F1 Score  

## 📊 Results
- Random Forest delivered the best performance with the highest accuracy.  
- Credit history and applicant income were strong predictors of loan approval.  
- Visualization revealed clear trends between income, education, and approval rates.

