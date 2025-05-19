## 🔍 Project Overview
This project builds a machine learning model to predict airline passenger satisfaction using demographic, flight, and service features.

## 🛠️ Features
- EDA with visualizations
- Data cleaning and preprocessing
- Feature engineering (aggregate, derived, interaction)
- Multiple ML models (Logistic Regression, Random Forest, XGBoost, etc.)
- Hyperparameter tuning with Optuna
- SHAP explainability
- Ensemble model for best performance

## 📊 Tech Stack
Python, pandas, scikit-learn, matplotlib, seaborn, XGBoost, LightGBM, SHAP, Optuna

## 🚀 How to Run
1. Clone the repo  
2. Install requirements with `pip install -r requirements.txt`  
3. Run `notebooks/airline_model_pipeline.ipynb` to see the workflow

## 📈 Results
Achieved high F1-score and balanced accuracy using an ensemble model. SHAP showed Online Boarding and Inflight Service as top predictors.

## 📄 License
MIT
