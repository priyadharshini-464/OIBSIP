 HOUSE PRICE PREDICTION USING LINEAR REGRESSION  
📌 PROJECT OVERVIEW  
This project focuses on building a **Linear Regression Machine Learning Model** to predict **house prices** based on multiple numerical and categorical features.  
The goal is to analyze the dataset, preprocess it, train a model, evaluate performance, and visualize actual vs predicted values.

---

## 🧹 DATA EXPLORATION & CLEANING  
The following steps were performed:

- Checked dataset structure  
- Displayed descriptive statistics  
- Handled missing values  
- Converted categorical columns using Label Encoding  
- Normalized data where necessary  

---

## 🎯 FEATURE SELECTION  
Target variable: **price**  
Features used include:

- area  
- bedrooms  
- bathrooms  
- stories  
- parking  
- mainroad  
- guestroom  
- basement  
- hotwaterheating  
- airconditioning  
- prefarea  

---

## 🤖 MODEL TRAINING  
Algorithm used: **Linear Regression**

Steps:

1. Train-Test split (80% train, 20% test)  
2. Model fitted using training data  
3. Predictions generated on test data  

---

## 📊 MODEL EVALUATION  
Metrics used:

- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  
- **R² Score (Accuracy Measure)**  

Higher R² indicates better model performance.  

---

## 📈 VISUALIZATION  
Scatter plot of **Actual vs Predicted Prices** was created to evaluate pattern and prediction accuracy.

This graph helps understand:

- Model fit quality  
- Prediction deviation  
- Relationship between real & predicted values  

---

## 🔍 INSIGHTS  
- Linear Regression model shows a clear positive correlation.  
- Middle-range house prices are predicted more accurately.  
- Some variation exists due to dataset noise and limited features.  

---

## 🛠️ TOOLS & TECHNOLOGIES USED  
- PYTHON  
- PANDAS  
- NUMPY  
- SCIKIT-LEARN (Linear Regression, Train-Test Split, Metrics)  
- MATPLOTLIB for visualization  

---

## 📁 PROJECT FILES  
House_Price_Prediction/
│── house_price_prediction.ipynb
│── README.md
│── Housing.csv
