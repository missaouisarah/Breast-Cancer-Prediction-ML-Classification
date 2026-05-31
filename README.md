# Breast-Cancer-Prediction-ML-Classification
> *Can a machine learn to save a life?*  A full end-to-end ML pipeline applied to one of healthcare's most critical challenges — distinguishing malignant from benign tumors based on cellular measurements.
**What makes this project rigorous :**
- 🔍 **4-method feature selection** (ANOVA Filter, RFECV, Forward/Backward Selection, Lasso L1) → final features = intersection of all methods
- ⚖️ **Model comparison** : Logistic Regression vs Random Forest vs SVM
- 🎯 **Recall prioritized over Accuracy** — because a false negative is not a wrong number, it is a missed diagnosis
- ✅ **Result** : 97.06% Recall · 98.24% Accuracy with Logistic Regression on 5 features

| Tool | Purpose |
|------|----------|
| `Python` · `Scikit-Learn` | Modeling & evaluation |
| `Pandas` | EDA & data exploration |
| `RFECV` · `Lasso L1` · 'Backward selection' · 'Forward Selection' | Feature selection |
| `Confusion Matrix` · `Recall` | Metric-driven evaluation |
[![Open in Colab](https://colab.research.google.com/drive/1veHpFXVyh0k0SOLeOmn_nNlUyGc2zm5-?usp=sharing)]
