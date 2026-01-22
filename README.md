# Housing Price Prediction with Feature Engineering

## Project Overview
This project focuses on predicting house prices using structured tabular data from the Kaggle Housing Prices dataset. The goal is to demonstrate a complete machine learning workflow with strong emphasis on feature engineering, model evaluation, and informed model selection.

---

## Dataset
- Source: Kaggle – Housing Prices: Advanced Regression Techniques
- Data Type: Structured tabular data
- Target Variable: `SalePrice`

---

## Project Objectives
- Perform exploratory data analysis to understand key factors influencing house prices
- Clean and preprocess structured housing data
- Apply feature engineering techniques to improve model performance
- Train and evaluate baseline regression models
- Select a final model based on validation performance
- Generate house price predictions on unseen test data

---

## Workflow
1. Introduction  
2. Project Objectives  
3. Import Libraries  
4. Load Dataset  
5. Exploratory Data Analysis (EDA)  
6. Data Cleaning  
7. Feature Engineering  
8. Train–Validation Split  
9. Model Training  
10. Model Evaluation  
11. Model Comparison  
12. Final Model Selection  
13. Final House Price Prediction  
14. Conclusion & Next Steps  

---

## Model Evaluation & Selection

Two baseline models were evaluated using validation data:

| Model | RMSE | R² |
|------|------|----|
| Linear Regression | 0.213 | 0.757 |
| Random Forest Regressor | 0.149 | 0.880 |

The Random Forest Regressor was selected as the final model based on superior validation performance and its ability to capture nonlinear relationships in structured housing data.

---

## Final Predictions
The selected Random Forest model was used to generate house price predictions on unseen test data. Predictions were produced on a log-transformed target and converted back to the original price scale for interpretability.

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- Git & GitHub

---

## Key Takeaways
- Feature engineering significantly impacts model performance in structured data problems
- Baseline models provide valuable performance benchmarks
- Validation-based evaluation helps ensure model generalization
- Tree-based models are effective for capturing nonlinear relationships in tabular data

---

## Author
Egahalemena Ufuoma Moses  
GitHub: https://github.com/ufuos10
