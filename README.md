# ❤️ Heart Attack Prediction

---

## 📌 Project Overview

This project uses machine learning to predict the likelihood of a heart attack based on patient medical data. The dataset was sourced from Kaggle:

🔗 [Heart Attack Analysis & Prediction Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)

All analysis and model training was performed in **Python** using libraries such as Scikit-learn, TensorFlow, Pandas, and Seaborn.

---

## 🧠 Features Analyzed

- `age` – Patient age  
- `sex` – Gender (1 = Male, 0 = Female)  
- `exang` – Exercise-induced angina  
- `ca` – Major blood vessel narrowing (0–3)  
- `cp` – Chest pain type  
- `trtbps` – Resting blood pressure  
- `chol` – Cholesterol level  
- `fbs` – Fasting blood sugar  
- `restecg` – Resting ECG results  
- `thalach` – Maximum heart rate achieved  

These features were used to explore trends and train predictive models.

---

## 📊 Key Insights

### 🔍 Correlation Analysis

A heatmap showed that the most important features for predicting heart attacks include:
- `thal`, `cp`, `ca`, `exang`, `oldpeak`, `thalach`, `slp`, `sex`, and `age`

### 📈 Visual Analysis

- **Women** are statistically more prone to heart attacks.
- Most data comes from patients aged **51–62**.
- Highest-risk age groups: **39–44** and **49–54**.
- **Men** more frequently report chest pain, despite lower relative risk.

Visuals were created with `Seaborn` and `Matplotlib`.

---

## 🤖 Machine Learning Models

### ✅ Neural Network (Keras)
- Architecture: 64 → 32 → 1 neurons
- Activation: `ReLU`, `Sigmoid`
- Accuracy: **~83.3%**

### 🌳 Random Forest (Scikit-learn)
- Estimators: 10
- Accuracy: **~83.6%**

Only the most correlated features were used, improving accuracy compared to using all columns.

---

## 🧰 Technologies Used

- **Python**  
- **Pandas**, **Seaborn**, **Matplotlib** – Data analysis and visualization  
- **Scikit-learn** – Random Forest, data splitting, metrics  
- **TensorFlow / Keras** – Neural Network  
- **Jupyter Notebook** – Interactive coding

---

## 🗂️ Repository Content

- `Atak_serca.ipynb` – Complete notebook with data exploration and model training  
- `README.md` – This project documentation  

---

If you'd like to contribute, feel free to fork the repository or open an issue.  
Thanks for checking it out!
