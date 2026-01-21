# Wine-Quality-EDA-ML
Exploratory Data Analysis and Machine Learning on Red Wine Quality Dataset
# 🍷 Wine Quality Analysis (EDA & Machine Learning)

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** and **Machine Learning** using the **Red Wine Quality Dataset**.  
The goal is to understand the factors affecting wine quality and explore challenges such as **class imbalance** in real-world datasets.

---

## 📊 Dataset Information
- Dataset: Red Wine Quality Dataset
- Source: UCI Machine Learning Repository
- Target Variable: `quality` (scores from 3 to 8)
- Features: 11 physicochemical attributes (acidity, alcohol, sulphates, etc.)

---

## 🔍 Exploratory Data Analysis (EDA)
Key EDA steps performed:
- Data inspection and cleaning
- Statistical summary of features
- Distribution analysis of wine quality
- Detection of **class imbalance**
- Feature correlation analysis
- Data visualization using Matplotlib & Seaborn

### 📌 Key Insight:
The dataset is **imbalanced**, with wine quality scores **5 and 6 dominating**, while extreme quality values (3 and 8) are underrepresented.  
This reflects real-world wine production but can bias classification models.

---

## 🤖 Machine Learning Approach
Different modeling perspectives were explored:

### 1️⃣ Classification
- Multi-class classification on wine quality
- Handling imbalance using:
  - `class_weight='balanced'`
  - Discussion of SMOTE (Synthetic Minority Oversampling Technique)

### 2️⃣ Regression (Recommended)
- Treating wine quality as a continuous variable
- Avoids class imbalance issues
- More suitable for real-world prediction tasks

---

## ⚖️ Handling Class Imbalance
- Used `class_weight` to penalize misclassification of minority classes
- Compared conceptual differences between:
  - Upsampling
  - SMOTE
  - Class-weighted learning

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure
