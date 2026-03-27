# 🎓 Student Performance Prediction using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-green" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

## 📌 Project Overview

This project builds a **Machine Learning model** to predict student final exam scores based on behavioral and academic factors.

The analysis compares:
- ✅ Linear Regression (primary model)
- 🌳 Decision Tree Regressor (baseline comparison)

The goal is to **identify key performance drivers** and generate insights for improving student outcomes.

---
## 🚨 Problem Statement

Educational institutions often struggle to identify underperforming students early enough to provide timely support. Traditional methods rely on manual evaluation and may fail to capture underlying patterns in student behavior.

This project addresses the challenge of predicting student academic performance early using machine learning, enabling proactive interventions, personalized learning strategies, and improved educational outcomes.

## 🎯 Objective

- Predict students' final exam scores using behavioral and academic data  
- Identify key factors influencing performance  
- Support data-driven decision-making in education  

## 🎯 Key Results

| Model                | R² Score | RMSE | MAE |
|---------------------|--------|------|-----|
| ✅ Linear Regression | **0.87** | **4.77** | **3.59** |
| 🌳 Decision Tree     | 0.58 | 8.57 | 7.43 |

### 🔍 Insight
- Linear Regression significantly outperformed Decision Tree  
- Indicates a **strong linear relationship** in the dataset  

---

## 📊 Dataset Overview

- **Total Records:** 150  
- **Target Variable:** `final_exam_score`

### Features:
- `hours_studied`
- `attendance_percentage`
- `previous_test_score`
- `sleep_hours`

---

## 📈 Exploratory Data Analysis (EDA)

### 🔹 Feature Relationships
<img width="571" height="455" alt="download" src="https://github.com/user-attachments/assets/f37df51a-33ce-4c0f-a708-10bf5e131764" />


### 🔍 EDA Insights

* Strong positive correlation: `previous_test_score`
* Moderate impact: `hours_studied`
* Sleep and attendance also contribute positively

---

## ⚙️ Methodology

1. Data Exploration (`.info()`, `.describe()`)
2. Data Cleaning (Mean Imputation)
3. Feature Selection
4. Train-Test Split (80/20)
5. Model Training
6. Model Evaluation
7. Residual Analysis
8. Model Comparison

---

## 🧠 Model Interpretation

| Feature        | Impact on Score     |
| -------------- | ------------------- |
| Hours Studied  | +4.45 points / hour |
| Attendance     | +0.32 points / %    |
| Previous Score | +0.42 points / unit |
| Sleep Hours    | +1.51 points / hour |

---

## 📉 Residual Analysis
<img width="574" height="453" alt="Residuals" src="https://github.com/user-attachments/assets/6ccd945d-7763-4e2c-b11a-691609a79e1b" />


### Insight:

* Residuals are randomly distributed → Linear model assumptions hold

## 💼 Business Impact

* 🎯 Early identification of at-risk students
* 📚 Personalized learning strategies
* 🏫 Optimized resource allocation
* 📊 Data-driven decision-making

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## ▶️ How to Run

```bash
git clone https://github.com/Muradamen/student-performance-prediction-ml.git
cd student-performance-prediction-ml
pip install -r requirements.txt
```

Then open the notebook in Jupyter or Google Colab.

---

## 🧪 Future Improvements

* Random Forest / XGBoost models
* Feature Engineering
* Cross-validation
* Deploy as web app (Streamlit / Flask)

---

## 👨‍💻 Author

**Murad Amin**
www.linkedin.com/in/muradamin
https://github.com/Muradamen

---

## 🌟 Project Highlights

✔ End-to-end ML pipeline
✔ Model comparison
✔ Business-focused insights
✔ Clean and interpretable model


## 📢 Share & Connect

If you found this useful, feel free to connect!

#ALXProjectPortfolio #DataScience #MachineLearning #Python #AI




