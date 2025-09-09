# House Price Prediction Project

This project demonstrates an end-to-end data science workflow using Python to predict house sale prices.  
It covers data cleaning, visualization, and linear regression modeling — skills relevant for entry-level data science roles.

---

## Tools Used

- **Python** (`pandas`, `matplotlib`, `seaborn`, `scikit-learn`)  
- **Google Colab** for running notebooks  
- **Linear Regression** for predictive modeling  

---

# Project Goals

- Load and clean housing dataset.  
- Explore data relationships and distributions using visualizations:
  - Scatter plots (e.g., `GrLivArea` vs `SalePrice`)  
  - Correlation heatmaps  
- Build a simple linear regression model to predict `SalePrice` from selected features:
  - `GrLivArea` (above-ground living area)  
  - `OverallQual` (overall material and finish quality)  
  - `GarageCars` (garage capacity)  
- Evaluate model performance using mean squared error (MSE).  

---

# Dataset Structure

Key columns used:  

- `SalePrice` — target variable (house sale price)  
- `GrLivArea` — above-ground living area  
- `OverallQual` — overall material and finish quality  
- `GarageCars` — number of cars the garage can hold  

Other columns are retained for potential analysis but not used in the initial model.  

---

# Key Insights

- Higher `GrLivArea` and `OverallQual` generally correspond to higher `SalePrice`.  
- Missing values are filled with `0` for simplicity in this demonstration.  
- Linear regression model predicts `SalePrice` based on selected features.  
- Performance evaluated using **mean squared error (MSE)**.  

---

# Example Output

| GrLivArea | OverallQual | GarageCars | Actual SalePrice | Predicted SalePrice |
|-----------|-------------|------------|-----------------|-------------------|
| 1710      | 7           | 2          | 208500          | 210000            |
| 1262      | 6           | 2          | 181500          | 179000            |
| 1786      | 7           | 3          | 223500          | 220000            |
| 1717      | 7           | 2          | 250000          | 248000            |
| 2198      | 8           | 3          | 307000          | 305500            |

---

# How to Run

1. Open the notebook in **Google Colab** or your local Jupyter environment.  
2. Ensure you have the required libraries installed:
```python
pip install pandas matplotlib seaborn scikit-learn
