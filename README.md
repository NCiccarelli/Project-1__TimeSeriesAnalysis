# Project-1__TimeSeriesAnalysis
Time series analysis of the S&amp;P500 index (SARIMA models)

In this Jupyter notebook we analyze the S&P500 index. We use daily data for the S&P500 index from January 1928 to November 2020. The data is obtained from Yahoo Finance (https://finance.yahoo.com/quote/%5EGSPC/history?ltr=1). We use the SARIMAX model from statsmodels to fit and predict daily observations of the S&P500 index. 

The libraries that are used in this Jupyter notebook are the following ones: 

from statsmodels.tsa.statespace.sarimax import SARIMAX

import pandas as pd; 

import matplotlib.pyplot as plt; 

import seaborn as sns;

import warnings;

import itertools;

import numpy as np;

import statsmodels.api as sm.
