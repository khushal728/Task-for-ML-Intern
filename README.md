# DON Concentration Prediction using Spectral Data

This project aims to predict DON (vomitoxin) concentration in corn samples using spectral data. The dataset contains 449 features representing reflectance values across various bands and the target variable vomitoxin_ppb.

## 🚀 Project Overview

Objective: Predict DON concentration accurately using machine learning models.

Tech Stack: Python, Pandas, NumPy, PyTorch, Scikit-learn, Streamlit (Optional for UI).

## 📊 Dataset Details

Total Features: 449 (including target column)

Target Variable: vomitoxin_ppb

Key Challenge: Handling high-dimensional data and improving prediction accuracy.


## 🛠️ Steps to Run the Project

1. Environment Setup

Install the required dependencies:
```
pip install pandas numpy scikit-learn torch
```

2. Data Preprocessing

Removed outliers using IQR method.

Applied MinMaxScaler for data normalization.

3. Dimensionality Reduction

Used PCA to reduce features while retaining 95% variance.

4. Model Training

Implemented a Random Forest Regressor as the baseline model.

Developed an Attention-Based Model in PyTorch for improved performance.

5. Evaluation Metrics

MAE (Mean Absolute Error): 12.32

RMSE (Root Mean Squared Error): 18.21

R² Score: 0.89

## 🚨 Key Highlights

✅ Effective feature reduction with PCA✅ Improved accuracy using Attention Mechanism✅ Optional Streamlit App for user interaction


## 🤝 Contribution

Feel free to contribute to this project by suggesting improvements or exploring alternative models. Fork the repository, make your changes, and submit a pull request.

📧 Contact

For queries or collaborations, reach out at [Khushal Joshi / Khushalj2003@gmail.com].






















