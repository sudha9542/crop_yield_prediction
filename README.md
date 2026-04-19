# 🌾 Predicting Crop Yield Using Machine Learning: A Data-Driven Approach

### MSc Data Science | University of Hertfordshire | 7PAM2002

---

## 📌 Project Overview

This project builds a machine learning system that predicts **crop yield (tons/hectare)** using environmental and agricultural factors such as rainfall, temperature, soil type, fertilizer use, and irrigation. The system also uses **SHAP-based Explainable AI** to make predictions transparent and understandable for farmers and policymakers.

---

## 🎯 Aim

To develop accurate machine learning regression models for crop yield prediction and to explain model decisions using Explainable Artificial Intelligence (XAI) techniques.

---

## 📂 Repository Structure

    ├── crop_yield_prediction.ipynb   # Main Jupyter Notebook (full code)
    ├── FPR_topic_36_Final.docx       # Final Project Report
    ├── README.md                     # Project description

---

## 📊 Dataset

- **Source:** Kaggle — [Agriculture Crop Yield Dataset](https://www.kaggle.com/datasets/samuelotiattakorah/agriculture-crop-yield)
- **Size:** 1,000,000 rows | 10 features
- **Target Variable:** `Yield_tons_per_hectare`
- **Key Features:** Rainfall, Temperature, Soil Type, Crop Type, Fertilizer Used, Irrigation Used, Days to Harvest, Weather Condition

---

## 🔧 Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Model training & evaluation |
| SHAP | Explainable AI |
| Google Colab | Development environment |

---

## 🤖 Models Trained

| Model | R² Score | RMSE |
|-------|----------|------|
| Linear Regression | 0.9132 | 0.4993 |
| Decision Tree | 0.9122 | 0.5022 |
| Random Forest | 0.9129 | 0.5002 |
| Ridge Regression | 0.9132 | 0.4993 |

> ✅ All models achieved over **91% predictive accuracy**

---

## 🔍 Key Findings

- **Rainfall** is the most influential environmental factor affecting crop yield
- **Fertilizer usage** has the highest agricultural input impact (SHAP score ≈ 0.21)
- **Irrigation** is the second most important agricultural input (SHAP score ≈ 0.14)
- 5-Fold Cross Validation confirmed **stable and reliable** model performance across all folds
- Hyperparameter tuning confirmed baseline models were already near-optimal

---

## 📋 Project Pipeline

    Data Collection → EDA → Preprocessing → Model Training → Hyperparameter Tuning → Cross Validation → SHAP Analysis → Results

---

## 🚀 How to Run

1. Clone this repository
       git clone https://github.com/lakshmi-sudha-pandiri/crop-yield-prediction.git
2. Open `crop_yield_prediction.ipynb` in Google Colab or Jupyter Notebook
3. Upload your `kaggle.json` file to authenticate the dataset download
4. Run all cells in order

---

## 🌱 Future Work

- Test advanced models — XGBoost, LightGBM, Deep Learning
- Include satellite imagery and seasonal climate data
- Expand to multi-country datasets for global applicability
- Build a web application for real-time yield prediction

---

## 👩‍💻 Author

**Lakshmi Sudha Pandiri**
MSc Data Science — University of Hertfordshire
[GitHub Profile](https://github.com/lakshmi-sudha-pandiri)

---

## 📚 References

- Islam et al. (2024) — Crop yield prediction using ML, R²=0.9745 with XGBoost
- Kalmani et al. (2024) — CNN-LSTM deep learning model, R²=0.967
- Khosravani Shariati & Abbasi (2025) — Winter wheat yield prediction
- Asamoah et al. (2024) — Random Forest for maize yield prediction

---

> *"Combining agriculture knowledge with data science to build smarter, sustainable farming solutions"* 🌾
