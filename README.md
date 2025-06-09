# Solar-Efficiency-ML-Predictor
# 🔆 Solar Efficiency Prediction System 🌞

A high-performance, ensemble-based machine learning solution to predict solar panel efficiency using environmental, electrical, and operational data.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Model](https://img.shields.io/badge/Model-Ensemble_LightGBM_XGBoost_CatBoost_RandomForest-green)
![Accuracy](https://img.shields.io/badge/Efficiency_Accuracy-89.689%25-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📊 Project Summary

This repository contains an end-to-end ML pipeline that:
- Preprocesses solar panel and environmental data
- Engineers robust features (power, resistance, irradiance, etc.)
- Trains state-of-the-art regressors (LightGBM, XGBoost, CatBoost, RandomForest)
- Combines them through **stacked ensemble modeling**
- Achieves **89.689% prediction efficiency** (R² score)

---

## 🚀 Achievements

✅ Achieved **89.689% efficiency** using advanced ensemble techniques  
✅ Performed extensive feature engineering with >25 derived features  
✅ Used robust cross-validation (5-Fold KFold CV)  
✅ Built a final Ridge Regression ensemble model on meta-learned predictions  
✅ Improved prediction RMSE by >3% over best individual model  

---

## 🛠️ Technologies Used

- Python 3.8+
- LightGBM
- XGBoost
- CatBoost
- Scikit-learn
- Pandas, NumPy
- Ridge Regression (Ensemble layer)
- RobustScaler (for normalization)

---

## 🧪 Model Training Overview

| Model         | CV RMSE (avg) | R² Score |
|---------------|---------------|----------|
| LightGBM      | ✅ Trained     | ~0.XXX   |
| XGBoost       | ✅ Trained     | ~0.XXX   |
| CatBoost      | ✅ Trained     | ~0.XXX   |
| RandomForest  | ✅ Trained     | ~0.XXX   |
| **Final Ensemble** | ✅ Trained     | **0.89689** |

---


