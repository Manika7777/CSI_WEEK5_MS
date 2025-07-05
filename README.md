# CSI_WEEK5_MS
# 🏡 House Price Prediction using Linear Regression

This project predicts house sale prices using **Linear Regression** on the [Kaggle: House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) dataset.

📈 Final model performance on validation set:
- 🧮 **MSE**: 631,201,196.72  
- 📏 **RMSE**: 25,123.72  
- 📈 **R² Score**: 0.9177  

---

## 📦 Project Files

| File Name                     | Description                                |
|------------------------------|--------------------------------------------|
| `House_Price_Prediction.ipynb` | Main Jupyter Notebook (Colab compatible)  |
| `house_price_predictions.csv` | Submission file with predicted sale prices |
| `README.md`                  | Project documentation                      |

---

## 🚀 How to Use

1. **Open in Google Colab**  
   Upload the notebook and dataset ZIP (`house-prices-advanced-regression-techniques.zip`)

2. **Run all cells** to:
   - Preprocess data
   - Engineer features
   - Train & evaluate a linear regression model
   - Visualize performance
   - Export final predictions

---

## 🧪 Workflow Overview

### 1. Data Handling
- Combines `train.csv` and `test.csv` for uniform preprocessing
- Handles missing values:
  - Categorical → `'None'`
  - Numerical → median

### 2. Feature Engineering
- `TotalSF`: Total square footage  
- `TotalBath`: Combined bathroom count  
- `HouseAge`: Difference between `YrSold` and `YearBuilt`

### 3. Encoding
- One-hot encoding of categorical variables

### 4. Model Training
- Algorithm: `LinearRegression` from `sklearn`
- 80/20 train-validation split
- Evaluation using MSE, RMSE, and R² score

### 5. Visualization
- Actual vs Predicted (Scatter, Line)
- Residual distribution
- Correlation heatmap

---

## 📊 Results

```
📊 Model Evaluation Summary
-----------------------------------
🧮 Mean Squared Error (MSE):        631,201,196.72
📏 Root Mean Squared Error (RMSE):  25,123.72
📈 R² Score (Coefficient of Determination): 0.9177
```

---

## 📈 Visual Insights

- 📌 **Residuals** follow a normal-like distribution  
- 🟢 **Strong correlation** between predicted and actual prices  
- 🔥 Achieved **high R²** with basic Linear Regression through preprocessing

---

## ✅ Requirements

✅ Google Colab Ready (no installation needed)  

---

## 👩‍💻 Author

**Manika Sarkar**
