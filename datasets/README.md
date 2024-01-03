# Kaggle Competition 

### Description
This competition is provided as a way to explore different time series techniques on a relatively simple and clean dataset.

You are given 5 years of store-item sales data, and asked to predict 3 months of sales for 50 different items at 10 different stores.

What's the best way to deal with seasonality? Should stores be modeled separately, or can you pool them together? Does deep learning work better than ARIMA? Can either beat xgboost?

This is a great competition to explore different models and improve your skills in forecasting.

### Evaluation
Submissions are evaluated on SMAPE between forecasts and actual values. We define SMAPE = 0 when the actual and predicted values are both 0.

### Dataset Description

The objective of this competition is to predict 3 months of item-level sales data at different store locations.

#### File descriptions
train.csv - Training data
test.csv - Test data (Note: the Public/Private split is time based)
sample_submission.csv - a sample submission file in the correct format


#### Data fields
date - Date of the sale data. There are no holiday effects or store closures.
store - Store ID
item - Item ID
sales - Number of items sold at a particular store on a particular date.

[Store Item Demand Forecasting Challenge](https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data)

#### Citation

inversion. (2018). Store Item Demand Forecasting Challenge. Kaggle. https://kaggle.com/competitions/demand-forecasting-kernels-only

```bibtex
@misc{demand-forecasting-kernels-only,
    author = {inversion},
    title = {Store Item Demand Forecasting Challenge},
    publisher = {Kaggle},
    year = {2018},
    url = {https://kaggle.com/competitions/demand-forecasting-kernels-only}
}
```
