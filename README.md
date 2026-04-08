#  House Price Classification using Mixture of Experts (MoE)

This project focuses on classifying house prices into three categories: **Low, Medium, and High** using advanced machine learning techniques.

---

##  Objective

The main objective is to improve classification performance by implementing a **Mixture of Experts (MoE)** model, which combines multiple specialized models with a gating mechanism.

---

##  Models Used

* Logistic Regression
* Random Forest
* Gradient Boosting
* CatBoost
* Mixture of Experts (MoE)

---

##  Methodology

* Data preprocessing and feature engineering
* Handling outliers using clipping
* Creating target classes using quantiles (Low, Medium, High)
* One-vs-Rest strategy for expert models
* Combining predictions using a gating model

---

##  Results

* Best baseline model: **CatBoost (~83%)**
* MoE model accuracy: **~84.6%**
* MoE improved performance compared to individual models

---

##  Explainable AI (XAI)

SHAP was used to interpret model predictions and understand feature importance.

### Key Features:

* GrLivArea
* OverallQual
* GarageArea
* YearBuilt

---

##  Conclusion

The Mixture of Experts approach improved classification performance by allowing each model to specialize in a specific class, resulting in better overall accuracy.

---

##  Tools & Libraries

* Python
* Pandas, NumPy
* Scikit-learn
* CatBoost, XGBoost
* SHAP
* Matplotlib

---

##  Project Structure

* `prediction.ipynb` → Main notebook
* `README.md` → Project description

---
## Developer

Lena Alshammari 

 This project demonstrates advanced machine learning, ensemble techniques, and model explainability.
