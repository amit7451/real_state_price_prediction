# 🏠 House Price Prediction  

## 📌 Project Overview  
This project predicts **house prices** based on various features such as area, number of rooms, location, and other property attributes.  
Using **Linear Regression** and **Polynomial Regression**, the model captures both simple and non-linear relationships between property features and prices.  

The goal is to build a **predictive model** that can assist buyers, sellers, and real estate agencies in estimating property values more accurately.  

---

## 📊 Dataset  
- **Source**: [Kaggle – House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) *(or mention your dataset source)*  
- **Features include**:  
  - Lot Area  
  - Number of Rooms  
  - Year Built  
  - Neighborhood (encoded)  
  - Overall Condition/Quality  
  - Sale Price (target variable)  

---

## 🛠️ Technologies Used  
- **Python 3**  
- **Libraries**:  
  - `numpy`, `pandas` – Data preprocessing & manipulation  
  - `matplotlib`, `seaborn` – Data visualization & EDA  
  - `scikit-learn` – Model building (Linear Regression, Polynomial Regression, Train-Test Split, Metrics)  
  - `Jupyter Notebook` – Development environment  

---

## 🔍 Methodology  
1. **Data Cleaning & Preprocessing**  
   - Handled missing values and outliers.  
   - Encoded categorical variables (e.g., neighborhood).  
   - Scaled numerical features where necessary.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized price distribution and feature correlations.  
   - Checked relationships between house attributes and price.  

3. **Model Building**  
   - Implemented **Linear Regression** for baseline prediction.  
   - Extended to **Polynomial Regression** to capture non-linear trends.  
   - Performed **Train-Test Split** to evaluate model performance.  

4. **Evaluation**  
   - Metrics used: **R² Score, RMSE, MAE**.  
   - Compared performance of Linear vs Polynomial regression.  

---

##  Results  
- Achieved an **R² Score of X.XX** on test data.  
- Polynomial regression improved accuracy compared to simple linear regression.  
- Identified top influential features affecting house prices.  

---


---

## 📈 Future Improvements  
- Implement **Regularization (Ridge, Lasso Regression)**.  
- Try **Logistic Regression** for classification tasks (e.g., predicting high/low price category).  
- Deploy the model using **Flask/Streamlit** for interactive predictions.  

---



