# 🩺 AI in Healthcare: Building a Life-Saving Heart Disease Predictor

This project leverages **Machine Learning** to predict whether a patient is at risk of **heart disease** based on their medical attributes.  
It demonstrates how AI can support early diagnosis, enabling proactive intervention and healthcare efficiency.

---

## 🎯 Objective

To develop and evaluate machine learning models capable of predicting the presence or absence of heart disease using clinical and physiological data.

---

## 🧩 Problem Statement

Heart disease remains one of the leading causes of death globally.  
By analyzing patient data (such as age, cholesterol, blood pressure, and chest pain type), this model aims to predict whether an individual is likely to have heart disease.

**Task Type:** Binary Classification  
**Target Variable:** `num`  
- `0` → No Heart Disease  
- `1` → Heart Disease Present

---

## 🧠 Project Workflow

### 1️⃣ Understanding the Dataset
- Medical attributes are analyzed to understand relationships with the target variable.
- Explored dataset distributions, feature correlations, and outlier patterns.

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized relationships between attributes like **age, sex, chest pain type (cp), resting blood pressure (trestbps)**, and **cholesterol (chol)**.
- Identified class imbalance and major contributing factors to heart disease.

### 3️⃣ Data Preprocessing
- Encoded categorical variables.
- Normalized numerical features for model stability.
- Handled missing values (if any) and prepared training/testing splits.

### 4️⃣ Model Building
Implemented multiple supervised learning algorithms for performance comparison:
- **Logistic Regression** — as a baseline model.
- **Random Forest Classifier** — for ensemble learning and feature importance.

### 5️⃣ Model Evaluation
Used standard classification metrics:
- **Accuracy**
- **Precision, Recall, F1-score**
- **Confusion Matrix**
- **ROC Curve & AUC**

### 6️⃣ Insights & Results
- Logistic Regression served as a strong interpretable baseline.
- Random Forest achieved the best performance by capturing non-linear relationships.
- Feature importance analysis revealed:
  - Chest pain type, resting blood pressure, and cholesterol level were key predictors.

---

## 🗂️ Project Structure
```
/AI_in_Healthcare_Building_a_Life_Saving_Heart_Disease_Predictor
├── AI_in_Healthcare_Building_a_Life_Saving_Heart_Disease_Predictor.ipynb
├── heart_disease_data.csv # Dataset (if applicable)
├── README.md # Project documentation
└── models/ # (optional) Saved trained models
```

---

## ⚙️ Tech Stack

| Category | Tools |
|-----------|--------|
| **Language** | Python (3.8+) |
| **Libraries** | NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn |
| **IDE** | Jupyter Notebook |
| **ML Algorithms** | Logistic Regression, K-NN,SVM, Random Forest |

---

## 📊 Key Outcomes

- Understood classification fundamentals and medical data preprocessing.
- Applied **EDA** to uncover class-specific health insights.
- Compared multiple models and tuned parameters for optimal prediction.
- Demonstrated that **AI can identify potential heart disease risks** with high accuracy.

---

## 🔍 Future Improvements

- Integrate more features (diet, lifestyle, family history).
- Deploy model via **Flask / Streamlit** for real-time patient prediction.
- Extend to multi-class problems (predicting severity levels).

---


⭐ *If you found this project insightful, consider giving it a star on GitHub!*
