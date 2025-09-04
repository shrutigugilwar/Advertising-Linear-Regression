# Advertising Linear Regression

This project predicts **sales** based on advertising budgets using **multi-feature Linear Regression**.

---

## **Dataset**

- **Features:**
  - `TV` → Advertising budget for TV (in thousands)
  - `Radio` → Advertising budget for Radio (in thousands)
  - `Newspaper` → Advertising budget for Newspaper (in thousands)
- **Target:** `Sales` (units sold)
- **Rows:** 200

---

## **Project Overview**

- Multi-feature Linear Regression model trained on `TV`, `Radio`, and `Newspaper`.
- Model predicts `Sales` for given advertising budgets.
- Includes a **sample test prediction** before visualization.
- **Visualization** compares actual vs predicted sales.

---

## **Usage**

1. Upload `Advertising.csv` to your local environment or Colab.
2. Run `advertising_lr.ipynb`.
3. Model outputs:
   - Mean Squared Error (MSE)
   - R² Score
   - Sample sales prediction
4. **Visualization:** Shows a scatter plot of actual vs predicted sales.

---

## **Sample Prediction**

Example:  

| TV Budget | Radio Budget | Newspaper Budget | Predicted Sales |
|-----------|--------------|----------------|----------------|
| 150       | 30           | 20             | 21.5           |

> Note: The actual predicted value may vary slightly depending on the training/test split.

---

## **Visualization**

![Actual vs Predicted Sales](images/actual_vs_predicted.png)

- **Blue dots:** Actual sales from test data  
- **Red line:** Perfect prediction line (y = x)  
- This visualization helps understand how well the model predicts sales.

---

## **Conclusion**

- Linear Regression provides a **simple and effective baseline** for predicting sales from advertising budgets.  
- **R² Score** is usually high (>0.9), indicating strong predictive power.  
- Future improvements can include:
  - Feature selection for better performance
  - Advanced regression models like Random Forest or XGBoost for even more accuracy

---

## **Author**

- **Shruti Gugilwar** – GitHub: https://github.com/shrutigugilwar
