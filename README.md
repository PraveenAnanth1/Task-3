# Task-3
---

# 🔍 Breast Cancer Linear Regression

This project implements **Simple and Multiple Linear Regression** using the Breast Cancer dataset to predict the `area_mean` of a tumor based on other features like `radius_mean`, `texture_mean`, etc.

---

## 📦 Tools Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**

---

## 🎯 Objective
- Understand how to apply **Simple** and **Multiple Linear Regression**
- Visualize model performance and residuals
- Evaluate the model using:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - R² (R-squared score)

---

## 📁 Dataset
- Sample Breast Cancer dataset with features such as:
  - `radius_mean`, `texture_mean`, `area_mean`, `smoothness_mean`, etc.
- Target variable for prediction: **`area_mean`**

---

## 🔨 Steps
1. **Import and Preprocess** the dataset (drop ID and diagnosis).
2. **Split** data into training and testing sets.
3. Fit:
   - ✅ Simple Linear Regression (1 feature)
   - ✅ Multiple Linear Regression (multiple features)
4. **Evaluate** with MAE, MSE, R².
5. **Visualize**:
   - Scatter plot with regression line
   - Actual vs Predicted
   - Residual plot

---

## 📊 Plots Included
- 📈 Regression line plot (`radius_mean` vs `area_mean`)
- 🎯 Actual vs Predicted values
- 🧮 Residuals vs Predicted values

---

## 📌 Conclusion
- Simple regression helps understand single-variable impact.
- Multiple regression uses several features for better prediction.
- Visualization and metrics help interpret the model's quality and accuracy.

---
