# 🚗 Used Car Price Prediction with Python

Predict used car prices using Multiple Linear Regression (MLR) with **scikit-learn**.

### 📂 Dataset Features
- Year of Manufacture (`make_year`)
- Mileage per Liter (`mileage_kmpl`)
- Engine Capacity (`engine_cc`)
- Other Categorical Features (fuel type, brand, etc.)

### ⚙️ Tools Used
- `pandas` ➔ Data manipulation
- `scikit-learn` ➔ Model building (Pipeline, OneHotEncoder, Linear Regression)
- `matplotlib` & `seaborn` ➔ Visualization
- `numpy` ➔ Numerical operations

### 📊 Results
- **R² Score:** 0.86 ➔ Model explains 86% of price variance
- **RMSE:** ~1000 USD ➔ Relatively low error for used car pricing
- Visualization shows good fit between actual vs predicted prices.

### 🚀 Next Development
- Add Streamlit app for interactive prediction
- Test other algorithms: Ridge, Lasso, Random Forest

---

### 🖥️ How to Run
```bash
git clone https://github.com/yourusername/used-car-price-prediction.git
cd used-car-price-prediction
pip install -r requirements.txt
jupyter notebook
