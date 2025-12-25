# COVID-19 Future Forecasting Using Supervised ML Models

This project implements the research for forecasting COVID-19 threatening factors (Confirmed Cases, Deaths, and Recoveries) using time-series regression models.

## 🧠 Overview
The study demonstrates the capability of supervised Machine Learning models to anticipate upcoming COVID-19 trends. By analyzing historical daily data from the **Johns Hopkins University (JHU)** repository, the project predicts the scenario for the next 10 days.

## 🚀 Models Implemented
As per the research paper, four standard forecasting models were utilized:
1. **Exponential Smoothing (ES):** The top-performing model for univariate time-series data.
2. **Linear Regression (LR):** Establishing linear relationships between time (days) and case counts.
3. **LASSO Regression:** Enhancing linear models using L1 regularization to reduce errors.
4. **Support Vector Machine (SVM):** A non-parametric technique (showed poor performance on this specific dataset as noted in the paper).

## 📊 Evaluation Metrics
Models are evaluated based on:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-Squared ($R^2$) Score
- Root Mean Square Error (RMSE)

## 📈 Key Findings
- **Exponential Smoothing (ES)** outperforms other models in long-term forecasting accuracy.
- **LR and LASSO** perform consistently well for daily trend identification.
- **SVM** struggled to capture the pandemic's exponential nature given the specific dataset constraints.

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- Scikit-Learn (LR, LASSO, SVM)
- Statsmodels (Exponential Smoothing)
- Matplotlib (Data Visualization)

---
**Author:** Zahra Mohaghegh  
*M.Sc. in Artificial Intelligence & Robotics*
