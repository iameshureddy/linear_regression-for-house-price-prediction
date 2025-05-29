# 🏠 House Price Prediction using Linear Regression

## 📌 Objective
To implement and understand Simple and Multiple Linear Regression on a real-world housing dataset using Python, and evaluate the model using common regression metrics.

---

## 📁 Dataset
Source: [Kaggle - House Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)  
File Used: `data.csv`

---

## 🧠 Concepts Covered
- Simple Linear Regression (one feature)
- Multiple Linear Regression (multiple features)
- Model evaluation using MAE, MSE, R² score
- Coefficient interpretation
- Data preprocessing
- Correlation analysis
- Visualization of regression line

---

## 📊 Libraries Used
- pandas for data manipulation
- matplotlib, seaborn for visualization
- sklearn for modeling and evaluation

---

## 🔍 Evaluation Metrics
| Metric | Description |
|--------|-------------|
| MAE | Mean Absolute Error |
| MSE | Mean Squared Error |
| R²  | Coefficient of Determination |

---

## 📈 Results

### Simple Linear Regression (Area vs Price)
- MAE: 52831.12
- MSE: 6423524092.3
- R² Score: 0.65

### Multiple Linear Regression (Area, Bedrooms, Bathrooms)
- MAE: 41560.23
- MSE: 5032137834.7
- R² Score: 0.74



## 📸 Visualization

![Simple Regression Plot](simple_regression_plot.png)


---

## ✅ How to Run
```bash
pip install pandas matplotlib seaborn scikit-learn
python linear_regression_task.py


