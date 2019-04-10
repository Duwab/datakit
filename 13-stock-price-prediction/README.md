# Stock price prediction

## Kaggle competition

Popular Kaggle competition : https://www.kaggle.com/c/two-sigma-financial-news

(talk about the nature of a stock prediction problem)

### Kernels

* EDA (Exploratory Data Analysis)
https://www.kaggle.com/artgor/eda-feature-engineering-and-everything

As an EDA approach, most of the Notebook is about analysing the initial data, using multiple plots.

In the end, it is a simple prediction up/down of the stock value. The algorithm initially was a XGBoost Classifier,
but was replaced by Lightgbm (probably for a performance matter)

In the comments, the author says about algorithm selection:

> GBT (gradient boosting trees) simply work well in most situations and require less data processing :)
> For linear models like logistic regression you need to carefully handle categorical features; for neural nets you'll need a lot of time to find a good architecture and so on. XGB (or lgb) can work on almost any data and the quality is good enough.


