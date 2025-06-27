# 🔥 Forest Fire Confidence Prediction

A complete machine learning project to predict the **confidence score** of forest fires based on satellite data. The project follows the full ML lifecycle—from data cleaning to deployment.

---

## 📁 Project Overview

- Predicts the likelihood (confidence score) of a forest fire.
- Uses satellite data: brightness, location, time, fire power, and more.
- Built using Python, Pandas, Scikit-learn, and Jupyter Notebooks.

---

## 📊 Dataset

The dataset includes:
- **Temprature**
- **RH(Relative Humidity)**
- **WS(Wind Speed)**
- **Rain** 
- **FFMC(Fine Fuel Moisture Code)**
- **DMC(Duff Moisture Code)**
- **DC(Drought Code)** 
- **ISI(Initial Speed Index)**
- **BUI(Buildup Index)**
- **FWI(Fire Weather Index)**
- **Classes** 

---

## 🛠 Steps Involved

1. **Data Cleaning**
   - Removed irrelevant columns like `day`, `month`, `year`.
   - Changed the datatypes of required columns.
   - Created seprate regions.
   - No missing values.

2. **Feature Engineering**
   - Converted `classes` to numeric.
   - One-hot encoded `type`.
   - Removed some highly correlated columns.

3. **Model Building**
   - Used linear regression,ridge & lasso regression.
   - Evaluated using metrics like R², MAE, MSE.
   - Used `train_test_split` and cross-validation.

4. **Deployment**
   - Deployed via a Flask/FastAPI API.

