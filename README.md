# Telco Customer Churn Prediction

## 📌 Overview  
This project aims to predict customer churn (i.e., customers leaving) for a telecom company using real-world data. The goal is to identify which customers are at risk of leaving and what features contribute to that behavior.

---

## 🗂 Dataset  
- Source: [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Records: 7043 customers  
- Features: 21 columns including demographics, account info, and services  
- Target: `Churn` (Yes/No)

---

## 🧠 Technologies Used
- Python 3
- Jupyter Notebook
- pandas, numpy
- seaborn, matplotlib
- scikit-learn (RandomForestClassifier, preprocessing pipeline)

---

## 📘 Project Structure
Telco-Churn-Prediction/
├── notebooks/
│ ├── 1_data_exploration.ipynb
│ └── 2_churn_prediction_model.ipynb
├── README.md


---

## 📊 Notebooks

### 🔍 1. Data Exploration
- Data loading & cleaning
- Type conversion (`TotalCharges`)
- Missing value handling
- Statistical summaries & boxplots
- Category-wise churn visualizations
- Correlation matrix

### 🤖 2. Churn Prediction Model
- Train/test split (70/30)
- Preprocessing with ColumnTransformer
- Model training with RandomForestClassifier
- Evaluation: classification report, confusion matrix
- Feature importance chart

---

## 📈 Results
- Model successfully predicts customer churn with reasonable accuracy.
- Most important features: `tenure`, `Contract`, `MonthlyCharges`, and services like `OnlineSecurity`.

---

## 👤 Author
**Parisa (Shahpari2kht)**  
Aspiring Data Scientist | Python & ML Enthusiast  
GitHub: [@Shahpari2kht](https://github.com/Shahpari2kht)

---

> ⭐ If you like this project, give it a star and feel free to fork or use it as a template.
