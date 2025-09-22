# 📊 Customer Churn Prediction (Telco Dataset)

![Churn Banner](https://img.shields.io/badge/Customer-Churn-red?style=for-the-badge)  
![ML](https://img.shields.io/badge/Machine%20Learning-blue?style=for-the-badge)  

---

## 🔹 Project Overview  
This project predicts **customer churn** (whether a customer will leave or stay) using the **Telco Customer Churn dataset**.  
Through **EDA, resampling, and ML models**, the project identifies customers at risk of leaving and provides actionable insights for improving customer retention.  

---

## 🔹 Project Story   

**Situation:**  
A telecom company with **7,043 active customers** was facing **high churn (~27%)**, resulting in a potential **$1M+ annual revenue loss**. Leadership lacked visibility into *which customers were likely to leave* and *why*.  

**Task:**  
Develop a **machine learning solution** to:  
- Predict churn with high accuracy.  
- Identify key churn drivers.  
- Enable targeted retention strategies to minimize revenue leakage.  

**Action:**  
- Conducted **EDA** and discovered clear churn patterns:  
  1. Customers using **electronic check payments** churned the most.  
  2. **Month-to-month contract** customers had much higher churn rates than long-term contracts.  
  3. Lack of **online security** and **tech support** strongly correlated with churn.  
  4. **Non-senior citizens** were more likely to churn compared to seniors.  
- Balanced the dataset using **SMOTEENN** to handle class imbalance.  
- Built and evaluated **Decision Tree** and **Random Forest** models.  

**Result:**  

- 📌 **Quick EDA Insights**:

Customers paying via Electronic Check churn more.

Month-to-month contracts show the highest churn.

Lack of Tech Support & Online Security increases churn risk.

Non-senior citizens are more likely to churn.

- ✅ **Decision Tree Model**  
  Confusion Matrix:  
[[477 63]

[ 14 620]]

 Accuracy: **93%**  
 Very strong recall & precision for churn prediction.  

- ✅ **Random Forest Model**  
Confusion Matrix:
[[478 40]

[ 27 625]]

 Accuracy: **94%**  
 Balanced performance with fewer false positives.  

- Business simulations showed that retaining even **10% of high-risk customers (~140 people)** could save **$100K+ annually**.  
- Delivered a **production-ready churn prediction model** (`model.sav`) that can be integrated into CRM systems for real-time customer risk alerts.  

---

## 🔹 Business Impact  
✅ **Retention-focused strategy** → Early warning system for churners.  
✅ **Revenue protection** → Saving even 10% of churners can protect **six-figure revenues**.  
✅ **Data-driven decision-making** → Clear visibility into churn drivers (contract type, payment method, support services).  
✅ **Scalable solution** → Ready to integrate into CRM for proactive retention.  

---

## 🔹 Tools & Technologies  
- 🐍 Python (Pandas, NumPy, Scikit-learn, Imbalanced-learn)  
- 📊 Visualization (Matplotlib, Seaborn)  
- ⚖️ Resampling (SMOTEENN)  
- 🌳 ML Models (Decision Tree, Random Forest)  
- 💾 Model Deployment (Joblib/Pickle)  
- 📝 Jupyter Notebook  

---

## 🔹 Author & Contact  
**Author**: Manav Agarwal  
📧 **Email**: *agarwalmanav1202@gmail.com*  
🔗 **LinkedIn**: [linkedin.com/in/manav-agarwal-363420384](https://www.linkedin.com/in/manav-agarwal-363420384)  
💻 **GitHub**: [github.com/manav-agarwal12](https://github.com/manav-agarwal12)

---
