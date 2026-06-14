# 🎓 Student Burnout Risk Prediction (Machine Learning Notebook Project)

This project predicts **student burnout risk level (Low, Medium, High)** using machine learning models based on academic behavior, AI usage, and study patterns.

> 📌 This project is implemented entirely in a **Jupyter Notebook (.ipynb)**

---

## 📊 Dataset Overview

The dataset contains **50,000 student records** with features such as:

- Major Category
- Year of Study
- Pre-Semester GPA
- Post-Semester GPA
- Weekly Generative AI Usage
- Traditional Study Hours
- Prompt Engineering Skill
- Tool Diversity
- Perceived AI Dependency
- Anxiety Level During Exams
- Institutional Policy
- Skill Retention Score

---

## 🎯 Target Variable

**Burnout_Risk_Level**
- 0 → Low
- 1 → Medium
- 2 → High

---

## ⚙️ Workflow (Inside Notebook)

The project follows a standard ML pipeline:

1. Data Loading (CSV)
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Encoding Categorical Variables
5. Feature Scaling (for KNN & Logistic Regression)
6. Train-Test Split
7. Model Training
8. Model Evaluation

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier

---

## 🏆 Model Performance

| Model | Accuracy |
|------|---------:|
| Logistic Regression | ~0.517 |
| KNN | ~0.469 |
| Decision Tree | ~0.433 |
| Random Forest | ~0.528 |

👉 Best Model: **Random Forest Classifier**

---

## 📈 Key Insights

- Weekly GenAI usage is the strongest factor linked to burnout.
- AI dependency also significantly affects burnout risk.
- Traditional study hours have a mild negative correlation with burnout.
- Burnout prediction is a challenging multi-class classification problem.

---

## 🧪 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---
