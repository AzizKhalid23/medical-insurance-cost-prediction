# medical-insurance-cost-prediction
# Medical Insurance Cost Prediction

This project predicts **medical insurance charges** using demographic and lifestyle information.  
It demonstrates an end-to-end machine learning workflow, from data exploration and preprocessing to model training, evaluation, and interpretation.

---

## Dataset
- **Source:** Kaggle – Medical Insurance Cost Prediction
- **Rows:** 1,338
- **Features:**
  - `age`
  - `sex`
  - `bmi`
  - `children`
  - `smoker`
  - `region`
- **Target:** `charges` (medical insurance cost)

---

## Project Workflow
1. Data loading and initial exploration
2. Exploratory Data Analysis (EDA)
3. One-hot encoding for categorical variables (`sex`, `smoker`, `region`)
4. Train/Test split (80/20)
5. Feature scaling (StandardScaler) for linear models
6. Model training:
   - **Linear Regression** (baseline)
   - **Random Forest Regressor** (final model)
7. Model evaluation using **MAE**, **RMSE**, and **R²**
8. Visual analysis (residuals, feature importance)

---

## Models & Results (Summary)
- **Linear Regression**
  - Serves as a baseline model
  - Captures linear relationships
- **Random Forest Regressor**
  - Handles non-linear relationships and feature interactions
  - Achieved better performance than the baseline
  - Explains a high proportion of variance in insurance charges

**Best Model:** Random Forest Regressor (R² ≈ 0.86)

---

## Key Insights
- **Smoking status** is the strongest predictor of higher insurance costs.
- **Age** and **BMI** significantly increase insurance charges.
- Geographic region has a relatively minor effect compared to lifestyle factors.

