# 🍷 Red Wine Quality Prediction Using Random Forest  
### *An Ensemble Learning Approach for Wine Quality Classification*  

---

## 📘 **Project Overview**

This project applies a **Random Forest Classifier** — an ensemble learning technique — to predict the **quality of red wine** based on its physicochemical attributes.  
By leveraging multiple decision trees and averaging their predictions, Random Forest reduces overfitting, enhances accuracy, and identifies key chemical factors that influence wine quality.  

> 🧠 **Goal:** Predict wine quality (score 0–10) from features like alcohol, acidity, sulphates, and more.

---


---

## 🧪 **Dataset Information**

The dataset contains **1,599 samples** of red wine from the *Vinho Verde* region of Portugal, with **11 input features** and **1 target label (`quality`)**.  

### 🔬 **Features:**
- `fixed acidity` – Non-volatile acids like tartaric acid  
- `volatile acidity` – Acetic acid levels (vinegar taste risk)  
- `citric acid` – Adds freshness and flavor  
- `residual sugar` – Sugar remaining post fermentation  
- `chlorides` – Salt content affecting taste  
- `free sulfur dioxide` & `total sulfur dioxide` – Preserve wine quality  
- `density` – Related to sugar/alcohol content  
- `pH` – Acidity level  
- `sulphates` – Antioxidant & microbial protection  
- `alcohol` – Alcohol percentage by volume  

### 🎯 **Target Variable:**
- `quality` (integer score 0–10) – Sensory rating by experts  

---

## 🧰 **Technologies Used**

| Category | Tools / Libraries |
|-----------|-------------------|
| **Language** | Python 🐍 |
| **Data Handling** | pandas, NumPy |
| **Visualization** | matplotlib, seaborn |
| **Machine Learning** | scikit-learn (RandomForestClassifier) |
| **Environment** | Jupyter Notebook / VS Code |

---

## 🚀 **Model Implementation**

### ⚙️ Steps:
1. **Data Loading & Cleaning** – Handle missing values, inspect distributions  
2. **Exploratory Data Analysis (EDA)** – Correlation heatmaps, boxplots, and pairplots  
3. **Feature & Target Selection** – Define independent (`X`) and dependent (`y`) variables  
4. **Train-Test Split** – 80% training, 20% testing  
5. **Model Training** – Random Forest with 1000 estimators (`n_estimators=1000`)  
6. **Model Evaluation** – Confusion matrix, classification report, accuracy score  

---

## 📊 **Key Visualizations**

- 🔥 **Correlation Matrix** – Identify relationships between variables  
- 🍷 **Boxplot (Alcohol vs Quality)** – Understand impact of alcohol on wine quality  
- 📈 **Pairplot (Selected Features)** – Multi-variable relationships  

*(Visual outputs stored in `/output` folder)*

---

## 🧮 **Model Performance**

| Metric | Training | Testing |
|:--------|:----------|:----------|
| **Accuracy** | ~99% | ~89–92% |
| **Evaluation** | Confusion Matrix, Precision, Recall, F1-score |

✅ **Observations:**
- The model generalizes well without severe overfitting.  
- `Alcohol` and `Volatile Acidity` were strong predictors of wine quality.  
- Random Forest effectively handled variance through ensemble averaging.

---

## 🎓 **Conclusion**

Random Forest proved to be a **robust and accurate ensemble method** for predicting wine quality.

- 🌲 **Robust & Accurate:** Combines multiple decision trees to improve reliability  
- 🧠 **Feature Importance:** Highlights which attributes most influence wine taste  
- 🔁 **Low Variance:** Performs consistently on unseen data  

> **Conclusion:** Random Forest is ideal for this classification problem — balancing accuracy, interpretability, and stability.

---

## ⚠️ **Disclaimer**

This project uses the **UCI Wine Quality Dataset (Red Wine)** for **educational and research purposes**.  
Model performance may vary on real-world or unseen wine datasets.

