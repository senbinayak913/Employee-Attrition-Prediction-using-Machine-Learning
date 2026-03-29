# 📊 Employee Attrition Prediction using Machine Learning

## 📌 Project Overview
Employee attrition is a major challenge for organizations, especially in the tech industry. This project aims to predict whether an employee is likely to leave the company using machine learning techniques.

The model helps organizations take proactive steps to improve employee retention, reduce costs, and enhance productivity.

---

## 🎯 Objectives
- Analyze employee data using Exploratory Data Analysis (EDA)
- Identify key factors influencing attrition
- Build predictive models
- Compare model performance
- Select the best model for business use

---

## 📂 Dataset
- IBM HR Analytics Employee Attrition Dataset
- Features include:
  - Age, Job Role, Department
  - Monthly Income
  - Job Satisfaction
  - Overtime
  - Distance from Home

Target Variable:
- Attrition (Yes / No)

---

## 🧹 Data Preprocessing
- Removed unnecessary columns:
  - EmployeeCount, StandardHours, Over18
- Converted categorical variables using encoding
- Applied one-hot encoding for features
- Performed train-test split (80:20)
- Applied feature scaling for Logistic Regression

---

## 📊 Exploratory Data Analysis (EDA)
Key insights:
- Employees working overtime are more likely to leave
- Lower salary is linked with higher attrition
- Job satisfaction strongly affects retention
- Younger employees tend to leave more frequently

Visualizations include:
- Attrition distribution
- Department vs Attrition
- Job Role vs Attrition
- Salary vs Attrition
- Overtime impact

---

## 🤖 Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Model Evaluation
Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- ROC Curve

### Results:
- Logistic Regression: **88.44%**
- Decision Tree: **81.97%**
- Random Forest: **87.76%**

---

## 🏆 Final Model Selection
Logistic Regression was selected as the final model because:
- It achieved the highest accuracy
- It is simple and interpretable
- It provides stable predictions

---

## 💼 Business Impact
This model helps organizations:
- Predict employee attrition in advance
- Reduce hiring and training costs
- Improve employee productivity
- Enhance decision-making

---

## 🚀 Future Scope
- Deploy as a web application
- Use real-time HR data
- Implement advanced models like XGBoost
- Integrate with HR dashboards

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter notebook
- Google Colab

---

## 📁 Project Structure
