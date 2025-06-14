# 🏍️ MotoGP Lap Time Prediction

This project is part of a Kaggle regression challenge focused on predicting MotoGP lap times using rich rider, bike, and circuit data.

## 🚀 Objective

To build a machine learning model that accurately predicts `Lap_Time_Seconds` using training data with over 1.9 million rows and 44+ features.

## 📊 Dataset Overview

- **Train shape:** (1,914,056 rows × 45 columns)
- **Test shape:** (546,874 rows × 44 columns)
- The dataset includes features such as:
  - Rider information
  - Bike specifications
  - Circuit length and conditions
  - Tire compounds
  - Weather and temperature
  - Career stats (podiums, wins, starts, finishes)

## 🧠 ML Pipeline

- **Preprocessing:**
  - Numerical: Imputation with mean + StandardScaler
  - Categorical: Imputation with constant + OneHotEncoding
- **Model used:** `RandomForestRegressor`
- **Evaluation Metric:** RMSE (Root Mean Squared Error)

## 📈 Results

- ✅ **Kaggle Public Leaderboard RMSE:** `0.62939`
- The model achieves a strong balance between performance and generalization.

- The dataset and problem statement are available from the official Kaggle competition:  
🔗 [Burnout Datathon – IEEE CSMUJ](https://www.kaggle.com/competitions/burnout-datathon-ieeecsmuj)


## 🔗 Notebook Link

> 📎 [View Full Kaggle Notebook](https://www.kaggle.com/your-kaggle-username/your-notebook-slug)


---


## 📌 Future Improvements

- Try XGBoost or LightGBM
- Hyperparameter tuning with RandomizedSearchCV or Optuna
- Use SHAP for feature interpretability

## 🙌 Acknowledgments

Thanks to Kaggle and the competition organizers for providing this rich dataset and challenge.


