# SC1015 - Mini Project
## :page_with_curl: About
This is our mini project for our module **SC1015 Introduction to Data Science and Artificial Inteligence**. The dataset we are using is S&P 500. We chose this dataset to compare the accuracy of machine learning models and statistical analysis model in predicting stock prices.

## :chart_with_upwards_trend: Problem Statement
Are we able to prove S&P 500 to be a reliable index to buy? Will predicting models justify the reliability? Will Machine Learning model or Statistical model be better?

## :busts_in_silhouette: Our Team
| Name | Parts Done | Github ID |
|---|:---:|---|
| Brandon Jang Jin Tian | Data Preparation, LSTM | @BrandonJang |
| Chung Zhi Xuan | Exploratory Analysis, ARIMA, SARIMA | @spaceman03 |
| Tee Qin Tong Bettina | Exploratory Analysis, ARIMA | @BettinaTee03 |

## Data Science Pipline: Ethical Considerations
**1. Possibility of Reinforced Human Bias**  
Predictive Model utilises past data to predict the possible results in the long run. The past data retrieved may be based on human decisions or human-led economic downturn. Therefore, the data used in the algorithm could possess some of these biases.  
**2. Lack of Transparency**  
External parties involved needs to understand how we gather, store and create the algorithm in order to utilise it or own it. It will be dishonest to them if there is a lack of publishing and might not give them a tailored experience.  
**3. Over reliance on model**  
People who are looking into purchasing S&P 500 index may consider our model. These people may rely on our model to purchase the S&P 500 indexes. If our model gives a prediction that is not close to the real data, it might lead to a loss for investors. Especially since the models do not take into account real life circumstances such as disease outbreaks, which might lead to an unexpected change in prices of indexes. Hence, if potential investors over rely on our model to predict future indexes, it might lead to undesirable outcomes for them.  




## Conclusion
In conclusion, a machine learning model (LSTM) seems to be a better model than the mathematical model (ARIMA/SARIMA) in predicting S&P 500 index price....

## :bulb: What We Learned

## References
- S&P 500 Historical Data: https://www.kaggle.com/datasets/henryhan117/sp-500-historical-data?select=SPX.csv
- Python API for FRED: https://github.com/mortada/fredapi
- Plotly: https://plotly.com/python/
- LSTM:
- ARIMA: https://github.com/0xpranjal/Stock-Prediction-using-different-models; https://towardsdatascience.com/time-series-forecasting-with-arima-sarima-and-sarimax-ee61099e78f6
