# 📈 Yes Bank Stock Price Prediction  

This project explores the impact of financial events on Yes Bank's stock prices and predicts the **monthly closing stock prices** using time series models and machine learning techniques. The dataset includes key stock price details such as opening, closing, highest, and lowest prices since the bank's inception.  

---

## 🏦 **Business Context**

Yes Bank, a prominent player in the Indian financial sector, faced significant turbulence following the fraud case involving its former CEO, Rana Kapoor, in 2018. This project aims to investigate the impact of such events on the bank's stock prices and leverage predictive models to forecast the closing stock price for each month.  

---

## 📄 **Dataset Description**

The dataset contains monthly stock price details for Yes Bank:  
- **Date**: Month and year of the record  
- **Open**: Opening price of the stock for the month  
- **High**: Highest price during the month  
- **Low**: Lowest price during the month  
- **Close**: Closing price of the stock for the month (target variable)  
- **Volume**: Volume of stocks traded  

---

## 🎯 **Objective**

1. Analyze trends and patterns in Yes Bank's stock prices over time.  
2. Investigate the impact of major financial events on stock price behavior.  
3. Build predictive models to forecast the monthly closing price of the stock.  

---

## 🛠 **Libraries Used**

### **Data Manipulation and Aggregation**  
- **Pandas**: Efficient handling and manipulation of time series data.  
- **NumPy**: Computational efficiency for numerical operations.  

### **Visualization**  
- **Matplotlib**: Time series plotting for trend analysis.  
- **Seaborn**: Heatmaps and distribution plots for correlation and insights.  

### **Modeling**  
- **Scikit-learn**:  
  - Model training and validation.  
  - Feature engineering and scaling.  
  - Performance metrics calculation.  

---

## 🧪 **Steps in the Workflow**

### 1️⃣ **Exploratory Data Analysis (EDA)**  
- Inspect the data for missing values and anomalies.  
- Analyze trends in opening, closing, high, and low prices over time.  
- Visualize the impact of major events on stock price trends.  

### 2️⃣ **Data Preprocessing**  
- Handle missing values using interpolation or similar techniques.  
- Perform feature engineering to extract relevant time-based features (e.g., month, year).  
- Scale numerical features to ensure optimal model performance.  

### 3️⃣ **Modeling and Prediction**  
- Compare traditional time series models (ARIMA, SARIMA) with machine learning models (Linear Regression, Random Forest, XGBoost).  
- Optimize models using hyperparameter tuning and cross-validation.  
- Evaluate performance using metrics like RMSE, MAE, and R².  

---

## 📊 **Key Visualizations**

1. **Trend Analysis**: Plot historical trends in stock prices (e.g., line charts for monthly closing prices).  
2. **Event Impact Analysis**: Highlight significant drops or spikes in stock prices coinciding with major financial news.  
3. **Correlation Analysis**: Heatmap showing relationships between opening, closing, high, and low prices.  

---
