# 💊 Medicine Risk Analysis & Classification

## 📌 Project Overview
This project analyzes a dataset of **11,000+ medicines** to understand patterns in medicine composition, user reviews, and potential risk indicators.  
It combines **Python and Machine Learning** to classify medicines into **high-risk** and **low-risk** categories based on side effect likelihood.

---

## 📊 Dataset
- **Source:** Kaggle – Medicine Details Dataset
- **Records:** ~11,000
- **Columns include:**  
  - Medicine Name  
  - Salt Composition  
  - Uses  
  - Manufacturer  
  - Excellent / Average / Poor Review %

## 🔍 Exploratory Data Analysis (EDA)
- Distribution of review percentages  
- Manufacturer analysis: top producers  
- Word clouds for:
  - Medicine uses
  - Salt composition
- Key insights:
  - Medicines with more complex compositions tend to have lower reviews  
  - Excellent Review % strongly correlates with low-risk medicines

---

## 🛠 Feature Engineering
- **Ingredient Count:** Number of salts per medicine (derived from composition)  
- **Risk Flag:** Binary classification based on Poor Review %  
  - High Risk: Poor Review % > 30  
  - Low Risk: Otherwise  
## 🤖 Machine Learning
- **Model:** Logistic Regression  
- **Features:**  
  - Ingredient count  
  - Excellent Review %  
- **Target:** High-risk (1) / Low-risk (0)  

**Performance Metrics:**
| Metric | Value |
|--------|-------|
| Accuracy | 78% |
| High-Risk Recall | 62% |
| High-Risk Precision | 75% |

---
## 📈 Key Insights
- Excellent Review % is a strong predictor of low-risk medicines  
- Ingredient complexity adds predictive value  
- Logistic Regression effectively identifies low-risk medicines and reasonably predicts high-risk medicines

---
