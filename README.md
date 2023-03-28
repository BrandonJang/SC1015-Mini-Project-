# SC1015 - Mini Project
## :page_with_curl: About
This is our mini project for our module **SC1015 Introduction to Data Science and Artificial Inteligence**. The dataset we are using is S&P 500. We chose this dataset to compare the accuracy of machine learning models and statistical analysis model in predicting stock prices.

## :chart_with_upwards_trend: Problem Statement
Will a Machine Learning model or a Statistical model be better in predicting S&P 500 index? Are we able to prove S&P 500 to be a reliable index to buy? Will predicting models justify the reliability of S&P 500? 

## :busts_in_silhouette: Our Team
| Name | Parts Done | Github ID |
|---|:---:|---|
| Brandon Jang Jin Tian | Data Preparation, LSTM | @BrandonJang |
| Chung Zhi Xuan | Exploratory Analysis, ARIMA, SARIMA | @spaceman03 |
| Tee Qin Tong Bettina | Exploratory Analysis, ARIMA | @BettinaTee03 |

## Data Science Pipline: Ethical Considerations
**1. Possibility of Reinforced Human Bias**  
Predictive Model utilises past data to predict the possible results in the long run. The past data retrieved may be based on human decisions or human-led economic downturn. Therefore, the data used in the algorithm could possess some of these biases.   
<br>
**2. Lack of Transparency**  
External parties involved needs to understand how we gather, store and create the algorithm in order to utilise it or own it. It will be dishonest to them if there is a lack of publishing and might not give them a tailored experience.  
<br>
**3. Over reliance on model**  
People who are looking into purchasing S&P 500 index may consider our model. These people may rely on our model to purchase the S&P 500 indexes. If our model gives a prediction that is not close to the real data, it might lead to a loss for investors. Especially since the models do not take into account real life circumstances such as disease outbreaks, which might lead to an unexpected change in prices of indexes. Hence, if potential investors over rely on our model to predict future indexes, it might lead to undesirable outcomes for them.  




## :bookmark_tabs: Conclusion
Predicting models can predict S&P 500 index prices to a certain extent of accuracy. We compared a machine learning model (LSTM) to statistical models (ARIMA/SARIMA).  
<br>
We found that the machine learning model (LSTM) seems to be a better model than the statistical models (ARIMA/SARIMA) in predicting S&P 500 index prices.
Between the statistical models, we also found that the ARIMA model is more accurate than the SARIMA model in the case of S&P 500 indexes. SARIMA also takes into the seasonality of the data. However, since S&P 500 is a time series data, which is not seasonal. Hence SARIMA model led to a more inaccurate prediction as compared to ARIMA model.  
<br>
Looking at the LSTM model, which we have concluded to be the most accurate model out of the 3 we have analysed, we can conclude that S&P 500 is a reliable index to buy. The LSTM Model predicts a steady upward trend for the S&P 500 index prices. This tells us that the S&P 500 index is reliable index to buy. The LSTM predicting model is able to justify that S&P 500 index is a reliable index to purchase.  




## :bulb: What We Learned

## References
- S&P 500 Historical Data: https://www.kaggle.com/datasets/henryhan117/sp-500-historical-data?select=SPX.csv
- Python API for FRED: https://github.com/mortada/fredapi
- Plotly: https://plotly.com/python/
- LSTM Predictive Model: https://medium.com/the-handbook-of-coding-in-finance/stock-prices-prediction-using-long-short-term-memory-lstm-model-in-python-734dd1ed6827
- ARIMA & SARIMA Predictive Models: https://github.com/0xpranjal/Stock-Prediction-using-different-models; https://towardsdatascience.com/time-series-forecasting-with-arima-sarima-and-sarimax-ee61099e78f6
