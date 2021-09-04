# StockAdvisor
![Alt -> Project Logo](./img/project_logo.png)

This project aim to analyze *Standard & Poor's 500* historical data in order to:
1. Extract meaninful insights from data
2. Forecasting future S&P 500 Companies' Stocks Indexes 
3. Extract useful features for a further analysis throught Machine Learning Algorithms.

S&P 500 (Standard and Poor's 500) is a free-float, capitalization-weighted index of the top 500 publicly listed stocks in the US (top 500 by market cap).

Analyzed Dataset is a *multi-variate Time Series one* that contains records from *1871-01* to *2018-04*.


## PROJECT CUES


### *[DATASET]*
> **DATASET SIZE**: 1,769 record
>
> **FEATURES**
> | **Date**        | **SP500**       | **Dividend**    | **Earnings**    | **Consumer Price** | **Long Interest Rate** | **Real Price**  | **Real Ernings** | **PE10**        | 
> | ----------- | ----------- | ----------- | ----------- | -----------    | -----------        | ----------- | -----------  | ----------- |
> | Date & Time      | Number       | Number       | Number       | Number          | Number              | Number       | Number        | Number       |
>
> **DATASET YEAR BUILD**: 2018

### *[ALGORITHMS]*
> 1. **SARIMA**
> 2. **Holt-Winters**
> 3. **Facebook Prophet**
> 4. **LSTM**
> 5. **Kalman Filtering**

------------------------------------------------------------------------------------------
## STACK SOFTWARE
| **Component**        |
| -----------      |
| Python           |
| Jupyter Notebook |
| Pandas           |
| SciPy            |
| Matplotlib       |
| NumPy            |
| Kats             |
| FilterPy         |
| PyTorch          | 

------------------------------------------------------------------------------------------
## ANALYSIS INSIGHTS
![Alt -> Analysis 1](./demo/analysis_1.jpg)


## REFERENCES
- [[1]](https://datahub.io/core/s-and-p-500#data-cli) Standard and Poor's (S&P) 500 Index Data
- [[2]](https://facebookresearch.github.io/Kats/) Facebook Kats, one stop shop for time series analysis in Python
- [[3]](https://www.researchgate.net/publication/323671215_Kalman_filter_based_time_series_prediction_of_cake_factory_daily_sale) Wu et. al. - Kalman Filter Based Time Series Prediction ofCake Factory Daily Sale
- [[4]](https://peerj.com/preprints/3190.pdf) Taylor et. al. - Forecasting at Scale

## AUTHOR
- [@r-scalia](https://github.com/rscdev7) Rosario Scalia