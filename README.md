# 📊 Customer Churn Prediction with Tableau Dashboard

This project combines machine learning with business intelligence to predict customer churn and visualize insights using Tableau. It's designed to showcase data analytics, modeling, and dashboarding skills in a single portfolio-worthy project.

---

## 🔍 Project Summary

- **Objective**: Predict which customers are likely to churn and explore the key factors influencing churn.
- **Tools Used**:
  - Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
  - Jupyter Notebook
  - Tableau (for interactive dashboards)

---

## 📁 Files Included

| File Name                                       | Description                                        |
|-------------------------------------------------|----------------------------------------------------|
| `Churn_Radar_Customer_Churn_Prediction.ipynb`   | Jupyter Notebook with ML pipeline and EDA          |
| `churn_with_prediction.csv`                     | Final dataset used for Tableau dashboard           |
| `Churn Radar - Customer Retention Insights.png` | Tableau dashboard image                            |
| `README.md`                                     | This file                                          |

---

## 📈 Tableau Dashboard

The Tableau dashboard provides visual answers to business questions like:

- Which contract types have the highest churn?
- How do monthly charges relate to churn?
- What is the churn rate across tenure groups?
- What’s the impact of tech support on churn?

✅ **Key KPIs Included**:
- **Total Customers**
- **Churn Rate (%)**
- **Average Monthly Revenue**

> 🔗 [Tableau Dashboard Link](https://public.tableau.com/views/ChurnRadar-CustomerRetentionInsights/ChurnRadar-CustomerRetentionInsights?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🔬 Machine Learning Model

A **Random Forest Classifier** was trained using features such as:

- `Tenure`
- `Contract Type`
- `Internet Service`
- `Tech Support`
- `Monthly Charges`
- and more...

**Target Variable**: `Churn` (Yes/No)

### 📊 Model Workflow:

1. **Data Cleaning**
2. **Label Encoding & Feature Scaling**
3. **Train-Test Split**
4. **Model Training (Random Forest)**
5. **Prediction Output (`churn_with_prediction.csv`)**

---

## 🚀 How to Use

### 📌 ML Notebook:
1. Open `Churn_Radar_Customer_Churn_Prediction.ipynb` in Jupyter/Colab.
2. Run all cells to generate `churn_with_prediction.csv`.

### 📌 Tableau Dashboard:
1. Open Tableau Public or Desktop.
2. Connect to `churn_with_prediction.csv`.
3. Recreate visuals using fields like `Churn`, `MonthlyCharges`, `Tenure`, `Contract`, etc.

---

## 📚 Dataset Source

> [Kaggle: Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 🧠 Insights Uncovered

- Month-to-month contracts show the highest churn rate.
- Customers without tech support are more likely to churn.
- Higher monthly charges slightly correlate with churn.
- Tenure is inversely related to churn likelihood.

---

## 🤝 Let's Connect

Feel free to reach out for collaboration or feedback:

- 💼 [LinkedIn](https://www.linkedin.com/in/ragavarshinibs)
- 📫 Email: ragavarshini0105@gmail.com

---

## ⭐ If you found this project helpful, please give it a star!


