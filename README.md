Got it! Here's a **concise, polished GitHub-ready README** in proper markdown format with badges, quick setup instructions, and a professional first-look style:

---

# Heart Disease Prediction 🫀

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Libraries](https://img.shields.io/badge/Dependencies-Pandas%2C%20NumPy%2C%20Sklearn%2C%20Matplotlib%2C%20Seaborn-yellow)]()

---

## 🚀 Project Overview

Predict the **10-year risk of coronary heart disease (CHD)** using **logistic regression**.
Binary classification:

* `0` → no risk
* `1` → at risk

**Goal:** Provide insights into patient health metrics that indicate CHD risk.

---

## 📊 Dataset

* **Source:** Framingham Heart Study (`framingham.csv`)
* **Rows / Columns:** 4,240 × 16
* **Target Variable:** `TenYearCHD`
* **Features used:**

  * `age`, `Sex_male`, `cigsPerDay`, `totChol`, `sysBP`, `glucose`

**Preprocessing:**

* Drop irrelevant columns & rows with missing values
* Scale features with `StandardScaler()`

---

## 🛠️ Tools & Techniques

### Libraries

* **Pandas / NumPy:** Data handling & numerical operations
* **Matplotlib / Seaborn:** Visualization & plots
* **Scikit-learn:** ML modeling, preprocessing, evaluation
* **Statsmodels / SciPy:** Statistical modeling & optimization (optional)

### Techniques

* **EDA:** `head()`, `shape`, `value_counts()`
* **Data Cleaning:** Column removal, renaming, handling missing values
* **Feature Selection:** Selecting 6 relevant features
* **Scaling:** `StandardScaler()`
* **Visualization:** Countplots, confusion matrix
* **Model Evaluation:** Accuracy, confusion matrix, classification report

---

## 🧠 Model

* **Algorithm:** Logistic Regression
* **Train/Test Split:** 70/30 (`random_state=4`)
* **Metrics:** Accuracy, confusion matrix, classification report

---

## 🎨 Visualizations

* Target class distribution
* Confusion matrix
* Feature distributions (via EDA)

---

## ⚡ Quick Setup

1. **Clone the repo:**

```bash
git clone https://github.com/GhadaFaress/Heart_Disease_Prediction.git
cd Heart_Disease_Prediction
```

2. **Install dependencies:**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. **Run Notebook:**

```bash
jupyter notebook heart_disease.ipynb
```

---

## 📈 Workflow Summary

**Load Data → Clean Data → Feature Selection → Scale Features → Train Model → Evaluate Performance → Visualize Results**

---

## 🔍 Results

* Predicts 10-year CHD risk
* Provides insights into patient demographics and health metrics
* Helps identify key factors contributing to CHD


