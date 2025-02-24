# 📊 Employee Attrition Analysis Using Machine Learning

## 🔍 Overview
This project analyzes an **Employee dataset** to identify key factors influencing **employee attrition** (whether an employee leaves or stays). The goal is to use **Machine Learning models** to predict attrition and provide insights for improving employee retention.

## 📂 Dataset
The dataset contains employee-related features such as:
- `Education`
- `JoiningYear`
- `City`
- `PaymentTier`
- `Age`
- `Gender`
- `EverBenched`
- `ExperienceInCurrentDomain`
- `LeaveOrNot` (Target Variable: 1 = Leave, 0 = Stay)

## 🛠️ Methodology
1. **Data Preprocessing**
   - Handling missing values (median for numeric, mode for categorical)
   - Encoding categorical variables using **Label Encoding** (or One-Hot Encoding)
   - Scaling numerical features using **StandardScaler**
   
2. **Exploratory Data Analysis (EDA)**
   - Visualizing attrition trends based on **experience, salary tier, city, and gender**
   - Identifying **key factors affecting attrition**  

3. **Machine Learning Models**
   - **Random Forest Classifier** (Primary Model)
   - **Logistic Regression** (Baseline Model for comparison)
   - **Hyperparameter tuning** to improve accuracy  

4. **Evaluation Metrics**
   - **Accuracy, Precision, Recall, F1-score**
   - **Feature Importance Analysis** using Random Forest

## 🚀 Technologies Used
- **Python**
- **Pandas, NumPy** (Data Processing)
- **Matplotlib, Seaborn** (Visualization)
- **Scikit-Learn** (Machine Learning)
- **Jupyter Notebook/Google Colab** (Development)

## 📊 Results & Insights
- **Employees with ≤2 years of experience** have a **higher attrition rate**.
- **Lower payment tier employees** are more likely to leave.
- **Employees who were benched** tend to leave more frequently.
- **Certain cities have higher turnover rates**, indicating job availability or dissatisfaction.
  
## 🔮 Future Improvements
- Use **XGBoost** or **Neural Networks** for better performance.
- Implement **automated feature selection** to improve accuracy.
- Integrate **SHAP (SHapley Additive Explanations)** for better explainability.

## 🏆 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Employee-Attrition-Analysis.git
