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

## 📔 Colab Notebook

🔗 [View Full Notebook on Google Colab](https://colab.research.google.com/#fileId=https%3A//storage.googleapis.com/kaggle-colab-exported-notebooks/shouryakrishna/shritech.0768ca1b-9c85-402c-b430-7d181fa3c2d5.ipynb%3FX-Goog-Algorithm%3DGOOG4-RSA-SHA256%26X-Goog-Credential%3Dgcp-kaggle-com%2540kaggle-161607.iam.gserviceaccount.com/20250614/auto/storage/goog4_request%26X-Goog-Date%3D20250614T155712Z%26X-Goog-Expires%3D259200%26X-Goog-SignedHeaders%3Dhost%26X-Goog-Signature%3D8a94c25c3258ad15a92905f063f4119717435d16af4b439742a0aadbe73bc545733ceb47d50ec0af3d5236974a15114a31424f82621dc9ded8dc0bdee020b12b82137ea8e8d31c9d42617e59b05aa0a1c09daeec3806c0c340342deaed68fd71852b9f716166b34eb77021761e765e35ba2d5a61516a817138b6c9ef20dac7e87f2edd3db0747042db3465f15a321f2d10a3105f9c8ab20a9f5652b189ac6056d14ec2764551d46649fc8682f40e908c05beeeda1943d4b15cbd772f4816b26a56035235ea3499cc00953cae883d9cf1aa5cd87ea0911c64bd27b06c0c714045c8975ec53ebb9047bd3454e69d46e99a54b8b9580def003263e8799db3169d87)



---


## 📌 Future Improvements

- Try XGBoost or LightGBM
- Hyperparameter tuning with RandomizedSearchCV or Optuna
- Use SHAP for feature interpretability

## 🙌 Acknowledgments

Thanks to Kaggle and the competition organizers for providing this rich dataset and challenge.


