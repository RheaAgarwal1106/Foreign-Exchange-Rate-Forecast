# Foreign Exchange Rate Forecast

## Introduction
This project aims to forecast foreign exchange rates by implementing a variety of statistical models like Autoregressive Distributive Lag Model (ARDL) and machine learning models like Support Vector Regression, XGBoost and Random Forest. A comparison between ARDL model and machine learning models is drawn which shows that ARDL models at par with machine learning algorithms (especially with 
small dataset) due to incorporation of lagged values of target variable and explanatory variables. Bagging and bootstrapping are performed to improve prediction power of the power, the 
highest improvement in RMSE of 30.66% was observed in random forest. Further, a hybrid model of LASSO- SVR is presented which improves RMSE of LASSO by 50.36% and that of SVR by 13.23%. Bootstrapped XGBoost outperforms all the models with the lowest RMSE of 0.02416.

## Objective
- Develop a model which studies inter-dependence of foreign exchange rates with international debt, interest rates, crude oil prices, gold price, imports, exports, Nasdaq Composite Index, Bombay Stock Exchange index, gross domestic product (GDP) and trade openness. Trade openness is defined as summation of imports and exports as a proportion of GDP. 

- Compare the performances of traditional statistical and improvised machine learning algorithms 

- Improve prediction power of machine learning algorithms by implementing bootstrapping and bagging techniques 

- Develop a hybrid model to capture coexisting linear and non- linear dependence of foreign exchange rates with macroeconomic indicators

## Algorithm

<img width="439" height="418" alt="image" src="https://github.com/user-attachments/assets/adc93a51-628d-434a-900b-487037d0b8fa" />

## Results

<img width="583" height="265" alt="image" src="https://github.com/user-attachments/assets/d7a66d3f-efe0-42e7-9ca1-b7caf035fd6e" />

