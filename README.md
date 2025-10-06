# 💳 Credit Card Fraud Detection — Smarter Banking with Machine Learning  

## 🧠 Project Overview  
This project tackles one of the toughest challenges in the financial world — detecting fraudulent credit card transactions.  
It’s built as a full end-to-end machine learning pipeline that mirrors what banks and fintech companies actually do to protect their customers.  

The goal is simple: **reduce financial loss** by spotting fraud early — and the model does exactly that.  
After multiple iterations and tuning, the optimized model **cut business costs from ~$20K (Logistic Regression)** to **~$12K (Random Forest + SMOTE tuned)**.  

---

## ⚙️ What This Project Does  
- **Explores and cleans large-scale financial data** with over 280K+ transactions.  
- **Identifies extreme imbalance** (fraudulent cases <1%) and corrects it using **SMOTE**.  
- **Trains multiple ML models** — from basic Logistic Regression to advanced ensemble methods like Random Forest, XGBoost, and CatBoost.  
- **Evaluates models** using precision, recall, F1-score, ROC-AUC, and cost impact.  
- **Explains predictions** using **SHAP values**, so we understand *why* the model flags a transaction as fraud.  

---

## 🧩 Key Highlights  
✅ Cleaned data and handled imbalance effectively using SMOTE.  
✅ Experimented with multiple models and hyperparameter tuning.  
✅ Visualized feature importances and correlation to spot hidden patterns.  
✅ Interpreted results with SHAP for transparency and trust.  
✅ Reduced financial risk while maintaining high recall on fraud cases.  

---

## 📊 Results Snapshot  
| Model | ROC-AUC | F1-Score | Estimated Business Cost |
|--------|----------|----------|--------------------------|
| Logistic Regression | 0.89 | 0.77 | ~$20,000 |
| Random Forest (SMOTE Tuned) | **0.97** | **0.86** | **~$12,000** |

---

## 🧠 Tech Stack  
**Languages:** Python  
**Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, lightgbm, catboost, shap, imbalanced-learn, category-encoders  

---

## 💡 What Makes This Project Different  
Instead of chasing the highest accuracy, I compared multiple models (Logistic Regression, Random Forest, XGBoost, LightGBM, CatBoost) based on **both performance and cost impact**.  
Through careful tuning and balancing using **SMOTE + Random Forest**, the model **reduced estimated business loss from around $20K to nearly $12K** — a clear win from both technical and financial perspectives.  
  

The pipeline shows:  
- How data preprocessing impacts real-world cost.  
- How explainable AI builds trust in ML systems.  
- How ensemble models outperform simple classifiers in production settings.  
 

