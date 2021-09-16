# Stock Advisor
![Alt -> Project Logo](./img/project_logo.png)

This project aim to analyze *Standard & Poor's 500* historical data in order to:
1. Extract meaningful insights from data
2. Forecasting future S&P 500 Companies' Stocks Indexes 

S&P 500 (Standard and Poor's 500) is a free-float, capitalization-weighted index of the top 500 publicly listed stocks in the US (top 500 by market cap).

Analyzed Dataset is a *multi-variate Time Series one* that contains records from *1871-01* to *2018-04*.


## PROJECT CUES


### *[DATASET]*
> **DATASET SIZE**: 1,769 record
>
> **FEATURES**
> | **Date**        | **SP500**       | **Dividend**    | **Earnings**    | **Consumer Price** | **Long Interest Rate** | **Real Price**  | **Real Ernings** | **PE10**        | 
> | ----------- | ----------- | ----------- | ----------- | -----------    | -----------        | ----------- | -----------  | ----------- |
> | Date      | Number       | Number       | Number       | Number          | Number              | Number       | Number        | Number       |
>
> **DATASET YEAR BUILD**: 2018

### *[ALGORITHMS]*
> 1. **SARIMA**
> 2. **Holt-Winters**
> 3. **Facebook Prophet**
> 4. **LSTM**

------------------------------------------------------------------------------------------
## STACK SOFTWARE
| **Component**    |
| -----------      |
| Python           |
| Jupyter Notebook |
| Pandas           |
| SciPy            |
| StatsModels      |
| Matplotlib       |
| NumPy            |
| Kats             |
| FilterPy         |
| PyTorch          | 

------------------------------------------------------------------------------------------
## ANALYSIS INSIGHTS
![Alt -> Analysis 1](./demo/analysis_1.jpg)


## REFERENCES
- [[1]](https://www.wiley.com/en-us/Time+Series+Analysis+and+Forecasting+by+Example-p-9780470540640) Bisgaard, Kulahci - Time Series Analysis and Forecasting by Example (First Edition)
- [[2]](https://www.springer.com/gp/book/9783319298528) Brockwell, Davis - Introduction to Time Series and Forecasting (Third Edition)
- [[3]](https://peerj.com/preprints/3190.pdf) Taylor et. al. (Facebook Research) - Forecasting at Scale
- [[4]](https://datahub.io/core/s-and-p-500#data-cli) Standard and Poor's (S&P) 500 Index Data
- [[5]](https://www.scipy.org/) SciPy, python-based ecosystem for mathematics, science, and engineering
- [[6]](https://facebookresearch.github.io/Kats/) Kats, one stop shop for time series analysis in Python

## AUTHOR
- [@r-scalia](https://github.com/rscdev7) Rosario Scalia